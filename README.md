<!--lint disable double-link awesome-toc-->

# Awesome Composer [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) ⭐ 437,918 | 🐛 71 | 📅 2026-01-28 [![Build on Windows](https://github.com/jakoch/awesome-composer/actions/workflows/awesome-bot.yml/badge.svg?branch=main)](https://github.com/jakoch/awesome-composer/actions/workflows/awesome-bot.yml) ⭐ 900 | 🐛 0 | 📅 2025-12-15 [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)](origin) with stars

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php](https://github.com/ziadoz/awesome-php) ⭐ 32,368 | 🐛 68 | 📅 2026-01-17.

*Please read the [contribution guidelines](https://github.com/jakoch/awesome-composer/blob/main/.github/CONTRIBUTING.md) ⭐ 900 | 🐛 0 | 📅 2025-12-15 before contributing.*

## Composer

* [GitHub](https://github.com/composer/composer) ⭐ 29,313 | 🐛 145 | 🌐 PHP | 📅 2026-02-15
* [Issues](https://github.com/composer/composer/issues) ⭐ 29,313 | 🐛 145 | 🌐 PHP | 📅 2026-02-15
* [Source](https://github.com/composer/composer/tree/HEAD/src/Composer) ⭐ 29,313 | 🐛 145 | 🌐 PHP | 📅 2026-02-15
* [Composer Installers](https://github.com/composer/installers) ⭐ 1,438 | 🐛 23 | 🌐 PHP | 📅 2026-01-01 - Composer installers for multiple frameworks.
* [Official Website](https://getcomposer.org/)
* [Documentation](https://getcomposer.org/doc/)
* [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
* [Find Packages on Packagist](https://packagist.org/)
* [CheatSheet](https://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.

### Support

#### Stack Overflow

* You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
* [Ask a new question](https://stackoverflow.com/questions/ask?tags=composer-php+php)
* [Find questions tagged `composer-php`](https://stackoverflow.com/questions/tagged/composer-php)

#### IRC

* IRC channels are on `irc.freenode.org`: [#composer](https://irc.com/#composer) for users and [#composer-dev](https://irc.com/#composer-dev) for development.

***

## Plugins

* [Prestissimo](https://github.com/hirak/prestissimo) ⭐ 6,135 | 🐛 40 | 🌐 PHP | 📅 2022-12-03 - A parallel downloader using `phpext_curl`.
* [Symfony-Flex](https://github.com/symfony/flex) ⭐ 4,223 | 🐛 19 | 🌐 PHP | 📅 2025-11-16 - Provides [recipe-based](https://github.com/symfony/recipes) ⭐ 1,018 | 🐛 34 | 🌐 PHP | 📅 2026-02-09 installation and configuration management for Symfony packages.
* [PackageVersions](https://github.com/Ocramius/PackageVersions) ⭐ 3,185 | 🐛 3 | 🌐 PHP | 📅 2026-02-16 - Provides a very quick and easy access to installed composer dependency versions.
* [Composer-Patches](https://github.com/cweagans/composer-patches) ⭐ 1,676 | 🐛 52 | 🌐 PHP | 📅 2026-01-30 - The plugin applies a patch from a local or remote file to any required package.
* [PackageVersions Deprecated](https://github.com/composer/package-versions-deprecated) ⭐ 1,526 | 🐛 1 | 🌐 PHP | 📅 2022-01-17 - Is a fork of Ocramius/PackageVersions providing compatibility with Composer 1 and 2 on PHP 7+.
* [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) ⭐ 1,088 | 🐛 12 | 🌐 PHP | 📅 2024-06-22 - A library for easily managing git hooks in your composer config.
* [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) ⭐ 993 | 🐛 72 | 🌐 PHP | 📅 2026-01-23 - Merges multiple `composer.json` files at Composer runtime.
* [Graph-Composer](https://github.com/clue/graph-composer) ⭐ 935 | 🐛 7 | 🌐 PHP | 📅 2025-08-06 - Provides a graph visualization for your project's `composer.json` and its dependencies.
* [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) ⭐ 889 | 🐛 15 | 🌐 PHP | 📅 2023-02-28 - A npm/Bower Dependencies Manager for Composer.
* [PHPCodeSniffer-Composer-Installer](https://github.com/PHPCSStandards/composer-installer) ⭐ 593 | 🐛 10 | 🌐 PHP | 📅 2026-02-13 - The plugin enables you to install [PHP\_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) ⭐ 10,798 | 🐛 269 | 🌐 PHP | 📅 2024-04-01 coding standards (rulesets).
* [Composer-Changelogs](https://github.com/pyrech/composer-changelogs) ⭐ 591 | 🐛 1 | 🌐 PHP | 📅 2025-11-27 - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file.
* [Composer-Dependency-Analyzer](https://github.com/shipmonk-rnd/composer-dependency-analyser) ⭐ 590 | 🐛 18 | 🌐 PHP | 📅 2026-01-28 - The plugin helps to find dependency issues, including dead, unused, shadow and misplaced dependencies.
* [Composer Registry Manager](https://github.com/slince/composer-registry-manager) ⭐ 559 | 🐛 4 | 🌐 PHP | 📅 2023-03-04 - Enables you to switch between different composer repositories.
* [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) ⭐ 522 | 🐛 7 | 🌐 PHP | 📅 2026-02-04 - Adds support for managing dependencies for multiple packages in a single repository or isolate bin dependencies.
* [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) ⭐ 312 | 🐛 13 | 🌐 PHP | 📅 2023-12-13 - The plugin helps to manage dependencies for multiple packages in a single repository.
* [Composer-Patches](https://github.com/vaimo/composer-patches) ⭐ 298 | 🐛 31 | 🌐 PHP | 📅 2026-02-03 - Applies a patch from a local or remote file to any package that is part of a given composer project.
* [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) ⭐ 235 | 🐛 18 | 🌐 PHP | 📅 2021-12-02 - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z").
* [Private-Composer-Installer](https://github.com/ffraenz/private-composer-installer) ⭐ 231 | 🐛 4 | 🌐 PHP | 📅 2024-09-02 - Install helper outsourcing sensitive keys from the package URL into environment variables.
* [Composer Preload](https://github.com/Ayesh/Composer-Preload) ⭐ 209 | 🐛 4 | 🌐 PHP | 📅 2022-05-16 - The plugin generates a `vendor/preload.php` file to warm up the Opcache.
* [Composer-Diff](https://github.com/IonBazan/composer-diff) ⭐ 184 | 🐛 3 | 🌐 PHP | 📅 2025-08-21 - Compares `composer.lock` changes and generates a Markdown report for usage in a pull request description.
* [Composer-Warmup](https://github.com/jderusse/composer-warmup) ⭐ 180 | 🐛 2 | 🌐 PHP | 📅 2021-01-18 - The plugin adds the command `warmup-opcode` to Composer, which triggers the compilation of all PHP files discovered in your project into the Opcache.
* [Foxy](https://github.com/fxpio/foxy) ⭐ 177 | 🐛 5 | 🌐 PHP | 📅 2024-07-29 - Composer plugin that executes npm/yarn packages installation operations, when composer package is installed or updated.
* [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) ⭐ 164 | 🐛 9 | 🌐 PHP | 📅 2017-12-04 - Allows you to share selected packages between your projects by creating symlinks.
* [Imposter-Plugin](https://github.com/typisttech/imposter-plugin) ⭐ 157 | 🐛 8 | 🌐 PHP | 📅 2023-10-06 - Wrapping all composer vendor packages inside your own namespace. Intended for WordPress plugins.
* [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) ⚠️ Archived - Removes tests & documentation folders from the vendor dir.
* [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) ⭐ 139 | 🐛 5 | 🌐 PHP | 📅 2025-06-16 - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (vendor folder).
* [Composer-Cleaner](https://github.com/dg/composer-cleaner) ⭐ 135 | 🐛 7 | 🌐 PHP | 📅 2026-01-04 - The tool removes unnecessary files and directories from the vendor directory.
* [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) ⭐ 107 | 🐛 10 | 🌐 PHP | 📅 2022-08-25 - Installer for Node.js and npm.
* [Composer-Composition](https://github.com/bamarni/composition) ⭐ 104 | 🐛 0 | 🌐 PHP | 📅 2016-03-18 - Provides an API, for checking your environment at runtime.
* [Composer-REPL](https://github.com/ramsey/composer-repl) ⭐ 104 | 🐛 0 | 📅 2025-03-06 - The plugin provides the `composer repl` command, which gives you a PHP language shell (read-eval-print loop).
* [Composer-Link](https://github.com/SanderSander/composer-link) ⭐ 87 | 🐛 3 | 🌐 PHP | 📅 2026-01-19 - Adds the ability to link local packages for development.
* [Composer-Skrub](https://github.com/ssx/skrub) ⭐ 86 | 🐛 4 | 🌐 PHP | 📅 2022-11-10 - The plugin helps to remove junk from Composer installations and trim build sizes.
* [Production-Dependencies-Guard](https://github.com/kalessil/production-dependencies-guard) ⭐ 86 | 🐛 5 | 🌐 PHP | 📅 2022-07-03 - Prevents development packages from being added into require and getting into production environment.
* [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin) ⭐ 80 | 🐛 2 | 🌐 PHP | 📅 2026-02-15 - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top.
* [CycloneDX-PHP-Composer](https://github.com/CycloneDX/cyclonedx-php-composer) ⭐ 80 | 🐛 19 | 🌐 PHP | 📅 2026-02-16 - Creates a [CycloneDX](https://cyclonedx.org/) "Software Bill-of-Materials" (SBOM) for the dependencies of a project. The SBOM enables dependency monitoring and risk analysis by [OWASP DependencyTrack](https://dependencytrack.org/).
* [Composer-AWS](https://github.com/naderman/composer-aws) ⚠️ Archived - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories).
* [Composer-Locator](https://github.com/mindplay-dk/composer-locator) ⚠️ Archived - Provides a means of locating the installation path for a given Composer package name.
* [Composer-Plugin-Exclude-Files](https://github.com/mcaskill/composer-plugin-exclude-files) ⭐ 40 | 🐛 0 | 🌐 PHP | 📅 2026-01-29 - A plugin for excluding files required by packages using the 'files' autoloading mechanism.
* [Composer-Vendor-Cleaner](https://github.com/liborm85/composer-vendor-cleaner) ⭐ 34 | 🐛 0 | 🌐 PHP | 📅 2025-11-21 - Plugin removes unnecessary development files and directories from `vendor` directory by glob pattern syntax.
* [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) ⭐ 29 | 🐛 1 | 🌐 PHP | 📅 2021-10-11 - Opinionated version of Wikimedia composer-merge-plugin to work in pair with Bamarni composer-bin-plugin.
* [Composer-Velocita](https://github.com/isaaceindhoven/composer-velocita) ⚠️ Archived - Fast and reliable Composer package downloads using [Velocita](https://github.com/isaaceindhoven/velocita-proxy) ⚠️ Archived: a caching reverse proxy that does not require you to modify your projects.
* [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) ⚠️ Archived - Comprehensive Plugin for composer to execute PHP Quality assurance Tools.
* [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin) ⭐ 21 | 🐛 1 | 🌐 PHP | 📅 2023-09-29 - Enables you to remove files and folders from the vendor folder (to make a cleaner and smaller deployment to production). It's an alternative to `.gitattributes`.
* [Composer-Symlinker](https://github.com/e-picas/composer-symlinker) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2015-04-19 - Enables you to load packages from different directories (instead of loading them from /vendor).
* [Drupal Vendor Hardening Composer Plugin](https://github.com/drupal/core-vendor-hardening) ⭐ 16 | 🐛 1 | 🌐 PHP | 📅 2026-02-05 - Removes extraneous directories from the project's vendor directory & adds .htaccess and web.config files to the root of the project's vendor directory.
* [Narrowspark-Automatic](https://github.com/narrowspark/automatic) ⚠️ Archived - Automates the most common tasks of applications, boost package downloads, adds a composer security audit and more.
* [Composer-Compile-Plugin](https://github.com/civicrm/composer-compile-plugin) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2025-11-02 - Allow PHP libraries to define simple, freeform compilation tasks. Support post-install hooks in any package.
* [Composer-Patchset](https://github.com/mageops/php-composer-plugin-patchset) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2025-05-30 - Automatically fetch, update and apply patches to any composer package with a twist - store the patchset as a composer package itself.
* [Composer-Downloads-Plugin](https://github.com/civicrm/composer-downloads-plugin) ⭐ 8 | 🐛 1 | 🌐 PHP | 📅 2024-04-09 - Lightweight mechanism to download external resources (ZIP/TAR files) with only a `url` and `path`.
* [PackageInfo](https://github.com/ThaDafinser/PackageInfo) ⭐ 7 | 🐛 2 | 🌐 PHP | 📅 2016-08-09 - Enables you to retrieve all package informations (like version, tag, release date, description).
* [Node-Composer](https://github.com/mariusbuescher/node-composer) ⭐ 6 | 🐛 6 | 🌐 PHP | 📅 2022-04-28 - Installer for Node.js, npm and yarn.
* [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2015-06-12 - The plugin uses `phpext_curl` for downloading packages.
* [PHP Inc](https://github.com/krakphp/php-inc) ⭐ 5 | 🐛 1 | 🌐 PHP | 📅 2021-08-23 - Automatically includes files for autoload and autoload-dev to facilitate using functions and grouped definitions within composer loaded applications.
* [Composer-Suggest](https://github.com/nfreear/composer-suggest) ⭐ 4 | 🐛 8 | 🌐 PHP | 📅 2018-07-31 - Enables you to install a custom group of suggested packages, based on keyword patterns.
* [Composer Translation Validator](https://github.com/move-elevator/composer-translation-validator) ⭐ 3 | 🐛 4 | 🌐 PHP | 📅 2026-02-14 - Validates translation files in your project, supports several file formats (regarding different frameworks) and provides useful validators for comparison, consistency and syntax checks.
* [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
* [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.

## Tools

* [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) ⭐ 5,351 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 - Enables you to navigate Composer/NPM dependencies on GitHub.
* [Composer/Xdebug-Handler](https://github.com/composer/xdebug-handler) ⭐ 2,557 | 🐛 0 | 🌐 PHP | 📅 2025-12-03 - Helps you to restart a CLI process without loading the xdebug extension.
* [Composer-Unused](https://github.com/composer-unused/composer-unused) ⭐ 1,654 | 🐛 11 | 🌐 PHP | 📅 2026-02-16 - A CLI tool, which scans your code and shows unused Composer dependencies.
* [Studio](https://github.com/franzliedke/studio) ⭐ 1,139 | 🐛 24 | 🌐 PHP | 📅 2024-04-21 - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project.
* [Composer-Normalize](https://github.com/ergebnis/composer-normalize) ⭐ 1,104 | 🐛 11 | 🌐 PHP | 📅 2026-02-16 - The plugin helps to keep your `composer.json` file(s) consistent by restructuring and sorting entries (normalizing).
* [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) ⭐ 985 | 🐛 42 | 🌐 PHP | 📅 2026-02-16 - A CLI tool to analyze dependencies and verify that no unknown imported symbols are used in the sources of a package.
* [Composer-Service](https://github.com/pborreli/composer-service) ⭐ 173 | 🐛 32 | 🌐 PHP | 📅 2021-07-27 - Enables you to run Composer as a service on a remote server.
* [Bramus/Composer-Autocomplete](https://github.com/bramus/composer-autocomplete) ⭐ 98 | 🐛 2 | 📅 2022-02-01 - A Bash/Shell autocompletion script for Composer.
* [Composer-Yaml](https://github.com/igorw/composer-yaml) ⭐ 54 | 🐛 4 | 🌐 PHP | 📅 2017-02-03 - This tool converts `composer.yml` to `composer.json`.
* [Composer PreferLowest Checker](https://github.com/dereuromark/composer-prefer-lowest) ⭐ 22 | 🐛 1 | 🌐 PHP | 📅 2025-11-22 - Strictly compare the specified minimum versions of your composer.json with the ones actually used by the prefer-lowest composer update command option.
* [Composer SemVer Checker](https://semver.madewithlove.com/) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
* [Composer Semver Range Checker](https://gitlab.com/MattyRad/composer.guru) - A tool to help check the satisfiable ranges of a composer constraint.

## Scripts

* [ParameterHandler](https://github.com/Incenteev/ParameterHandler) ⭐ 932 | 🐛 32 | 🌐 PHP | 📅 2025-11-26 - Allows you to manage your ignored parameters when running a composer install or update.
* [Melody](https://github.com/sensiolabs/melody) ⚠️ Archived - One-file composer scripts.
* [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer) ⭐ 151 | 🐛 1 | 🌐 PHP | 📅 2025-12-02 - A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.
* [Tooly](https://github.com/tommy-muehle/tooly-composer-script) ⭐ 103 | 🐛 8 | 🌐 PHP | 📅 2024-01-10 - Manage needed PHAR files in your project `composer.json`. Every PHAR file will be saved in the composer binary directory. Optional with GPG verification for every PHAR.
* [ScriptsDev](https://github.com/neronmoon/scriptsdev) ⭐ 69 | 🐛 1 | 🌐 PHP | 📅 2020-12-16 - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode.
* [Composer-Substitution-Plugin](https://github.com/villfa/composer-substitution-plugin) ⭐ 51 | 🐛 1 | 🌐 PHP | 📅 2024-01-31 - A Composer plugin replacing placeholders in the `scripts` section by dynamic values.
* [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) ⭐ 6 | 🐛 1 | 🌐 PHP | 📅 2018-01-29 - Allows you to lint the Travis CI configuration file (`.travis.yml`).
* [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2017-05-08 - Enables you to run a Composer script against multiple, locally installed PHP versions, which are managed by PHPBrew or phpenv.
* [Composer-Vendor-Cleanup](https://github.com/0xch/composer-vendor-cleanup) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2021-05-23 - A script which removes whitelisted unnecessary files (like tests/docs etc.) from the vendor directory.

## Services

* [Dependabot](https://github.com/security/advanced-security) - Dependabot is a dependency update service. It monitors and updates your dependencies by sending a pull-request. The service is free for public repos and personal account repos.

***

## Tutorials

* [A beginners guide to Composer](https://www.digitalocean.com/community/tutorials/a-beginners-guide-to-composer)
* [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
* [Easy package management with Composer](https://code.tutsplus.com/easy-package-management-with-composer--net-25530t)
* [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
* [Composer Primer](https://daylerees.com/composer-primer/)
* [PHP Composer Magento Tutorial by Alan Storm](https://alanastorm.com/php_composer_magento_tutorial/)
* [Creating and Using Composer Packages](https://www.packtpub.com/en-us/learning/how-to-tutorials/creating-and-using-composer-packages/)

## Blogs

* [Jordi Boggiano (seldaek)](https://seld.be/)
* [Nils Adermann (naderman)](https://naderman.de/)
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)
* [The long journey of making PHPs Composer memory-efficient and fast (toflar)](https://medium.com/@yanick.witschi/the-long-journey-of-making-phps-composer-memory-efficient-and-fast-63d12944aaa8)

## Videos

* [Composer Best Practices 2018 - Nils Adermann @ scotphp18](https://www.youtube.com/watch?v=eQkFjMfyqFY)
* [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
* [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
* [Composer Best Practices — Jordi Boggiano @ phptek 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
* [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
* [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
* [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
* [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)
* [Composer 2 - Jordi Boggiano @ Symfony UK usergroup 2020](https://www.youtube.com/watch?v=BAgwWhRo82w)
* [Lessons learned building the Composer internals - Jordi Boggiano @ CODEiD Odessa PHP Conference 2017](https://www.youtube.com/watch?v=pjvbn6TBZqM)

## Slides

* Slides by Nils Adermann
  * Source: <https://naderman.de/slippy/src/>
  * [PHP Reinvented - How Composer helped shape the new way of writing PHP](https://naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  * [Composer Update](https://naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  * [Dependency Management with Composer PHP Reinvented](https://naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  * [Managing dependencies is
    more than running
    "composer update"](https://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf)
  * [Composer
    Best Practices @ T3DD17](https://naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf)
  * [Gain Control over your
    Dependencies with
    Private Packagist](https://naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf)
  * [Composer.lock demystified](https://naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
  * [Compoer In-Depth @ Contao Konferenz 2018](https://naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
  * [Composer Best Practices 2018](https://naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
  * [Developing and Deploying Magento with Composer Best Practices](https://naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
  * [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](https://naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
* Slides by Jordi Boggiano
  * Source: <http://slides.seld.be/>
  * [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  * [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  * [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  * [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  * [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)
  * [Lessons Learned Building the Composer Internals (2018)](http://slides.seld.be/?file=2018-04-20+Lessons+Learned+Building+the+Composer+Internals.html)

***

## Packagist

[Packagist](https://packagist.org) is the PHP Package Repository.

### Setup a Packagist Mirror

* [Packagist Mirror](https://github.com/Webysther/packagist-mirror) ⚠️ Archived - This script helps to setup a packagist mirror. It is the maintained and stable version of [Packagist Crawler](https://github.com/hirak/packagist-crawler) ⭐ 57 | 🐛 0 | 🌐 PHP | 📅 2021-11-14.
* [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) ⭐ 31 | 🐛 2 | 🌐 PHP | 📅 2019-05-14 - Another implementation for creating a packagist mirror.
* [Docker Image](https://github.com/Webysther/packagist-mirror-docker) ⚠️ Archived - This Docker image helps to create a customized packagist mirror.

### Packagist Mirrors

About metadata mirrors: <https://packagist.org/mirrors>

* Global, CloudFlare - [packagist.pages.dev](https://packagist.pages.dev/)
* North America
  * Canada - [packagist.org](https://packagist.org) *Main mirror*
* Africa
  * South Africa - [packagist.co.za](https://packagist.co.za)
* Asia
  * China - <https://pkg.xyz/>, <https://developer.aliyun.com/composer>
  * India - <https://packagist.in/>
  * Japan - [packagist.jp](https://packagist.jp)
  * Korea - <https://packagist.kr/>

## Composer Repositories

### Registry Manager

* <https://github.com/slince/composer-registry-manager> ⭐ 559 | 🐛 4 | 🌐 PHP | 📅 2023-03-04 - The plugin helps you to switch between different composer repositories.

### Private repositories

* [fxpio/tug](https://github.com/fxpio/tug) ⭐ 43 | 🐛 0 | 🌐 TypeScript | 📅 2022-08-18 - Enables you to host a private Composer registry on AWS Serverless serving your private PHP packages, which are hosted on GitHub or GitLab services.

### Private Packagist

* [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories.
* [Private Packagist Enterprise](https://packagist.com) - On-premise self-hosted version of Private Packagist.
* [Private Packagist API Client](https://github.com/packagist/private-packagist-api-client) ⭐ 35 | 🐛 1 | 🌐 PHP | 📅 2026-02-02 - A PHP client for the Private Packagist API. The client handles authentication, signature generation and access to all endpoints.

### Repman

* [repman.io](https://repman.io) & [repman-io/repman](https://github.com/repman-io/repman) ⭐ 568 | 🐛 123 | 🌐 PHP | 📅 2026-02-06 - A Private PHP Package Repository Manager & Packagist Proxy.
* [repman-io/composer-plugin](https://github.com/repman-io/composer-plugin) ⭐ 11 | 🐛 2 | 🌐 PHP | 📅 2024-02-27 - This plugin enables downloading via Repman by adding a distribution mirror URL for all your dependencies (without need to update the `composer.lock` file).

## Packagist-compatible repositories

* [Packeton](https://github.com/vtsykun/packeton) ⭐ 504 | 🐛 33 | 🌐 PHP | 📅 2026-02-15 - Private self-hosted Composer repository for vendors. Fork of packagist with adding support for authorization, customer users, groups, webhooks.
* [Release Belt](https://github.com/Rarst/release-belt) ⭐ 176 | 🐛 1 | 🌐 PHP | 📅 2022-07-20 - Self–hosted Composer repository implementation to quickly integrate ZIP files of third party non–Composer releases.
* [Satis Server](https://github.com/lukaszlach/satis-server) ⭐ 116 | 🐛 4 | 🌐 Shell | 📅 2021-09-22 - This docker container provides a Satis Server and enables you to run a private, self-hosted Composer repository with support for Git, Mercurial, and Subversion, HTTP API, HTTPs support, webhook handler and scheduled builds.
* [WordPress Packagist](https://wpackagist.org/) - Mirrors the WordPress plugin and theme directories as a Composer repository.
* [Asset Packagist](https://asset-packagist.org/) - Enables installation of Bower and NPM packages as native Composer packages.
* [Firegento](https://packages.firegento.com/) - A Composer Repository providing Magento Modules.
* [Drupal Packagist](https://www.drupal.org/node/2822344) - Composer repositories for Drupal 7 and 8 core, modules, and themes.
* [Cloudsmith](https://cloudsmith.com/) - A fully managed package management SaaS with PHP/Composer support (and many others).
* [RepoFlow](https://www.repoflow.io) - Simple and fast platform for hosting private Composer registries. Also supports Docker, npm, PyPI, Maven, and RubyGems. Offers free options for both cloud and self-hosted setups.

### Satis

* [Satisfy](https://github.com/project-satisfy/satisfy) ⭐ 543 | 🐛 8 | 🌐 PHP | 📅 2025-05-28 - Satis composer repository manager with a Web UI.
* [GitLab-Composer](https://github.com/wemakecustom/gitlab-composer) ⭐ 163 | 🐛 6 | 🌐 PHP | 📅 2018-08-06 - This is a branch/tag indexer for GitLab repositories.
* [Satis Control Panel](https://github.com/realshadow/satis-control-panel) ⭐ 152 | 🐛 8 | 🌐 PHP | 📅 2019-01-10 - A simple web UI for managing your Satis Repository with optional CI integration.
* [Satis Go](https://github.com/benschw/satis-go) ⭐ 96 | 🐛 5 | 🌐 Go | 📅 2020-06-12 - A web server for managing Satis configuration and hosting the generated Composer repository.

### Toran Proxy

* [ToranProxy](https://toranproxy.com/) (deprecated) - In addition to providing a composer repository ToranProxy acts as a proxy server for Packagist and GitHub.

***

## Copyright

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.
