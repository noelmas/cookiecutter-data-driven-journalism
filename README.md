# DDJ

A Cookiecutter template for Jupyter projects for data-drien journalism tweaked and forked from [JAStark's](https://github.com/noelmas/cookiecutter-data-driven-journalism/commits?author=JAStark) original data-driven journalism template.

## Requirements

* cookiecutter 1.6.0
* python 3.6

## Usage

To begin a new data-driven journalism project, open a terminal, navigate to where you want the project to reside, and type:

`cookiecutter gh:noelmas/cookiecutter-ddj`

- `full_name`: e.g. `Jennifer A. Stark` (this will be used to populate the `AUTHORS` file)
- `github_username`: e.g. `noelmas` (will populate the `AUTHORS` file)
- `project_name`: the name of the published story for easy cross-referencing, or, if you don't know it yet, something relatable. This text will populate the `README` file.
- `project_slug`: leave empty. It will create a project directory named using `project_name` with underscores automatically added between words.
- `short_description`: a short description of the Project. This text will populate the `README.md`
- `date`: leave as-is.

## Project Structure
```
.
├── .gitignore
├── AUTHORS.md
├── README.md
├── data
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── viz
├── keys.txt
├── notebooks
└── requirements.txt

## Licence

This project is licensed under the terms of [MIT License](/LICENSE)
