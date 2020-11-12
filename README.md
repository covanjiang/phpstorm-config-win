# phpstorm-settings-win

- Windows PHPStorm settings.

### Plugins
- .env file support
- BashSupport
- Chinese PHP Document
- Color Highlighter
- Git Commit Template
- IdeaVim
- Ideolog
- Laravel
- Material Theme UI
- Atom Material Icons
- PHP Annotations
- Rainbow Brackets
- Symfony Support
- Translation

### Tools
1. PHP_CodeSniffer

- Install `php_codesniffer` locally on Windows.

```shell
# Need to install PHP and Composer dependencies. 
# Don't forget to configure environment variables.
composer require squizlabs/php_codesniffer
```

2. PHP CS Fixer

- Install `php-cs-fixer` locally on Windows.
```shell
composer require friendsofphp/php-cs-fixer
```

- Set the keymap for `php-cs-fixer`.

### Tips
1. Ignore the warning that the line length exceeds 120.
```xml
<?xml version="1.0"?>
<ruleset name="CustomStandard">
 <rule ref="PSR2">
    <exclude name="Generic.Files.LineLength"/>
 </rule>
</ruleset>
```

- Save it and add to `php_codesniffer` rules.
