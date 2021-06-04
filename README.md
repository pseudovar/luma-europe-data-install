# Luma Europe Data Install

Utilising [https://github.com/PMET-public/module-data-install](https://github.com/PMET-public/module-data-install).

## Installation/testing

* Take a db dump
* Install module
    - Run `composer config repositories.installer git https://github.com/jasonfordAdobe/luma-europe-data-install.git;composer require jasfordadobe/luma-europe-data-install;`
    - Run `bin/magento se:up`

## Parts

### To Do


* [ ] Product Attribute Label Translations
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [ ] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv
* [ ] Product Attribute Option Translations
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [ ] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv
* [ ] Category Translations
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [ ] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv
* [ ] Website URLs
    - [ ] GBP
    - [ ] EURO
* [ ] Currency Configuration
    - [ ] Import conversion of Krona
* [ ] Make composer require for each sub-repo
    - [ ] How do we provide options for people to install just the languages they want?
    - [ ] luma_be_nl
    - [ ] luma_be_fr
    - [ ] luma_fr_fr
    - [ ] luma_de_de
    - [X] luma_nl_nl
    - [ ] luma_es_es
    - [ ] luma_se_sv

### Done

* [X] Create install script for the Chrome extension
    - [X] Remove MagentoEse store switcher
    - [X] Add custom IMI store switcher
    - [X] Add custom PB modules
    - [X] Add Commerce Improvements module
* [X] Configuration
    - [X] Global
    - [X] luma_be_nl
    - [X] luma_be_fr
    - [X] luma_fr_fr
    - [X] luma_de_de
    - [X] luma_nl_nl
    - [X] luma_es_es
    - [X] luma_se_sv
* [X] Split into different repos for each language
    - [X] Global
    - [X] luma_be_nl
    - [X] luma_be_fr
    - [X] luma_fr_fr
    - [X] luma_de_de
    - [X] luma_nl_nl
    - [X] luma_es_es
    - [X] luma_se_sv
* [X] Websites/Stores
* [X] Category Import
* [X] Products (export)
    - [X] Translations
    - [X] New 3D product
    - [X] New Images
* [X] New Products
    - [X] Custom Attribute (Flavour)
    - [X] Energy Bar
    - [X] Water Bottle
* [X] Pages
    - [X] luma_be_nl
    - [X] luma_be_fr
    - [X] luma_fr_fr
    - [X] luma_de_de
    - [X] luma_nl_nl
    - [X] luma_es_es
    - [X] luma_se_sv
* [X] Product translations (title, description)
    - [X] luma_be_nl
    - [X] luma_be_fr
    - [X] luma_fr_fr
    - [X] luma_de_de
    - [X] luma_nl_nl
    - [X] luma_es_es
    - [X] luma_se_sv