# Hungarian (magyar) Magento2 Language Pack (hu_HU)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Hungarian (magyar) translations used can be found [here](https://crowdin.com/project/magento-2/hu).
This translation is usefull for people living in the Hungary (Magyarország).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.0.2](https://crowdin.com/project/magento-2/hu#/2.0.2) at Crowdin and based on the Magento 2.0.2 sourcefiles.
There have been  3434 strings translated of the 7776 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/44)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_hu_hu:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_hu_hu/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_hu_hu`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/hu_HU/hu_HU.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Hungarian (Hungary)*'

# Contribute
To help push the '*Hungarian (magyar) Magento2 Language Pack (hu_HU)*' forward please goto [this](https://crowdin.com/project/magento-2/hu) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).