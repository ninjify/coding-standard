# Coding standard

Tuned & very strict coding standards for PHP projects. Trusted by [Contributte](https://github.com/contributte), [Apitte](https://github.com/apitte), [Nettrine](https://github.com/nettrine)
and many others projects.

This library use sniffs from [slevomat/coding-standards](https://github.com/slevomat/coding-standards) and ruleset definitions are based on [consistence/coding-standard](https://github.com/consistence/coding-standard) and [doctrine/coding-standard](https://github.com/doctrine/coding-standard). Thank yu guys.

-----

[![Downloads total](https://img.shields.io/packagist/dt/ninjify/coding-standard.svg?style=flat-square)](https://packagist.org/packages/ninjify/coding-standard)
[![Latest stable](https://img.shields.io/packagist/v/ninjify/coding-standard.svg?style=flat-square)](https://packagist.org/packages/ninjify/coding-standard)

## Install

```bash
composer require --dev ninjify/coding-standard
```

## Usage

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
