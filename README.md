# Mugar_ArgentinaSetup for Magento2

Metapackage to install a set of modules that will improve the configuration of your store for websites that are running in Argentina.

Current included modules are:

* [Mugar_ArgentinaRegions](https://github.com/holamugar/module-argentina-regions)

## Installation

Use [composer](https://getcomposer.org/) to install Mugar_ArgentinaSetup.

```
composer require mugar/module-argentina-setup
```

Then you'll need to activate the module.

```
bin/magento module:enable Mugar_ArgentinaSetup
bin/magento setup:upgrade
bin/magento cache:clean
```

## Uninstall

```
bin/magento module:uninstall Mugar_ArgentinaSetup
```

If you used Composer for installation Magento will remove the files and database information. 

## Support

You can request to be added to [Slack](https://mugar.slack.com/).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### How to create a PR

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

[MIT](https://choosealicense.com/licenses/mit/)