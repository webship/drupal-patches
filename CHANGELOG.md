# Changelog — webship/drupal-patches (`11.4.x`)

All notable changes on the `11.4.x` branch of [`webship/drupal-patches`](https://github.com/webship/drupal-patches), newest first.
Each release lists the commits — merged pull requests and the drupal.org issues they reference — since the previous release.
`#N` links to the pull request; 7-digit `#NNNNNNN` refs are drupal.org issues.

## [Unreleased]

- Remove the Drupal Core patch for [#3465033](https://www.drupal.org/i/3465033) from Drupal 11.4.9 on: core [#3507570](https://www.drupal.org/i/3507570), committed to 11.4.x after 11.4.8, rewrites `AddItemToToolbar` and handles the divider; the patch no longer applies. This release requires `drupal/core >=11.4.9 <11.5`, so sites on 11.4.8 and older keep 11.4.0 with the patch.
