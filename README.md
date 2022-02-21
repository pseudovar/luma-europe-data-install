# Luma Europe Data Install

Utilising [https://github.com/PMET-public/module-data-install](https://github.com/PMET-public/module-data-install).

## Installation/testing

* Take a db dump
* Install module
    - Run `composer config repositories.installer git https://github.com/jasonfordAdobe/luma-europe-data-install.git;composer require jasfordadobe/luma-europe-data-install;`
    - Run `bin/magento se:up`

## Parts

All the language translations are individually created as distinct data-install modules. This module brings them all together.

### Data Installs

* SE_SV https://github.com/jasonfordAdobe/luma-europe-se-sv-data-install
* FR_FR https://github.com/jasonfordAdobe/luma-europe-fr-fr-data-install
* ES_ES https://github.com/jasonfordAdobe/luma-europe-es-es-data-install
* DE_DE https://github.com/jasonfordAdobe/luma-europe-de-de-data-install
* BE_NL https://github.com/jasonfordAdobe/luma-europe-be-nl-data-install
* BE_FR https://github.com/jasonfordAdobe/luma-europe-be-fr-data-install
* NL_NL https://github.com/jasonfordAdobe/luma-europe-nl-nl-data-install
* New Products https://github.com/jasonfordAdobe/luma-europe-new-products-data-install

### Custom Modules Included

* Jason's Commerce Improvements https://github.com/jasonfordAdobe/jason_commerce_improvements
* Store Switcher with Flags https://github.com/jasonfordAdobe/magento2-store-switch-all-store-views
* Quick Category Creation CLI https://github.com/jasonfordAdobe/quickcreatecli
* PageBuilder Animation Component https://github.com/jasonfordAdobe/jason-pagebuilder-animate
* PageBuilder In Page Anchor Compontent https://github.com/jasonfordAdobe/pagebuilder-anchor
* PageBuilder Icons Component https://github.com/jasonfordAdobe/pagebuilder-icons

### To Do

Currently waiting on the data-install module to be able to import translations for categories, attributes/values and tax.

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
* [X] Website URLs
    - [X] GBP
    - [X] EURO
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
