# Research Software Development (in Python) Course

SWD3: Research Software Development documentation and course notes.

[![DOI](https://zenodo.org/badge/<GITHUB_ID>.svg)](https://zenodo.org/badge/latestdoi/<GITHUB_ID>)

## Building instructions

*Note that this repository is also configured to build via a GitHub action. HTML pages are not tracked via version control*.

You can use pip to install the package `heading_container` to run the scripts in this project. These scripts pull in the content from presentations and format them as an article. The environment with this package must be active before using Quarto to render the material.

Install the most recent development version (may not be stable):

```bash
pip install <PACKAGE_NAME>@git+https://github.com/<USER_NAME>/<REPO_NAME>
```

Or install a specific version (version 0.1.0 in this example; please check the releases page):

```bash
pip install https://github.com/<USER_NAME>/<REPO_NAME>/archive/refs/tags/v0.1.0.tar.gz

# or

pip install <PACKAGE_NAME>@git+https://github.com/m<USER_NAME>/<REPO_NAME>@v0.1.0
```

## Author

Below is a list of contributors (in chronological order of addition) with associated Contributor Role Taxonomy (CRediT) roles. Please see the [CRediT website](https://credit.niso.org/) for definitions of roles.

- [Maeve Murphy Quinlan](https://orcid.org/0000-0003-2958-1008): conceptualization, writing (original draft), writing (review and editing), data curation, methodology.
  - Creation of website, Python workflows, GitHub actions.
  - Redesign of course.

## Citation instructions

Please use the suggested citation in the sidebar (under "Cite this repository"), or view the CITATION.cff file.

## License

This material is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/), and is copyrighted by the University of Leeds.