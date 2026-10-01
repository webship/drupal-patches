# Changelog — webship/drupal-patches (`12.0.x`)

All notable changes on the `12.0.x` branch of [`webship/drupal-patches`](https://github.com/webship/drupal-patches), newest first.
Each release lists the commits — merged pull requests and the drupal.org issues they reference — since the previous release.
`#N` links to the pull request; 7-digit `#NNNNNNN` refs are drupal.org issues.

## [Unreleased]

- Carry the 17 core patches from `11.4.x` that apply to Drupal 12.0.0-beta1, from the same files on the `patches` branch
- Not carried, each needs a re-roll for 12: [#2741877](https://www.drupal.org/i/2741877), [#3465033](https://www.drupal.org/i/3465033), [#3543210](https://www.drupal.org/i/3543210), [#3559809](https://www.drupal.org/i/3559809); [#3080606](https://www.drupal.org/i/3080606) (Layout Builder) is dropped
- Run the patch test on PHP 8.5, which Drupal 12 requires, and name the install-log artifact by run id outside pull requests
