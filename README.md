# Ecomteck Free Responsive Magento 2 Theme

## About and purpose

Ecomteck Free Theme is a free and home-made Magento 2 theme, developed by Ecomteck. Its purpose is providing a starting point for the development of our own client projects. It's a solid base to extend the Magento 2 Blank theme with functionality & styling without breaking future upgrades. It is continuously being worked on, both refined and expanded. All added changes and new features are extends; we try to stay away from overrides until there is absolutely no other way possible.

Ecomteck Free Theme for magento 2 site is simple and clean theme which allow you build your store quickly and easily to custom layout and styles

The theme are using there resources:

bootstrap 4 responsive layout
google fonts
awesome icons font
OWL Carousel

## It comprises of the following extensions:
* Magefan_Blog
* Magefan_Community
* Ves_All
* Ves_Brand
* Ves_Productlist
* Ves_Setup

## SOFTWARE VERSION
Magento 2.1.x, Magento 2.2.x, Magento 2.3.x

## Required System

PHP version 7.0.8 or greater
Composer installation – http://devdocs.magento.com/guides/v2.0/install-gde/prereq/integrator_install_composer.html

## Demo

## Technicalities

* The theme inherits from the Magento Blank theme.
* The theme itself is declared in theme.xml. This file is a necessity for all Magento 2 themes and contains information about inheritance.
* The composer.json file contains the dependency information required for this theme.

## Installation

The modules are intended to be installed using composer. If you do not have composer installed (check by entering the command "composer --help" into your terminal), please install it using the following commands:

```
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```

After installing composer, use the following commands to install Ecomteck to your Magento 2 installation:

```
composer require ecomteck/theme-frontend-ecomteck
```

After installing "Ecomteck Frontend Ecomteck" theme, you can verify that the installation succeeded by going to the Magento 2 back-end and navigating to **Content -> Design -> Themes**. If it listed there, you should be happy.

Normally, this theme will never be set as a the main theme for a client, but to set this theme for development purposes on the storefront, go to: **Content -> Design -> Configuration** and set the Ecomteck frontend ecomteck theme on the Store View you wish to use. Do not forget to flush the cache afterwards.

Then you can setup there CMS Blocks for the theme by copy content on there .txt files under folder: 
app/code/design/frontend/Ecomteck/ecomteck/Sample_Data/cms-blocks/

and add there CMS Pages for the theme by copy content on there .txt files under folder:
app/code/design/frontend/Ecomteck/ecomteck/Sample_Data/cms-pages/

Also copy sample images files by decompress the file "app/code/design/frontend/Ecomteck/ecomteck/Sample_Data/Sample_Media.zip" into webroot folder.
