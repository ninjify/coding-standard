![](https://heatbadger.now.sh/github/readme/ninjify/coding-standard/)

<p align=center>
  <a href="https://packagist.org/packages/ninjify/coding-standard"><img src="https://badgen.net/packagist/dm/ninjify/coding-standard"></a>
  <a href="https://packagist.org/packages/ninjify/coding-standard"><img src="https://badgen.net/packagist/v/ninjify/coding-standard"></a>
</p>
<p align=center>
  <a href="https://packagist.org/packages/ninjify/coding-standard"><img src="https://badgen.net/packagist/php/ninjify/coding-standard"></a>
  <a href="https://github.com/ninjify/coding-standard"><img src="https://badgen.net/github/license/ninjify/coding-standard"></a>
  <a href="https://bit.ly/ctteg"><img src="https://badgen.net/badge/support/gitter/cyan"></a>
  <a href="https://bit.ly/cttfo"><img src="https://badgen.net/badge/support/forum/yellow"></a>
  <a href="https://contributte.org/partners.html"><img src="https://badgen.net/badge/sponsor/donations/F96854"></a>
</p>

<p align=center>
Website 🚀 <a href="https://contributte.org">contributte.org</a> | Contact 👨🏻‍💻 <a href="https://f3l1x.io">f3l1x.io</a> | Twitter 🐦 <a href="https://twitter.com/contributte">@contributte</a>
</p>

## Usage

To install latest version of `ninjify/coding-standard` use [Composer](https://getcomposer.com).

```
composer require --dev ninjify/coding-standard
```

## Versions

| State       | Version      | Branch   | PHP      |
|-------------|--------------|----------|----------|
| dev         | `^0.12`      | `master` | `>= 7.2` |
| stable      | `^0.11`      | `master` | `>= 7.2` |

## Documentation

### Usage

| File          | Usage  |
|---------------|--------|
| ruleset       | global |
| contributte   | Contributte, Apitte, Nettrine |

Create `ruleset.xml` in root of your project.

```
<?xml version="1.0"?>
<ruleset name="Acme">
    <!-- Ninjify Coding Standard -->
    <rule ref="./vendor/ninjify/coding-standard/ruleset.xml"/>

    <!-- OR -->
    
    <!-- Contributte Coding Standard -->
    <rule ref="./vendor/ninjify/coding-standard/contributte.xml"/>

    <!--Exclude folders -->
    <exclude-pattern>/tests/tmp</exclude-pattern>
</ruleset>
```

### Integration

Take a look at `phpstorm` folder, there should be prepared codestyle.


## Development

See [how to contribute](https://contributte.org) to this package. This package is currently maintained by these authors.

<a href="https://github.com/f3l1x">
    <img width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **contributte** development team.
Also thank you for using this package.
