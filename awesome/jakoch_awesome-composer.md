# Information comes from [jakoch/awesome-composer](https://github.com/jakoch/awesome-composer)
## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php](https://github.com/ziadoz/awesome-php).

*Please read the [contribution guidelines](contributing.md) before contributing.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues) :star:16725
- [Github](https://github.com/composer/composer) :star:16725
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.
- [Composer Installers](https://github.com/composer/installers) - Composer installers for multiple frameworks. :star:994

### Support

#### Stack Overflow

- You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC channels are on `irc.freenode.org`: [#composer](https://webchat.freenode.net/?channels=composer) for users and [#composer-dev](https://webchat.freenode.net/?channels=composer-dev) for development.

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) - A npm/Bower Dependencies Manager for Composer. :star:841
- [Composer-AWS](https://github.com/naderman/composer-aws) - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories). :star:62
- [Composer-Composition](https://github.com/bamarni/composition) - Provides an API, for checking your environment at runtime. :star:106
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) - Enables you to install a custom group of suggested packages, based on keyword patterns. :star:4
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z"). :star:172
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs) - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file. :star:421
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) - Merges multiple `composer.json` files at Composer runtime. :star:473
- [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) - Adds support for managing dependencies for multiple packages in a single repository or isolate bin dependencies. :star:138
- [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) - Opinionated version of Wikimedia composer-merge-plugin to work in pair with Bamarni composer-bin-plugin. :star:9
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) - The plugin adds support for managing dependencies for multiple packages in a single repository. :star:210
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin) - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top. :star:61
- [Composer-Patches](https://github.com/cweagans/composer-patches) - The plugin applies a patch from a local or remote file to any required package. :star:534
- [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) - Comprehensive Plugin for composer to execute PHP Quality assurance Tools. :star:22
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) - Removes tests & documentation folders from the vendor dir. :star:74
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) - The tool removes unnecessary files and directories from the vendor directory. :star:81
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) - Allows you to share your selected packages between your projects by creating symlinks. :star:158
- [Composer-Symlinker](https://github.com/dg/composer-symlinker) - Enables you to load some packages from different directories (instead of loading them from /vendor). :star:20
- [Prestissimo](https://github.com/hirak/prestissimo) - A parallel downloader using `phpext_curl`. :star:4097
- [Composer-FastFetch](https://github.com/jakoch/composer-fastfetch) - Parallel Downloader using external download tools: Aria2. :star:12
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) - The plugin use phpext_curl for downloading packages. :star:3
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (which is in the vendor folder). :star:95
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.
- [PackageVersions](https://github.com/Ocramius/PackageVersions) - Provides a very quick and easy access to installed composer dependency versions. :star:1315
- [Composer Locator](https://github.com/mindplay-dk/composer-locator) - Provides a means of locating the installation path for a given Composer package name. :star:55
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) - Check if a package is installed and retrieve all package informations like version, tag release date, description, ... :star:5
- [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin) - The composer plugin to remove useless files in vendor by yourself. :star:5
- [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) - A library for easily managing git hooks in your composer config. :star:206
- [Symfony-Flex](https://github.com/symfony/flex) - Provides [recipe-based](https://github.com/symfony/recipes) installation and configuration management for Symfony packages. :star:1747
- [Narrowspark-Automatic](https://github.com/narrowspark/automatic) - Automates the most common tasks of applications, boost package downloads, adds a composer security audit and more. :star:4
- [PHPCodeSniffer-Composer-Installer](https://github.com/DealerDirect/phpcodesniffer-composer-installer) - Automates the configuration of custom PHP_CodeSniffer standards/sniffs via Composer :star:81
- [Composer-Warmup](https://github.com/jderusse/composer-warmup) - The plugin adds the command `warmup-opcode` to Composer, which triggers the compilation of all PHP files discovered in your project into the Opcache. :star:142
- [Foxy](https://github.com/fxpio/foxy) - Composer plugin that executes npm/yarn packages installation operations when composer package is installed or updated. :star:55
- [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) - downloads and installs NodeJS and npm as composer package  :star:92
- [Imposter-Plugin](https://github.com/typisttech/imposter-plugin) - Wrapping all composer vendor packages inside your own namespace. Intended for WordPress plugins. :star:10

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) - This tool converts composer.yml to composer.json. :star:49
- [Studio](https://github.com/franzliedke/studio) - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project. :star:715
- [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) - Enables you to navigate Composer/NPM dependencies on Github. :star:2978
- [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) - A CLI tool to analyze dependencies and verify that no unknown imported symbols are used in the sources of a package. :star:222

## Scripts

- [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) - Allows you to lint the Travis CI configuration file (`.travis.yml`). :star:4
- [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) - Enables you to run a Composer script against multiple, locally installed PHP versions, which are managed by PHPBrew or phpenv. :star:5
- [ScriptsDev](https://github.com/neronmoon/scriptsdev) - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode. :star:49
- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) - Allows you to manage your ignored parameters when running a composer install or update. :star:686
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer)- A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script) - Manage needed PHAR files in your project composer.json. Every PHAR file will be saved in the composer binary directory. Optional with GPG verification for every PHAR. :star:79

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) - Mirrors the WordPress plugin and theme directories as a Composer repository.
- [Asset Packagist](https://asset-packagist.org/) - Enables installation of Bower and NPM packages as native Composer packages.
- [Firegento](http://packages.firegento.com/) - A Composer Repository providing Magento Modules.
- [Drupal Packagist](https://www.drupal.org/node/2822344) - Composer repositories for Drupal 7 and 8 core, modules, and themes.
- [Satis Server](https://github.com/lukaszlach/satis-server) - This docker container provides a Satis Server and enables you to run a private, self-hosted Composer repository with support for Git, Mercurial, and Subversion, HTTP API, HTTPs support, webhook handler and scheduled builds. :star:33

## GUI 

- [Composercat](https://www.getcomposercat.com/) - Composercat is a comprehensive GUI for the Composer package manager, designed both for professionals and people taking their first steps with Composer.

## Tutorials

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](https://alanstorm.com/php_composer_magento_tutorial/ )

## Books

- [Creating and Using Composer Packages](https://hub.packtpub.com/creating-and-using-composer-packages/)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](http://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
- [Composer Best Practices — Jordi Boggiano @ php[tek] 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
- [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Slides

- Slides by Nils Aderman
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](http://www.naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  - [Composer Update](http://www.naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](http://www.naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  - [Managing dependencies is
more than running
"composer update"](http://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf)
  - [Composer
Best Practices](http://www.naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf)
  - [Gain Control over your
Dependencies with
Private Packagist](http://www.naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf)
- Slides by Jordi Boggiano
  - [Dependency Management with Composer](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  - [In Depth with Composer](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Composer Best Practices](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)

## Packagist

- [Packagist Mirror from Brazil](https://github.com/Webysther/packagist-mirror) - This is a maintained stable version of [packagist crawler](https://github.com/hirak/packagist-crawler). :star:27
- [Docker Image](https://github.com/Webysther/packagist-mirror-docker) - This Docker image helps to create a customized packagist mirror. :star:4
- [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) - Another implementation for creating a packagist mirror. :star:22

### Packagist Mirrors

About metadata mirrors: https://packagist.org/mirrors

- North America
  - Canada - [packagist.org](https://packagist.org) *Main mirror*
- South America
  - Brazil - [packagist.com.br](https://packagist.com.br)
- Asia
  - China - [php.cnpkg.org](https://php.cnpkg.org)
  - Indonesia - [packagist.phpindonesia.id](https://packagist.phpindonesia.id)
  - Japan - [packagist.jp](https://packagist.jp)

## Composer Repositories

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories
- [Private Packagist Enterprise](https://packagist.com) - On-premise self-hosted version of Private Packagist

### Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - This is a branch/tag indexer for Gitlab repositories. :star:143
- [Satisfy](https://github.com/ludofleury/satisfy) - Satis composer repository manager with a Web UI. :star:254
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - A simple web UI for managing your Satis Repository with optional CI integration. :star:101
- [Satis Go](https://github.com/benschw/satis-go) - A web server for managing Satis configuration and hosting the generated Composer repository. :star:68

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) (deprecated) - In addition to providing a composer repository ToranProxy acts as a proxy server for Packagist and GitHub.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.

