# Plugin Template for Shopware 6

![Plugin Template for Shopware 6](https://repository-images.githubusercontent.com/403016477/019d5dc6-0f4c-489d-a7d8-d431994c1c5b)

Use thisRepository for a starting point to start developing Shopware 6 Plugins.

For more Boilerplate Code look into my [Plugin Boilerplate](https://github.com/brianvarskonst/BvskPluginBoilerplate) Repository.

The plugin is compatible with PHP version 7.4 and higher.

## Use
### Git Clone
```bash
$ git clone git@github.com:brianvarskonst/shopware6-plugin.git ./custom/plugins
$ cd shopware6-plugin && rm -rf .git
```

## How to install the Plugin
### Composer install (recommended)
```
bin/console plugin:refresh
bin/console plugin:install --activate Plugin
```
#### Building
The composer install does not come with compiled javascript. You will have to build/compile your administration and storefront javascript.

In case you are using the production template, the command below should do the trick.
```
bin/build.sh
```
#### Build Assets
Building the javascript & css will still be needed.
```
bin/build.sh
```

## Contributions
Please help with code, love, shares, feedback and bug reporting.

## License
The MIT License (MIT). Please see [License File](LICENSE) for more information.

