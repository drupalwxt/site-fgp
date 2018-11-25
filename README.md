Composer Project template for Drupal
====================================

[![Build Status][ci-badge]][ci]

Drupal WxT codebase for `<site-fgp>`.

## Requirements

* [Composer][composer]
* [Node][node]

## New Project

```sh
composer create-project drupalwxt/wxt-project:8.x-dev site-fgp
```

## Docker support via `drupal-scaffold-docker`

This project makes use of the `drupal-scaffold-docker` plugin for automatically
downloading and instantiating a Docker based Drupal infrastructure.

- [README.md][docker-scaffold-readme]
- [template/docker/README.md][docker-readme]

## Maintenance

List of common commands are as follows:

| Task                                            | Composer                                               |
|-------------------------------------------------|--------------------------------------------------------|
| Latest version of a contributed project         | ```composer require drupal/fgp:8.*```         |
| Specific version of a contributed project       | ```composer require drupal/fgp:8.1.0-beta5``` |
| Updating all projects including Drupal Core     | ```composer update```                                  |
| Updating a single contributed project           | ```composer update drupal/fgp```              |
| Updating Drupal Core exclusively                | ```composer update drupal/core```                      |


[ci]:                       https://travis-ci.org/drupalwxt/site-fgp
[ci-badge]:                 https://travis-ci.org/drupalwxt/site-fgp.svg?branch=8.x
[composer]:                 https://getcomposer.org
[node]:                     https://nodejs.org
[docker-scaffold-readme]:   https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/README.md
[docker-readme]:            https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/template/docker/README.md
