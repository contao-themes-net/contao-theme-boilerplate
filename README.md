# contao-theme-boilerplate
this is a boilerplate to load themes via contao manager or composer in contao cms

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

