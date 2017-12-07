# contao-theme-boilerplate
this is a boilerplate to load themes via contao manager or composer in contao cms

license

pdir contao theme licence -> see LICENSE file for more informations

## compatible
compatible with Contao 4.4.x

## rename & replace

Rename the following folders to your THEME_NAME:

    ./src/ContaoThemesNet/[THEME_NAME]ThemeBundle

Rename the following files to your THEME_NAME

    ./src/ContaoThemesNet/[THEME_NAME]ThemeBundle/[THEME_NAME]]ThemeBundle.php

Replace THEME_NAME in following files

    ./src/ContaoThemesNet/[THEME_NAME]ThemeBundle/ContaoManager/Plugin.php
    ./src/ContaoThemesNet/[THEME_NAME]ThemeBundle/[THEME_NAME]ThemeBundle.php
    ./composer.json

## structure

    ./src/ContaoThemesNet/[THEME_NAME]ThemeBundle/Resources
        config = symlink to web (Images, JS, CSS etc.)
        public = Symfony config (services etc.)
        views = Templates for Twig
        contao = contao stuff (config, dca etc.)

    # Weitere Beispiele für Verzeichnisse in ./src/
    Typ     	                    Verzeichnis
    Commands	                    Command/
    Controllers	                    Controller/
    Service Container Extensions	DependencyInjection/
    Event Listeners	                EventListener/
    Model Klassen	                Model/
    Übersetzungen (Symfony)	        Resources/translations/
    Übersetzungen (Contao)	        Resources/contao/languages/
    Templates (.html5)              Resources/contao/templates/
    Unit-Tests	                    Tests/

## composer.json

    Key	Wert
    name	        contao-themes-net/[theme-name]-bundle (<vendor>/<name>-bundle)
    description	    Kurze Beschreibung
    type	        contao-bundle
    license	        "pdir contao theme licence" (auch andere Lizenzen möglich)
    require	        Abhängigkeiten
    require-dev     Abhängigkeiten (nur dev-Mode)
    autoload	    PSR-4 (Standard)

## dependencies

- [contao theme helper bundle](https://github.com/pdir/contao-theme-helper-bundle) by [pdir](https://pdir.de/ "Webdesign für Dresden")

## install
