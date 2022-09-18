# Ready-to-use documentation template

![Version flag](https://img.shields.io/badge/version-v1.0-green?style=flat) ![Date flag](https://img.shields.io/badge/date-2022%2F08-yellow?style=flat) ![Lang flag](https://img.shields.io/pypi/pyversions/Django?style=flat) ![Lang flag](https://img.shields.io/badge/mkdocs->%3D%201.3.1-8CA1AF?style=flat) ![Lang flag](https://img.shields.io/badge/mkdocs%7Ei18n->%3D%200.0.4-26A69A?style=flat) ![Lang flag](https://img.shields.io/badge/mike->%3D%201.1.2-809CC9?style=flat) ![Lang flag](https://img.shields.io/badge/theme-material-2196F3?style=flat)   

| Information   | Detail                                                                                                             |
| :------------ | :----------------------------------------------------------------------------------------------------------------- |
| Subject       | Ready-to-use documentation template project                                                                        |
| Version       | 1.0                                                                                                                |
| Date          | 2022-08-22                                                                                                         |
| Maintainers   | [ISAsxm](https://github.com/ISAsxm)                                                                                |

---

## Foreword

The overall objective of this project is to provide a ready-to-use documentation model with English/French bilingual parameters and versioning parameters.  

---

## Information concerning this project

You can modify the `index.md` and `index.fr.md` files and create new `.en.md` and `.fr.md` files to build your project documentation (don't forget to add them to the `mkdocs.yml` file under the `nav` key).

You can modify the site name, GitHub repo url and the copyright in the `mkdocs.yml` file, under the respective keys `site_name`, `repo_url` and `copyright`.

You can change the logo and favicon under the respective paths `docs/assets/logo.svg` and `docs/images/favicon.svg`. 

For changes to the theme or plugins, please refer to the official documentation listed below.

This project is developped through the **[mkdocs](https://www.mkdocs.org)** OpenSource project.

The theme used is **[material](https://github.com/squidfunk/mkdocs-material)**.

Plugins installed are **[mkdocs-i18n](https://pypi.org/project/mkdocs-i18n/)** for translations, **[mike](https://github.com/jimporter/mike)** for versioning and [mkdocs-glightbox](https://github.com/blueswen/mkdocs-glightbox) for image zoom functionality.

!!! warning "Pay attention please"
    Please refer to their official documentation before modify this project.

---

## Project installation

1. Clone this git directory using the following command:

``` sh
git clone [path_to_the_repository]
```

2. Install the requirements, run the following commands at the root of the project:

``` sh
pip3 install -r requirements.txt
```

> _**Important**
    If you didn't get this folder from **Git**, you need to run the `git init` command on the root of this project before setting up the project to be able to use versioning under **mike** plugins._
---

## Project setup  

Please refer to the Mkdocs and Mike section to start the development server.

### Mkdocs >=1.3.1

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

#### Mkdocs basic command line

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Mkdocs Material (theme) >=8.4.1

For full documentation visit [mkdocs-material](https://squidfunk.github.io/mkdocs-material/).

### Plugins 

#### Mike (versioning) >=1.1.2 

For full documentation visit [mike](https://github.com/jimporter/mike).

######  Mike basic command line 

* `mkdocs new [dir-name]` - Create a new project.
* `mike serve` - Start the live-reloading docs server include versioning.
* `mike deploy --update-aliases [version-number] latest` - Publish the first version through version-number.
* `mike set-default latest` - Set the default version to latest.
* `mike deploy --update-aliases [new-version-number] latest` - Publish a new version through new-version-number.
* `mike deploy --push --update-aliases [version-number] latest` - Publish and git push on gh branch the first version through version-number.
* `mike set-default --push latest` - Set the default version to latest and git push on gh branch.
* `mike deploy --push --update-aliases [new-version-number] latest` - Publish and git push on gh branch a new version through new-version-number.


#### Mkdocs-i18n (internalisation) >=0.0.4

For full documentation visit [mkdocs-i18n](https://pypi.org/project/mkdocs-i18n/).

#### MkDocs GLightbox (image lightbox)

For full documentation visit [mkdocs-glightbox](https://github.com/blueswen/mkdocs-glightbox)