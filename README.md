# Awesome PHP

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing and Collaborating
Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) for details.

## Table of Contents
- [Awesome PHP](#awesome-php)
    - [Architectural](#architectural)
    - [Asset Management](#asset-management)
    - [API](#api)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Build Tools](#build-tools)
    - [Caching and Locking](#caching-and-locking)
    - [Code Analysis](#code-analysis)
    - [Code Quality](#code-quality)
    - [Command Line](#command-line)
    - [Components](#components)
    - [Configuration](#configuration)
    - [Content Management Systems](#content-management-systems-cms)
    - [Continuous Integration](#continuous-integration)
    - [Database](#database)
    - [Data Structure and Storage](#data-structure-and-storage)
    - [Date and Time](#date-and-time)
    - [Dependency Injection](#dependency-injection)
    - [Documentation](#documentation)
    - [E-commerce](#e-commerce)
    - [Email](#email)
    - [Event](#event)
    - [Files](#Files)
    - [Filtering and Validation](#filtering-and-validation)
    - [Frameworks](#frameworks)
    - [Framework Extras](#framework-extras)
    - [Geolocation](#geolocation)
    - [HTTP](#http)
    - [Imagery](#imagery)
    - [Internationalisation and Localisation](#internationalisation-and-localisation)
    - [JSON](#json)
    - [Logging](#logging)
    - [Markup and CSS](#markup-and-css)
    - [Micro Frameworks](#micro-frameworks)
    - [Micro Framework Extras](#micro-framework-extras)
    - [Middlewares](#middlewares)
    - [Migrations](#migrations)
    - [Miscellaneous](#miscellaneous)
    - [Navigation](#navigation)
    - [NoSQL](#nosql)
    - [Notifications](#notifications)
    - [Numbers](#numbers)
    - [Office](#office)
    - [PDF](#pdf)
    - [Queue](#queue)
    - [Routers](#routers)
    - [Scraping](#scraping)
    - [Search](#search)
    - [Security](#security)
    - [Security: Hashing](#security-hashing)
    - [Serverless](#serverless)
    - [Static Analysis](#static-analysis)
    - [Static Site Generators](#static-site-generators)
    - [Strings](#strings)
    - [Streams](#streams)
    - [Task Runners](#task-runners)
    - [Templating](#templating)
    - [Testing](#testing)
    - [Third Party APIs](#third-party-apis)
    - [URL](#url)   

### ACL (Access Control List) & RBAC (Role-based Access Control)

* [Geggleto ACL](https://github.com/geggleto/geggleto-acl) - PSR-7 Zend ACL implementation - Permission Library [ slim, psr7, acl, permissions, zend ]
* [Laminas ACL](https://docs.laminas.dev/laminas-permissions-acl/) - Create, manage, and query access control lists
* [Laminas RBAC](https://docs.laminas.dev/laminas-permissions-rbac/) - laminas-permissions-rbac provides a lightweight Role-Based Access Control (RBAC) implementation
* [Slim ACL](https://github.com/slimphp-api/slim-acl) - ACL middleware for slim, using Zend\Permissions\Acl
* [Slim Skeleton with ACL, JWT and MySQL](https://github.com/thiago231286/skeleton-api-slim-jwt-acl-mysql) - Slim Skeleton with ACL, JWT and MySQL
* [Slim Middleware Basic ACL](https://github.com/conrad10781/slim-middleware-basic-acl) - Very easy ACL implementation for Slim Framework 3 when using HTTP Authentication

### Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP ) - A repository of software patterns implemented in PHP.
* [Finite](https://yohan.giarel.li/Finite/) - A simple PHP finite state machine.
* [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
* [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
* [Patchwork](https://patchwork2.org/) - A library for redefining userland functions.
* [Pipeline](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
* [Porter](https://github.com/ScriptFUSION/Porter) - Data import abstraction library for consuming Web APIs and other data sources.
* [RulerZ](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern

### Asset Management
*Tools for managing, compressing and minifying website assets.*

* [JShrink](https://github.com/tedious/JShrink) - A JavaScript minifier library.
* [Laravel Mix](https://github.com/laravel-mix/laravel-mix ) - An elegant wrapper around Webpack for the 80% use case.
* [Symfony Asset](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets.
* [Symfony Encore](https://github.com/symfony/webpack-encore) - A simple but powerful API for processing and compiling assets built around Webpack

### API
*Libraries and web tools for developing APIs.*

* [API Platform](https://api-platform.com ) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
* [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) - An API builder built with the Laminas Framework.
* [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
* [Jane](https://github.com/janephp/janephp/) - An OpenApi client generator with validation support.
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
* [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
* [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

### Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* [Aura.Auth](https://github.com/auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters.
* [SocialConnect Auth](https://github.com/socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
* [Json Web Token](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.
* [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](https://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [Opauth](https://github.com/opauth/opauth) - A multi-provider authentication framework.
* [Paseto](https://github.com/paragonie/paseto) - Platform-Agnostic Security Tokens.
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
* [TwitterOAuth](https://github.com/abraham/twitteroauth) - A Twitter OAuth library

### Build Tools
*Project build and automation tools.*

* [Box](https://github.com/box-project/box) - A utility to build PHAR files
* [Construct](https://github.com/jonathantorres/construct) - A PHP project/micro-package generator
* [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant
* [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software

### Caching and Locking
*Libraries for caching data and acquiring locks.*

* [APIx Cache](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing.
* [CacheTool](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
* [CakePHP Cache](https://github.com/cakephp/cache) - A caching library.
* [Doctrine Cache](https://github.com/doctrine/cache) - A caching library.
* [Metaphore](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect.
* [Stash](https://github.com/tedious/Stash) - Another library for caching.
* [Laminas Cache](https://github.com/laminas/laminas-cache) - Another caching library.
* [Lock](https://github.com/php-lock/lock) - A lock library to provide exclusive execution

### Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* [Better Reflection](https://github.com/Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code
* [Code Climate](https://codeclimate.com) - An automated code review.
* [GrumPHP](https://github.com/phpro/grumphp) - A PHP code-quality tool.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* [Phpactor](https://github.com/phpactor/phpactor) - PHP completion, refactoring and introspection tool.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - A tool to visualize metrics and source code.
* [Rector](https://github.com/rectorphp/rector) - A tool to upgrade and refactor code.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer).
* [UBench](https://github.com/devster/ubench) - A simple micro benchmark library.

### Code Quality
*Libraries for managing code quality, formatting and linting.*

* [CaptainHook](https://github.com/captainhookphp/captainhook) - An easy-to-use and flexible Git hook library. 
* [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
* [PHP Mess Detector](https://github.com/phpmd/phpmd) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code

### Command Line
*Libraries related to the command line.*

* [Aura.Cli](https://github.com/auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
* [Boris](https://github.com/borisrepl/boris) - A tiny PHP REPL.
* [Cilex](https://github.com/Cilex/Cilex) - A micro framework for building command line tools.
* [CLI Menu](https://github.com/php-school/cli-menu) - A library for building CLI menus.
* [CLIFramework](https://github.com/c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* [CLImate](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting.
* [Commando](https://github.com/nategood/commando) - Another simple command line opt parser.
* [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
* [GetOpt](https://github.com/getopt-php/getopt-php) - A command line opt parser.
* [GetOptionKit](https://github.com/c9s/GetOptionKit) - Another command line opt parser.
* [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL.
* [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library

### Components
*Standalone components from web development frameworks and development groups.*

* [Aura](https://auraphp.com/) - Independent components, fully decoupled from each other and from any framework
* [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins
* [Hoa Project](https://github.com/hoaproject) - (ARCHIVED) Archived, but still some really cool components here
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group
* [Laminas Components](https://docs.laminas.dev/components/) - The components that make the Laminas Framework
* [Laravel Components](https://github.com/illuminate) - The Laravel Framework components
* [Nette Components](https://github.com/nette/) - The Nette Foundation components
* [Spatie Open Source](https://spatie.be/open-source) - A collection of open source PHP and Laravel packages
* [Symfony Components](https://symfony.com/components) - The components that make Symfony

## Configuration
*Libraries and tools for configuration.*

* [PHP Dotenv](https://github.com/vlucas/phpdotenv) - Parse and load environment variables from `.env` files.
* [Symfony Dotenv](https://github.com/symfony/dotenv)- Parse and load environment variables from `.env` files.
* [Yo! Symfony TOML](https://github.com/yosymfony/toml) - A PHP parser for [TOML](https://github.com/toml-lang/toml)

### Content Management Systems (CMS)
*Tools for managing digital content.*

* [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium sized business and non-profits (a fork of Drupal).
* [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
* [CraftCMS](https://github.com/craftcms/cms) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
* [Drupal](https://www.drupal.org) - An enterprise level CMS.
* [Grav](https://github.com/getgrav/grav) - A modern flat-file CMS.
* [Joomla](https://www.joomla.org/) - Another leading CMS.
* [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
* [Magento](https://business.adobe.com/products/magento/magento-commerce.html) - The most popular ecommerce platform.
* [Moodle](https://moodle.org/) - An open-source learning platform.
* [Pico CMS](https://picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
* [Statamic](https://statamic.com/) - Build beautiful, easy to manage websites.
* [WordPress](https://wordpress.org/) - A blogging platform and CMS

### Continuous Integration
*Libraries and applications for continuous integration.*

* [CircleCI](https://circleci.com) - A continuous integration platform.
* [GitlabCi](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* [Jenkins](https://www.jenkins.io/) - A continuous integration platform with [PHP support](https://www.jenkins.io/solutions/php/).
* [JoliCi](https://github.com/jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker.
* [PHPCI](https://github.com/dancryer/phpci) - An open source continuous integration platform for PHP.
* [SemaphoreCI](https://semaphoreci.com/) - A continuous integration platform for open source and private projects.
* [Shippable](https://jfrog.com/blog/weve-acquired-shippable-to-complete-devops-pipeline-automation-from-code-to-production/) - A Docker based continious integration platform for open source and private projects.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform.
* [Setup PHP](https://github.com/shivammathur/setup-php) - A GitHub Action for PHP

### Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) - A data mapper implementation for your persistence model in PHP.
* [Aura.Sql](https://github.com/auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator.
* [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
* [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
* [CakePHP ORM](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern.
* [Cycle ORM](https://github.com/cycle/orm) - PHP DataMapper, ORM.
* [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions ) - A collection of Doctrine behavioural extensions.
* [Doctrine](https://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Laravel Eloquent](https://github.com/illuminate/database) - A simple ORM.
* [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
* [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
* [Slimdump](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL.
* [Spot2](https://github.com/spotorm/spot2) - A MySQL datamapper ORM


### Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [CakePHP Collection](https://github.com/cakephp/collection) - A simple collections library.
* [Fractal](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output.
* [Ginq](https://github.com/akanehara/ginq) - Another PHP library based on .NET's LINQ.
* [JsonMapper](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
* [JSON Machine](https://github.com/halaxa/json-machine) - Provides iteration over huge JSONs using simple `foreach`
* [Knapsack](https://github.com/DusanKasan/Knapsack) - Collection library inspired by Clojure's sequences.
* [msgpack.php](https://github.com/rybakit/msgpack.php) - A pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format.
* [PINQ](https://github.com/TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query).
* [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
* [YaLinqo](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
* [Laminas Serializer](https://github.com/laminas/laminas-serializer) - Another library for serialising and de-serialising data

### Date and Time
*Libraries for working with dates and times.*

* [CalendR](https://yohan.giarel.li/CalendR/) - A calendar management library.
* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
* [Chronos](https://github.com/cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time.
* [Moment.php](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.
* [Yasumi](https://github.com/azuyalabs/yasumi) - An library to help you calculate the dates and names of holidays

### Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* [Aura.Di](https://github.com/auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
* [Acclimate](https://github.com/AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators.
* [Auryn](https://github.com/rdlowrey/Auryn) - A recursive dependency injector.
* [Container](https://github.com/thephpleague/container) - Another flexible dependency injection container.
* [Disco](https://github.com/bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container.
* [PHP-DI](https://php-di.org/) - A dependency injection container that supports autowiring.
* [Pimple](https://pimple.symfony.com/) - A tiny dependency injection container.
* [Symfony DI](https://github.com/symfony/dependency-injection) - A dependency injection container component

### Documentation
*Libraries for generating project documentation.*

* [APIGen](https://github.com/apigen/apigen) - Another API documentation generator.
* [daux.io](https://github.com/dauxio/daux.io) - A documentation generator which uses Markdown files.
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor) - A documentation generator.
* [phpDox](https://phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation)

### E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [Money](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
* [Brick\Money](https://github.com/brick/money) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
* [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
* [Payum](https://github.com/payum/payum) - A payment abstraction library.
* [Shopware](https://github.com/shopware/shopware) - Highly customizable e-commerce software
* [Swap](https://github.com/florianv/swap) - An exchange rates library.
* [Sylius](https://sylius.com/) - An open source e-commerce solution

### Email
*Libraries for sending and parsing email.*

* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
* [Email Validator](https://github.com/nojacko/email-validator) - A small email address validation library.
* [Fetch](https://github.com/tedious/Fetch) - An IMAP library.
* [Mautic](https://github.com/mautic/mautic) - Email marketing automation
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
* [PHP IMAP](https://github.com/barbushin/php-imap) - A library to access mailboxes via POP3, IMAP and NNTP.
* [Stampie](https://github.com/Stampie/Stampie) - A library for email services such as [SendGrid](https://sendgrid.com/), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).
* [SwiftMailer](https://swiftmailer.symfony.com) - A mailer solution.
* [Symfony Mailer](https://github.com/symfony/mailer) - A powerful library for creating and sending emails

### Event
*Libraries that are event-driven or implement non-blocking event loops.*
* [Amp](https://github.com/amphp/amp) - An event driven non-blocking I/O library.
* [Broadway](https://github.com/broadway/broadway) - An event source and CQRS library.
* [CakePHP Event](https://github.com/cakephp/event) - An event dispatcher library.
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - Yet another web socket library.
* [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
* [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events.
* [Pawl](https://github.com/ratchetphp/Pawl) - An asynchronous web socket client.
* [Prooph Event Store](https://github.com/prooph/event-store) - An event source component to persist event messages
* [PHP Defer](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP
* [Phly Event](https://github.com/phly/phly-event-dispatcher) - Event Dispatcher
* [Ratchet](https://github.com/ratchetphp/Ratchet) - A web socket library.
* [ReactPHP](https://github.com/reactphp/reactphp) - An event driven non-blocking I/O library.
* [RxPHP](https://github.com/ReactiveX/RxPHP) - A reactive extension library.
* [Swoole](https://github.com/swoole/swoole-src) - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
* [Workerman](https://github.com/walkor/Workerman) - An event driven non-blocking I/O library

### Files
*Libraries for file manipulation and MIME type detection.*

* [CSV](https://github.com/thephpleague/csv) - A CSV data manipulation library.
* [Flysystem](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems.
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.
* [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.

### Frameworks
*Web development frameworks.*

* [CakePHP](https://cakephp.org/) - A rapid application development framework
* [Ice Frameowkr](https://www.iceframework.org/) - PHP Framework as a C-Extension
* [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
* [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
* [Nette](https://nette.org) - A web framework comprised of mature components.
* [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
* [Spiral](https://spiral.dev/) - A high performance PHP/Go framework.
* [Symfony](https://symfony.com/) - A set of reuseable components and a web framework.
* [Yii2](https://github.com/yiisoft/yii2/) - A fast, secure, and efficient web framework.

### Framework Extras
*Extras related to web development frameworks.*

* [CakePHP CRUD](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
* [Knp RAD Components](https://rad.knplabs.com/) - A set of Rapid Application Development (RAD) components for Symfony.
* [LaravelS](https://github.com/hhxsv5/laravel-s) - Glue for using Swoole in Laravel or Lumen.
* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.
* [Livewire](https://laravel-livewire.com/) - A full-stack framework for Laravel that takes the pain out of building dynamic UIs

### Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* [GeoCoder](https://geocoder-php.org/) - A geocoding library.
* [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.
* [GeoTools](https://github.com/thephpleague/geotools) - A library of geo-related tools.
* [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library

### HTTP
*Libraries for working with HTTP.*

* [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
* [Nyholm PSR-7](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation. Very strict and very fast.
* [PHP VCR](https://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
* [Requests](https://github.com/WordPress/Requests) - A simple HTTP library.
* [Retrofit](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients.
* [Symfony HTTP Client](https://github.com/symfony/http-client) - A component to fetch HTTP resources synchronously or asynchronously.
* [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP Message implementation

### Imagery
*Libraries for manipulating images.*

* [Color Extractor](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
* [Glide](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
* [Image Hash](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
* [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
* [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library

### Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura.Intl](https://github.com/auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
* [CakePHP I18n](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers.

### JSON
*Libraries for working with JSON.*

* [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
* [JSONMapper](https://github.com/JsonMapper/JsonMapper) - A library for mapping JSON to PHP objects

### Logging
*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger

### Markup and CSS
*Libraries for working with markup and CSS formats.

* [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
* [Decoda](https://github.com/milesj/decoda) - A lightweight markup parser library.
* [Essence](https://github.com/essence/essence) - A library for extracting web media.
* [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
* [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
* [PHP CSS Parser](https://github.com/sabberworm/PHP-CSS-Parser) - A Parser for CSS Files written in PHP.
* [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.
* [Shiki PHP](https://github.com/spatie/shiki-php) - A [Shiki](https://github.com/shikijs/shiki) code highlighting package in PHP.
* [VObject](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects

### Micro Frameworks
*Micro frameworks and routers.*

* [BulletPHP]()
* [Laravel-Zero](https://laravel-zero.com) - A micro-framework for console applications.
* [Lumen](https://lumen.laravel.com/) - A micro-framework by Laravel.
* [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas
* [Proton](https://github.com/kraugar/Proton) - Microframework built on Orno/Route, Orni/DI and League/Event
* [Radar](https://github.com/radarphp/Radar.Adr) - An Action-Domain-Responder implementation for PHP.
* [Silly](https://github.com/mnapoli/silly) - A micro-framework for CLI applications.
* [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras
*Extras related to micro frameworks and routers.*

* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
* [Slim Twig View](https://github.com/slimphp/Slim-Views) - Integrate Twig into Slim.
* [Slim PHP View](https://github.com/slimphp/PHP-View) - A simple PHP renderer for Slim

### Middlewares
*Collections of middleware to be passed to a middleware dispatcher*

* [Awesome PSR-15 Middlwares](https://github.com/middlewares/awesome-psr15-middlewares) - Collection of PSR15 Middlewares
* [Branca Token Middleware](https://github.com/tuupola/branca-middleware) - PSR-7 and PSR-15 Branca token authentication middleware
* [PSR-7 Middlewares](https://github.com/oscarotero/psr7-middlewares) - (DEPRECATED) Inspiring collection of handy PSR-7 middlewares
* [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares) - Inspiring collection of handy PSR-15 middlewares
* [CSRF Middleware](https://github.com/zakirullin/csrf-middleware) - A PSR-15 middleware to automate CSRF-token verification process

### Middleware Dispatchers
*Libraries for building application using middlewares.*

* [Middleland](https://github.com/oscarotero/middleland) - Simple PSR-15 middleware dispatcher
* [Relay](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony
* [Mezzio](https://github.com/mezzio/mezzio) - A framework for building PSR-15 middleware applications
* [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) - Middleware for PHP built on top of PSR-7

### Migrations
Libraries to help manage database schemas and migrations.

* [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.
* [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library.
* [Phinx](https://github.com/cakephp/phinx) - Another database migration library.
* [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library.
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite

### Miscellaneous
*Useful libraries or utilities that don't fit into the categories above.*

* [Annotations](https://github.com/doctrine/annotations) - An annotation library (part of Doctrine).
* [BotMan](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chat bots.
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - A library for optimising autoloading.
* [Hprose-PHP](https://github.com/hprose/hprose-php) - A cross-language RPC.
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
* [Safe](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false.
* [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized

### Navigation
*Tools for building navigation structures.*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.
* [Menu](https://github.com/spatie/menu) - A flexible menu library with a fluent interface

### NoSQL
*Libraries for working with "NoSQL" backends.*

* [PHPMongo](https://github.com/sokil/php-mongo) - A MongoDB ORM.
* [Predis](https://github.com/predis/predis) - A feature complete Redis library


### Notifications
*Libraries for working with notification software.*

* [JoliNotif](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
* [Notificato](https://github.com/mac-cain13/notificato) - A library for handling push notifications.
* [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.
* [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

### Numbers
*Libraries for working with numbers.*

* [Brick\Math](https://github.com/brick/math) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
* [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
* [DecimalObject](https://github.com/spryker/decimal-object) - A value object to handle decimals/floats easily and more precisely.
* [IP](https://github.com/darsyn/ip) - An immutable value object for working with IPv4 and IPv6 addresses.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
* [MathPHP](https://github.com/markrogoyski/math-php) - A math library for PHP

### Office
*Libraries for working with office suite documents.*

* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
* [PHPWord](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
* [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
* [Spout](https://github.com/box/spout) - Read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way .

### PDF
*Libraries and software for working with PDF files.*

* [Dompdf](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
* [PHPPdf](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML.
* [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
* [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF

### Queue
*Libraries for working with event and task queues.*

* [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.
* [BunnyPHP](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
* [Pheanstalk](https://github.com/pheanstalk/pheanstalk) - A Beanstalkd client library.
* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
* [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
* [Thumper](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.
* [Enqueue](https://github.com/php-enqueue/enqueue-dev) - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports

### Routers
*Libraries for handling application routing.*

* [Aura.Router](https://github.com/auraphp/Aura.Router) - A full-featured routing library.
* [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
* [Klein](https://github.com/klein/klein.php) - A flexible router.
* [Pux](https://github.com/c9s/Pux) - Another fast routing library.
* [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route


### Scraping
*Libraries for scraping websites.*

* [Chrome PHP](https://github.com/chrome-php/chrome) - Instrument headless Chrome/Chromium instances from PHP. 
* [DiDOM](https://github.com/Imangazaliev/DiDOM) - A super fast HTML scrapper and parser.
* [Embed](https://github.com/oscarotero/Embed) - An information extractor from any web service or page.
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - A simple web scraper.
* [Symfony Panther](https://github.com/symfony/panther) - A browser testing and web crawling library for PHP and Symfony.
* [PHP Spider](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider

### Search
*Libraries and software for indexing and performing search queries on data.*

* [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
* [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
* [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines

### Security
*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

* [Anti CSRF](https://github.com/paragonie/anti-csrf) - Standalone anti-CSRF attack library
* [Awesome AppSec](https://github.com/paragonie/awesome-appsec) - Curated list of awesome AppSec learning resources
* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium).
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
* [IniScan](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security
* [Multifactor Auth](https://github.com/paragonie/multi_factor) - A library by Paragonie to create and handle Multifactor Authentication
* [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
* [Paragonie Repos](https://github.com/orgs/paragonie/repositories) - A collection of security-focused PHP libs by Paragonie
* [PHPGGC](https://github.com/ambionics/phpggc) - A library of PHP unserializeable payloads along with a tool to generate them.
* [PHP Encryption](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
* [PHP SSH](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
* [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
* [RandomLib](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings
* [Slim 4 CSRF PSR-15 Middleware](https://github.com/slimphp/Slim-Csrf) - Slim Framework CSRF protection middleware
* [Symfony Security Monitoring](https://security.symfony.com/) - A web tool to check your Composer dependencies for security advisories, previously known as "SensioLabs Security Check".
* [SQLMap](https://github.com/sqlmapproject/sqlmap) - An automatic SQL injection and database takeover tool. 
* [TCrypto](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library.
* [VAddy](https://vaddy.net/) - A continuous security testing platform for web applications.
* [Zap](https://owasp.org/www-project-zap/) - An integrated penetration testing tool for web applications

### Security: Hashing
*Libraries and tools for working with and storing passwords.*

* [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
* [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
* [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
* [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
* [Password-Generator](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* [phpass](https://www.openwall.com/phpass/) - A portable password hashing framework.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS

### Serverless
*Libraries and tools to help build serverless web applications.*

* [Bref](https://bref.sh/) - Serverless PHP on AWS Lambda.
* [OpenWhisk](https://openwhisk.apache.org/) - An open-source serverless cloud platform.
* [Serverless Framework](https://www.serverless.com/framework) - An open-source framework for building serverless applications.
* [Laravel Vapor](https://vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS

### Sessions and Cookies
*Libraries for handling Sessions and Cookies*

* [Storageless Sessions](https://github.com/psr7-sessions/storageless) - Storage-less PSR-7 session support
* [Aura.Session](https://github.com/auraphp/Aura.Session) - Tools for managing sessions, including session segments and read-once messages

### Static Analysis
*Libraries for performing static analysis of PHP code.*

* [Exakat](https://github.com/exakat/exakat) - A static analysis engine for PHP.
* [Deptrac](https://github.com/qossmic/deptrac) - A static code analysis tool that helps to enforce rules for dependencies between software layers.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [phan](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
* [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP.
* [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer.
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
* [PHP Migration](https://github.com/monque/PHP-Migration) - A static analyzer for PHP version migration.
* [PHPStan](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool.
* [Psalm](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications

### Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML

### Streams
*Libraries for working with streams.*

* [ByteStream](https://amphp.org/byte-stream/) - An asynchronous stream abstraction.
* [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library

### Strings
*Libraries for parsing and manipulating strings.*

* [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
* [Device Detector](https://github.com/matomo-org/device-detector) - Another library for parsing user agent strings.
* [Jieba-PHP](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
* [Portable UTF-8](https://github.com/voku/portable-utf8) - A string manipulation library with UTF-8 safe replacement methods.
* [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
* [Stringy](https://github.com/voku/Stringy) - A string manipulation library with multibyte support.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [URLify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
* [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs

### Task Runners
*Libraries for automating and running tasks.*

* [Bldr](https://bldr.io/) - A PHP Task runner built on Symfony components.
* [Jobby](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
* [Robo](https://github.com/consolidation/Robo) - A PHP Task runner with object-orientated configurations.
* [Task](https://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp

### Templating
*Libraries and tools for templating and lexing.*

* [Latte](https://latte.nette.org/) - The safest and truly intuitive templates for PHP.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
* [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
* [PHPTAL](https://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
* [Twig](https://twig.symfony.com/) - A comprehensive templating language

### Testing
*Libraries for testing codebases and generating test data.*

* [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library.
* [AspectMock](https://github.com/Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception.
* [Atoum](https://github.com/atoum/atoum) - A simple testing library.
* [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
* [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework.
* [Faker](https://github.com/fakerphp/faker) - A fake data generator library.
* [HTTP Mock](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
* [Infection](https://github.com/infection/infection) - An AST-based PHP Mutation testing framework.
* [Kahlan](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* [Mink](https://mink.behat.org/en/latest/) - Web acceptance testing.
* [Mockery](https://github.com/mockery/mockery) - A mock object library for testing.
* [ParaTest](https://github.com/paratestphp/paratest) - A parallel testing library for PHPUnit.
* [Pest](https://pestphp.com/) - A testing framework with a focus on simplicity.
* [Peridot](https://github.com/peridot-php/peridot) - An event driven test framework.
* [Phake](https://github.com/phake/phake) - Another mock object library for testing.
* [Pho](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework.
* [PHP-Mock](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
* [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) -  A MySQL engine written in pure PHP. 
* [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
* [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.
* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
* [Prophecy](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
* [VFS Stream](https://github.com/bovigo/vfsStream) - A virtual filesystem stream wrapper for testing

### Text Editors and IDEs
*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Apache NetBeans](https://netbeans.apache.org/) - An IDE with support for PHP and HTML5.
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* [VS Code](https://code.visualstudio.com/) - An open source code editor

### Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
* [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
* [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
* [Github](https://github.com/KnpLabs/php-github-api) - A library to interface with the Github API.
* [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
* [Square](https://github.com/square/connect-php-sdk) - The official Square PHP SDK for payments and other Square APIs.
* [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
* [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API

### URL
*Libraries for parsing URLs.*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
* [Purl](https://github.com/jwage/purl) - A URL manipulation library.
* [sabre/uri](https://github.com/sabre-io/uri) - A functional URI manipulation library.
* [Uri](https://github.com/thephpleague/uri) - Another URL manipulation library

### Validation
*Libraries for filtering and validating data.*

* [Assert](https://github.com/beberlei/assert) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
* [Aura.Filter](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
* [CakePHP Validation](https://github.com/cakephp/validation) - Another validation library.
* [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
* [JSON Schema](https://github.com/justinrainbow/json-schema) - A [JSON Schema](https://json-schema.org/) validation library.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
* [Respect Validation](https://github.com/Respect/Validation) - A simple validation library.
* [Upload](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation.
* [Valitron](https://github.com/vlucas/valitron) - Another validation library.
* [Volan](https://github.com/serkin/Volan) - Another simplified validation library
