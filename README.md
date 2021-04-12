# Luma Europe Data Install

Utilising [https://github.com/PMET-public/module-data-install](https://github.com/PMET-public/module-data-install).

## Installation/testing

* Take a db dump
* Install module
    - Run `composer config repositories.installer git https://github.com/jasonfordAdobe/luma-europe-data-install.git;composer require jasfordadobe/luma-europe-data-install;`
    - Run `bin/magento se:up`

## Parts

### To Do

* [ ] Pages
* [ ] Product Attribute Label Translations
* [ ] Product Attribute Option Translations
* [ ] New Products
    - [ ] Energy Bar
    - [ ] Water Bottle
* [ ] Category Import
* [ ] Category Translations
* [ ] Website URLs
* [ ] Split into different repos for each language
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [X] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv
* [ ] Make composer require for each sub-repo
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [X] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv

### Done

* [X] Configuration
* [X] Products (export)
    - [X] Translations
    - [X] New 3D product
    - [X] New Images
* [X] Websites/Stores