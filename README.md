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

3. Change `client_id` and `client_secret` credentials in the `credentials.json` -file.

## Running the project

1. Activate the spopularity environment

```sh
conda activate spopularity
```

2. Run the Jupyter notebook

```sh
jupyter notebook look-at-the-data.ipynb
```

