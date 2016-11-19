# Coding standard

Tuned & very strict coding standards for PHP projects

-----

[![Downloads total](https://img.shields.io/packagist/dt/ninjify/coding-standard.svg?style=flat-square)](https://packagist.org/packages/ninjify/coding-standard)
[![Latest stable](https://img.shields.io/packagist/v/ninjify/coding-standard.svg?style=flat-square)](https://packagist.org/packages/ninjify/coding-standard)

## Install

```bash
composer require --dev ninjify/coding-standard
```

## Strictness

| File          | Strictness |
|---------------|------------|
| ruleset       | strict     |
| ruleset-nette | 90%        |

## Usage

Create `ruleset.xml` in root of your project.

```
<?xml version="1.0"?>
<ruleset name="YourProject">
    <!-- Extending rulesets -->
    <rule ref="./../../ninjify/coding-standard/ruleset.xml" />

    <!-- My rules -->
    
    <!-- Exclude folders -->
    <exclude-pattern>*/tests/tmp</exclude-pattern>
</ruleset>
```

