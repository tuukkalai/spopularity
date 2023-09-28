# Spopularity

Repo for Introduction to Data Science course miniproject.

## Project initial setup

1. Set up a Conda environment with `environments.yml`-file

```sh
conda env create --name spopularity --file=environments.yml
```

2. Rename `credentials_example.json` to `credentials.json`

```sh
mv credentials_example.json credentials.json
```

3. Change credentials in the `credentials.json` -file.

 ```txt
client_id       Spotify WebAPI client_id
client_secret   Spotify WebAPI client_secret
rapid-api-key   Key for Rapid API (https://rapidapi.com/LDVIN/api/billboard-api/)
```

## Running the project

1. Activate the spopularity environment

```sh
conda activate spopularity
```

2. Run the Jupyter notebook

```sh
jupyter notebook look-at-the-data.ipynb
```

