# Project Howdy: Generate "hello world" data for many human languages, with current country flag emoji.

Used at [my personal website](https://roguh.com).

A simple Python script that converts country codes into emoji and English text into multiple languages, using Google Translate.

## Run

```
pipenv run ./generate_hugo_config_yaml.py > out
```

View output: `cat out`.

View translation errors: `cat errors.log`.

## Experiment

```
pipenv run ipython -i interactive.py
```


# A.K.A. *project pandoglot*

# Useful:

- https://pypi.org/project/googletrans/
- https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2
- Wikipedia pages for languages
- https://en.wikipedia.org/wiki/Demographics_of_the_Arab_League#Arab_League_populations
