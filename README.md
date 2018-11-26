Composer Project template for Drupal FGP
========================================

[![Build Status][ci-badge]][ci]

Drupal 8 FGP codebase for `site-fgp`.

## Requirements

* [Composer][composer]
* [Node][node]

## Maintenance

List of common commands are as follows:

| Task                                            | Composer                                               |
|-------------------------------------------------|--------------------------------------------------------|
| Latest version of a contributed project         | ```composer require drupal/fgp:2.2.*```                |
| Specific version of a contributed project       | ```composer require drupal/fgp:2.2.1```                |
| Updating all projects including Drupal Core     | ```composer update```                                  |
| Updating a single contributed project           | ```composer update drupal/fgp```                       |
| Updating Drupal Core exclusively                | ```composer update drupal/core```                      |


[ci]:                       https://travis-ci.org/drupalwxt/site-fgp
[ci-badge]:                 https://travis-ci.org/drupalwxt/site-fgp.svg?branch=8.x
[composer]:                 https://getcomposer.org
[node]:                     https://nodejs.org
[docker-scaffold-readme]:   https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/README.md
[docker-readme]:            https://github.com/drupal-composer-ext/drupal-scaffold-docker/blob/8.x/template/docker/README.md
