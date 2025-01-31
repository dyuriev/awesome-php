# Awesome PHP
A curated list of amazingly awesome PHP libraries, resources and shiny things.

- [Awesome PHP](#awesome-php)
	- [Package Management](#package-management)
	- [Package Management Extras](#package-management-extras)
	- [Frameworks](#frameworks)
	- [Framework Extras](#framework-extras)
	- [Framework Components](#framework-components)
	- [Micro Frameworks](#micro-frameworks)
	- [Micro Framework Extras](#micro-framework-extras)
	- [Templating](#templating)
	- [Static Site Generators](#static-site-generators)
	- [HTTP](#http)
	- [URL](#url)
	- [Email](#email)
	- [Files](#files)
	- [Streams](#streams)
	- [Dependency Injection](#dependency-injection)
	- [Imagery](#imagery)
	- [Testing](#testing)
	- [Documentation](#documentation)
	- [Security](#security)
	- [Code Analysis](#code-analysis)
	- [Build Tools](#build-tools)
	- [Task Runners](#task-runners)
	- [Asset Management](#asset-management)
	- [Geolocation](#geolocation)
	- [Date and Time](#date-and-time)
	- [Event](#event)
	- [Logging](#logging)
	- [E-commerce](#e-commerce)
	- [PDF](#pdf)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [NoSQL](#nosql)
	- [Queue](#queue)
	- [Search](#search)
	- [Command Line](#command-line)
	- [Authentication](#authentication)
	- [Markup](#markup)
	- [Text and Numbers](#text-and-numbers)
	- [Filtering and Validation](#filtering-and-validation)
	- [REST and API](#rest-and-api)
	- [Caching](#caching)
	- [Data Structure and Storage](#data-structure-and-storage)
	- [Notifications](#notifications)
	- [Deployment](#deployment)
	- [Third Party APIs](#third-party-apis)
	- [Miscellaneous](#miscellaneous)
	- [Development Software](#development-software)
	- [Web Tools](#web-tools)
- [Resources](#resources)
	- [Websites](#websites)
	- [Books](#books)
	- [Web Reading](#web-reading)
	- [PHP Reading](#php-reading)
	- [PHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

## Package Management
*Libraries for package and dependency management.*

* [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager.
* [Composer Installers](https://github.com/composer/installers) - A  multi framework Composer library installer.

## Package Management Extras
*Extras related to package management.*

* [Satis](https://github.com/composer/satis) - A static Composer repository generator.
* [Composition](https://github.com/bamarni/composition) - A library to check your Composer environment at runtime.
* [Poser](https://github.com/FrenkyNet/Poser) - A Composer class aliasing library.
* [Version](https://github.com/herrera-io/php-version) - A parsing and comparison library for semantic versioning.
* [NameSpacer](https://github.com/ralphschindler/Namespacer) - A library to convert from underscores to namespaces.
* [Patch Installer](https://github.com/goatherd/patch-installer) - A library to install patches using Composer.
* [Composer Checker](https://github.com/silpion/composer-checker) - A tool to validate Composer configurations.

## Frameworks
*Web development frameworks.*

* [Symfony2](http://symfony.com/) - A framework comprised of individual components.
* [Zend Framework 2](http://framework.zend.com) - Another framework comprised of individual components.
* [Laravel 4](http://laravel.com/) - A simple PHP framework.
* [Aura PHP](http://auraphp.com/) - A framework of independent components.
* [Phalcon](http://phalconphp.com/en/) - A framework implemented as a C extension.

## Framework Extras
*Extras related to web development frameworks.*

* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.
* [Knp RAD Bundle](http://rad.knplabs.com/) - A Rapid Application Development (RAD) bundle for Symfony 2.

## Framework Components
*Standalone component from web development frameworks.*

* [Symfony2 Components](http://symfony.com/doc/master/components/index.html) - The components that make Symfony2.
* [Zend Framework 2 Components](https://packages.zendframework.com/) - The components that make ZF2.
* [Aura Components](http://auraphp.github.com/) - A package of PHP 5.4 components.
* [Hoa Project](http://hoa-project.net/En/) - Another package of PHP components.

## Micro Frameworks
*Micro frameworks and routers.*

* [Silex](http://silex.sensiolabs.org/) - A micro framework built around Symfony2 components.
* [Slim](http://www.slimframework.com/) - Another simple micro framework.
* [Bullet PHP](http://bulletphp.com/) - A micro framework for building REST APIs.
* [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
* [Pux](https://github.com/c9s/Pux) - Another fast routing library.

## Micro Framework Extras
*Extras related to micro frameworks and routers.*

* [Silex Skeleton](https://github.com/fabpot/Silex-Skeleton) - A project skeleton for Silex.
* [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - A web debug toolbar for Silex.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Silex/Symfony.
* [Slim Skeleton](https://github.com/codeguy/Slim-Skeleton) - A skeleton for Slim.
* [Slim View](https://github.com/codeguy/Slim-Views) - A collection of custom views for Slim.
* [Slim Middleware](https://github.com/codeguy/Slim-Middleware) - A collection of custom middleware for Slim.

## Templating
*Libraries and tools for templating and lexing.*

* [Twig](http://twig.sensiolabs.org/) - A comprehensive templating language.
* [Twig Cache Extension](https://github.com/asm89/twig-cache-extension) - A template fragment cache library for Twig.
* [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
* [Phly Mustache](https://github.com/weierophinney/phly_mustache) - Another PHP implementation of the Mustache template language.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Lex](https://github.com/pyrocms/lex) - A lightweight template parser.

## Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Sculpin](http://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Phrozn](http://phrozn.info) - Another tool that converts Textile, Markdown and Twig into HTML.

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [Guzzle](http://guzzlephp.org/) - A HTTP client.
* [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
* [Requests](https://github.com/rmccue/Requests) - A simple HTTP library.
* [Goutte](https://github.com/fabpot/Goutte) - A simple web scraper.
* [PHP VCR](http://php-vcr.github.io/) - A library for recording and replaying HTTP requests.

## URL
*Libraries for parsing URLs.*

* [Purl](https://github.com/jwage/purl) - A URL manipulation library.
* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.

## Email
*Libraries for sending and parsing email.*

* [SwiftMailer](http://swiftmailer.org/) - A mailer solution.
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
* [Fetch](https://github.com/tedivm/Fetch) - An IMAP library.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
* [Stampie](https://github.com/henrikbjorn/Stampie) - A library for email services such as [SendGrid](http://sendgrid.com), [PostMark](http://postmarkapp.com), [MailGun](http://www.mailgun.com) and [Mandrill](http://www.mandrill.com).

## Files
*Libraries for file manipulation and MIME type detection.*

* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
* [Flysystem](https://github.com/FrenkyNet/Flysystem) - Another filesystem abstraction layer.
* [Canal](https://github.com/dflydev/dflydev-canal) - A library to determine internet media types.
* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - A library that parses Apache MIME types.
* [Ferret](https://github.com/versionable/Ferret) - A MIME detection library.
* [Hoa Mime](https://github.com/hoaproject/Mime) - Another MIME detection library.
* [Lurker](https://github.com/henrikbjorn/Lurker) - A resource tracking library.
* [PHP File Locator](https://github.com/herrera-io/php-file-locator) - A library for locating files in large projects.
* [PHP FFmpeg](https://github.com/alchemy-fr/PHP-FFmpeg/) - A wrapper for the [FFmpeg](http://www.ffmpeg.org/) video library.
* [CSV](https://github.com/nyamsprod/Bakame.csv) - A CSV data manipulation library.
* [Cartographer](https://github.com/tackk/cartographer) - A sitemap generation library.

## Streams
*Libraries for working with streams.*

* [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

## Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* [Pimple](http://pimple.sensiolabs.org/) - A tiny dependency injection container.
* [Auryn](https://github.com/rdlowrey/Auryn) - Another dependency injection container.
* [Orno Di](https://github.com/orno/di) - Another flexible dependency injection container.
* [PHP DI](http://mnapoli.github.com/PHP-DI/) - A dependency injection implementation using annotations.
* [Acclimate](https://github.com/jeremeamia/acclimate) - A common interface to dependency injection containers and service locators.

## Imagery
*Libraries for manipulating images.*

* [Imagine](http://imagine.readthedocs.org/en/latest/index.html) - An image manipulation library.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.
* [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library.
* [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - A library to extract GIF animation frame information.
* [GIF Creator](https://github.com/Sybio/GifCreator) - A library to create GIF animations from multiple images.
* [Image With Text](https://github.com/nmcteam/image-with-text) - A library for embedding text into images.
* [Color Extractor](https://github.com/php-loep/color-extractor) - A library for extracting colours from images.

## Testing
*Libraries for testing codebases and generating test data.*

* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
* [DBUnit](https://github.com/sebastianbergmann/dbunit) - A database testing library for PHPUnit.
* [ParaTest](https://github.com/brianium/paratest) - A parallel testing library for PHPUnit.
* [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
* [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework.
* [Atoum](https://github.com/atoum/atoum) - A simple testing library.
* [Mockery](https://github.com/padraic/mockery) - A mock object library for testing.
* [Phake](https://github.com/mlively/Phake) - Another mock object library for testing.
* [Parody](https://github.com/dotink/Parody) - Yet another mock object library for testing.
* [Sismo](http://sismo.sensiolabs.org/) - A continuous testing server library.
* [Faker](https://github.com/fzaninotto/Faker) - A fake data generator library.
* [Samsui](https://github.com/mauris/samsui) - Another fake data generator library.
* [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library.
* [Behat](http://behat.org/) - A behaviour driven development (BDD) testing framework.
* [Pho](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework.
* [Mink](http://mink.behat.org/) - Web acceptance testing.
* [HTTP Mock](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
* [VFS Stream](https://github.com/mikey179/vfsStream) - A virtual filesystem stream wrapper for testing.
* [VFS](https://github.com/adlawson/vfs.php) - Another virtual filesystem for testing.
* [Locust](http://locust.io/) - A modern load test library written in Python.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform.
* [PHPCI](http://www.phptesting.org/) - An open source continuous integration platform for PHP.

## Documentation
*Libraries for generating project documentation.*

* [Sami](https://github.com/fabpot/Sami) - An API documentation generator.
* [APIGen](https://github.com/apigen/apigen) - Another API documentation generator.
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - A documentation generator.

## Security
*Libraries for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
* [RandomLib](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings.
* [True Random](https://github.com/pixeloution/true-random) - A library that generates random numbers using [www.random.org](http://www.random.org/).
* [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - A PHP security library.
* [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
* [PHPAss](http://www.openwall.com/phpass/) - A portable password hashing framework.
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
* [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
* [TCrypto](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library.
* [PHP IDS](https://github.com/PHPIDS/PHPIDS) - A structured PHP security layer.
* [PHP SSH](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
* [IniScan](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security.
* [SensioLabs Security Check](https://security.sensiolabs.org/) - A web tool to check your Composer dependecies for security advisories.
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - An integrated penetration testing tool for web applications.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
* [PHPPHP](https://github.com/ircmaxell/PHPPHP) - A PHP VM implementation in PHP.
* [PHPSandbox](https://github.com/fieryprophet/php-sandbox) - A PHP sandbox environment.
* [Dissect](https://github.com/jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [PHP Mess Detector](http://phpmd.org/) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code.
* [PHP Analyser](https://github.com/scrutinizer-ci/php-analyzer) - A library for analysing PHP code to find bugs and errors.
* [PHP CS Fixer](https://github.com/fabpot/PHP-CS-Fixer) - A coding standard fixer library.
* [PHP Manipulator](https://github.com/schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - A static metric library.
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - A command line utility for refactoring PHP code.
* [UBench](https://github.com/devster/ubench) - A simple micro benchmark library.
* [Athletic](https://github.com/polyfractal/athletic) - An annotation based benchmark framework.
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
* [PHPDBG](http://phpdbg.com/) - An interactive PHP debugger.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to scrutinise PHP code.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
* [xDebug](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
* [xHprof](https://github.com/phacility/xhprof) - Another profiling tool for PHP.

## Build Tools
*Project build and automation tools.*

* [Go](https://github.com/herrera-io/php-go) - A simple PHP build tool.
* [Bob](https://github.com/CHH/bob) - A simple project automation tool.
* [Phake](https://github.com/jaz303/phake) - A rake PHP clone library.
* [Box](https://github.com/kherge/Box) - A utility to build PHAR files.
* [Phing](http://www.phing.info/) - A PHP project build system inspired by Apache Ant.

## Task Runners
*Libraries for automating and running tasks.*
* [Task](http://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.
* [Robo](https://github.com/Codegyre/Robo) - A PHP Task runner with object-orientated configurations.
* [Bldr](http://bldr.io/) - A PHP Task runner built on Symfony components.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

* [Assetic](https://github.com/kriswallsmith/assetic) - An asset manager pipeline library.
* [Pipe](https://github.com/CHH/pipe) - Another asset manager pipeline library.
* [Munee](https://github.com/meenie/munee) - An asset optimiser library.
* [JShrink](https://github.com/tedivm/JShrink) - A JavaScript minifier library.
* [Puli](https://github.com/webmozart/puli) - A library for determining assets absolute paths.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCoder](http://geocoder-php.org/) - A geocoding library.
* [GeoTools](https://github.com/php-loep/Geotools) - A library of geo-related tools.
* [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library.
* [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.

## Date and Time
*Libraries for working with dates and times.*

* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
* [ExpressiveDate](https://github.com/jasonlewis/expressive-date) - Another DateTime API extension.
* [CalendR](http://yohan.giarel.li/CalendR) - A calendar management library.

## Event
*Libraries that are event-driven or implement non-blocking event loops.*

* [React](https://github.com/reactphp/react) - An event driven non-blocking I/O library.
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - A reactive extension library.
* [Ratchet](https://github.com/cboden/Ratchet) - A web socket library.
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - Another web socket library.
* [Hoa EventSource](https://github.com/hoaproject/Eventsource) - An event source library.
* [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
* [FuelPHP Event](https://github.com/fuelphp/event) - Another event dispatcher library.

## Logging
*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.
* [KLogger](https://github.com/katzgrau/KLogger) - An easy-to-use PSR-3 compliant logging class.

## E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [OmniPay](https://github.com/adrianmacneil/omnipay) - A framework agnostic multi-gateway payment processing library.
* [Payum](https://github.com/payum/payum) - A payment abstraction library.
* [Sylius](http://www.sylius.org/) - An open source e-commerce solution.
* [Thelia](http://thelia.net/v2/) - Another open source e-commerce solution.
* [Money](https://github.com/mathiasverraes/money) - A PHP implementation of Fowler's money pattern.
* [Sebastian Money](https://github.com/sebastianbergmann/money) - Another library for working with monetary values.
* [Swap](https://github.com/florianv/swap) - An exchange rates library.

## PDF
*Libraries and software for working with PDF files.*

* [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
* [WKHTMLToPDF](https://github.com/antialize/wkhtmltopdf) - A tool to convert HTML to PDF.

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [Doctrine](http://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - A migration library for Doctrine.
* [Doctrine Extensions](https://github.com/l3pp4rd/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
* [Propel](http://www.propelorm.org/) - A fast ORM.
* [Eloquent](https://github.com/illuminate/database) - The Laravel 4 ORM.
* [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
* [Spot](https://github.com/vlucas/Spot) - A MySQL datamapper ORM.
* [RedBean](http://redbeanphp.com/) - A lightweight, configuration-less ORM.
* [PHP ActiveRecord](https://github.com/kla/php-activerecord) - A PHP Active Record implementation.
* [Paris and Idiorm](http://j4mie.github.io/idiormandparis/) - A minimalist database library.
* [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
* [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library.
* [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library.
* [Phinx](https://github.com/robmorgan/phinx) - Another database migration library.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.

## NoSQL
*Libraries for working with "NoSQL" backends.*

* [MongoQB](https://github.com/alexbilbie/MongoQB) - A MongoDB query builder library.
* [Monga](https://github.com/thephpleague/monga) - A MongoDB abstraction library.
* [Predis](https://github.com/nrk/predis) - A feature complete Redis library.

## Queue
*Libraries for working with event and task queues.*

* [Pheanstalk](https://github.com/pda/pheanstalk) - A Beanstalkd client library.
* [PHP AMQP](https://github.com/videlalvaro/php-amqplib) - A pure PHP AMQP library.
* [Thumper](https://github.com/videlalvaro/Thumper) - A RabbitMQ pattern library.
* [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.

## Search
*Libraries and software for indexing and performing search queries on data.*

* [ElasticSearch PHP](https://github.com/elasticsearch/elasticsearch-php) - The official client library for [ElasticSearch](http://www.elasticsearch.org/).
* [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
* [Solarium](http://www.solarium-project.org/) - A client library for [Solr](http://lucene.apache.org/solr/).

## Command Line
*Libraries for building command line utilities.*

* [Boris](https://github.com/d11wtq/boris) - A tiny PHP REPL.
* [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL.
* [Pecan](https://github.com/mcrumm/pecan) - An event-driven, non-blocking shell.
* [GetOpt](https://github.com/ulrichsg/getopt-php) - A command line opt parser.
* [OptParse](https://github.com/CHH/optparse) - Another command line opt parser.
* [Commando](https://github.com/nategood/commando) - Another simple command line opt parser.
* [GetOptionKit](https://github.com/c9s/php-GetOptionKit) - Another command line opt parser.
* [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
* [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.
* [Hoa Console](https://github.com/hoaproject/Console) - Another command line library.
* [Shunt](https://github.com/php-loep/shunt) - A library for running commands in parallel on multiple remote machines.

## Authentication
*Libraries for implementing authentications schemes.*

* [Sentry](https://github.com/cartalyst/sentry) - A framework agnostic authentication & authorisation library.
* [Sentry Social](http://docs.cartalyst.com/sentry-social-2/introduction) - A library for social network authentication.
* [OPAuth](https://github.com/opauth/opauth) - A multi-provider authentication framework.
* [OAuth2](https://github.com/php-loep/oauth2-server) - An OAuth2 authentication server, resource server and client library.
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
* [TwitterOAuth](https://github.com/ruudk/twitteroauth) - A Twitter OAuth library.
* [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - A fully tested Twitter SDK.
* [Hawk](https://github.com/dflydev/dflydev-hawk) - A Hawk HTTP authentication library.

## Markup
*Libraries for working with markup.*

* [Decoda](http://milesj.me/code/php/decoda) - A lightweight markup parser library.
* [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.
* [Dflydev Markdown](https://github.com/dflydev/dflydev-markdown) - Another Markdown parser.
* [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
* [Ciconia](https://github.com/kzykhys/Ciconia) - Another Markdown parser that supports Github flavoured Markdown.
* [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 convertor library.
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
* [Hoa String](https://github.com/hoaproject/String) - Another UTF-8 string library.
* [Stringy](https://github.com/danielstjules/Stringy) - A string manipulation library with multibyte support.
* [Numbers PHP](https://github.com/powder96/numbers.php) - A library for working with numbers.
* [Math](https://github.com/moontoast/math) - A library for working with large numbers.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
* [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs.
* [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs.
* [Urlify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
* [Text](https://github.com/kzykhys/Text) - A text manipulation library.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
* [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.

## Filtering and Validation
*Libraries for filtering and validating data.*

* [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
* [Respect Validate](https://github.com/Respect/Validation) - A simple validation library.
* [Valitron](https://github.com/vlucas/valitron) - Another validation library.
* [Upload](https://github.com/codeguy/Upload) - A library for handling file uploads and validation.
* [DMS Filter](https://github.com/rdohms/DMS-Filter) - An annotation filtering library.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating various ISO and ZIP codes (IBAN, SWIFT/BIC, BBAN, VAT, SSN, UKNIN).

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2.
* [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.

## Caching
*Libraries for caching data.*

* [Alternative PHP Cache (APC)](http://www.php.net/manual/en/book.apc.php) - Open opcode cache for PHP.
* [Cache](https://github.com/doctrine/cache) - A caching library (part of Doctrine).
* [Stash](https://github.com/tedivm/Stash) - Another library for caching.

## Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [Ardent](https://github.com/morrisonlevi/Ardent) - A library of data structures.
* [PHP Collections](https://github.com/schmittjoh/php-collection) - A simple collections library.
* [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
* [PHP Object Storage](https://github.com/herrera-io/php-object-storage) - A library for object storage.
* [Fractal](https://github.com/php-loep/fractal) - A library for converting complex data structures to JSON output.

## Notifications
*Libraries for working with notification software.*

* [Nod](https://github.com/filp/nod) - A notification library (e.g., Growl).
* [Notificato](https://github.com/wrep/notificato) - A library for handling push notifications.
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
* [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.

## Deployment

* [Pomander](https://github.com/tamagokun/pomander) - A deployment tool for PHP applications.
* [Rocketeer](https://github.com/Anahkiasen/rocketeer) - A fast and easy deployer for the PHP world.

## Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
* [S3 Stream Wrapper](https://github.com/gwkunze/S3StreamWrapper) - A stream wrapper library for Amazon S3.
* [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
* [Campaign Monitor](http://campaignmonitor.github.com/createsend-php/) - The official Campaign Monitor PHP library.
* [Digital Ocean](https://github.com/toin0u/DigitalOcean) - A library to interface with the Digital Ocean API.
* [Github](https://github.com/dsyph3r/github-api3-php) - A library to interface with the Github API.
* [PHP Github API](https://github.com/KnpLabs/php-github-api) - Another library to interface with the Github API.
* [Twitter OAuth](https://github.com/widop/twitter-oauth) - A library to interface with Twitter's OAuth workflow.
* [Twitter REST](https://github.com/widop/twitter-rest) - A library to interact with Twitter's REST API.
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php) - The official PHP Dropbox SDK library.
* [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.
* [HybridAuth](https://github.com/hybridauth/hybridauth) - An open source social sign on library.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Spork](https://github.com/kriswallsmith/spork) - A process forking library.
* [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
* [JSONPCallbackValidator](https://github.com/willdurand/JsonpCallbackValidator) - A library for validating JSONP callbacks.
* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
* [Ruler](https://github.com/bobthecow/Ruler) - A simple stateless production rules engine.
* [LiteCQRS](https://github.com/beberlei/litecqrs-php) - A CQRS (Command Query Responsibility Separation) library.
* [Sslurp](https://github.com/EvanDotPro/Sslurp) - A library that makes dealing with SSL suck less.
* [PHP Option](https://github.com/schmittjoh/php-option) An option type library.
* [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library.
* [Sabre VObject](https://github.com/evert/sabre-vobject) - A library for parsing VCard and iCalendar objects.
* [Annotations](https://github.com/doctrine/annotations) - An annotations library (part of Doctrine).
* [Whoops](https://github.com/filp/whoops) - A pretty error handling library.
* [Finite](http://yohan.giarel.li/Finite) - A simple PHP finite state machine.
* [LadyBug](https://github.com/raulfraile/Ladybug) - A dumper library.
* [Plum](https://github.com/aerialls/Plum) - A deployer library.
* [Procrastinator](https://github.com/lstrojny/Procrastinator) - A library for running time consuming tasks.
* [Compose](https://github.com/igorw/compose) - A function composition library.
* [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized.
* [Jumper](https://github.com/kakawait/Jumper) - A remote service executor library.
* [Underscore](http://anahkiasen.github.io/underscore-php/) - A PHP port of the Underscore JS library.
* [PHP PassBook](https://github.com/eymengunay/php-passbook) - A PHP library for iOS PassBook.
* [PHP Expression](https://github.com/Kitano/php-expression) - A PHP expression language.
* [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software.
* [Wise](https://github.com/herrera-io/php-wise) - A configuration manager.
* [Opengraph](https://github.com/euskadi31/Opengraph) - An opengraph library.
* [Essence](https://github.com/felixgirault/essence) - A library for extracting web media.
* [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
* [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
* [Monad PHP](https://github.com/ircmaxell/monad-php) - A simple Monad library.
* [Flux](https://github.com/selvinortiz/flux) - A regular expression building library.
* [Patchwork](http://antecedent.github.io/patchwork/) - A library for redefining userland functions.
* [Galapagos](https://github.com/igorw/galapagos) - Evolutionary language transformation.
* [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
* [PHPCR](https://github.com/phpcr/phpcr) - A PHP port of the Java Content Repository (JCR).
* [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
* [ClassPreloader](https://github.com/mtdowling/ClassPreloader) - A library for optimising autoloading.
* [Lib Country](https://github.com/phine/lib-country) - A library for country and subdivision data.
* [Lib Accessor](https://github.com/phine/lib-accessor) - A library for simplifying accessors.
* [PHPStack](http://dunkels.com/adam/phpstack/) - A TCP/IP stack proof of concept written in PHP.
* [Nmap](https://github.com/willdurand/nmap) - A PHP wrapper around [Nmap](http://nmap.org/).
* [Code Mover](https://github.com/dantleech/code-mover) - A library for moving code.
* [Iter](https://github.com/nikic/iter) - A library that provides iteration primatives using generators.
* [Lambda PHP](https://github.com/igorw/lambda-php) - A Lambda calculus interpreter in PHP.
* [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* [PHP-GPIO](https://github.com/ronanguilloux/php-gpio) - A library for playing with the Raspberry PI's GPIO pins.

## Development Software
*Software for creating a development environment.*

* [HomeBrew](http://mxcl.github.com/homebrew/) - A package manager for OSX.
* [HomeBrew PHP](https://github.com/josegonzalez/homebrew-php) - A PHP tap for HomeBrew.
* [PHP OSX](http://php-osx.liip.ch/) - A PHP installer for OSX.
* [HipHop PHP](https://github.com/facebook/hiphop-php) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
* [Ansible](http://www.ansibleworks.com/) - A radically simple orchestration framework.
* [Puppet](http://puppetlabs.com/) - A server automation framework and application.
* [Chef](https://github.com/opscode/chef) - A systems integration framework.
* [SaltStack](http://saltstack.com/community.html) - An infrastructure management tool.
* [PHP Brew](https://github.com/c9s/phpbrew) - A PHP version manager and installer.
* [PHP Env](https://github.com/CHH/phpenv) - Another PHP version manager.
* [PHP Switch](https://github.com/jubianchi/phpswitch) - Another version manager.
* [PHP Build](https://github.com/CHH/php-build) - Another PHP version installer.
* [CodeKit](http://incident57.com/codekit/) - A general web development tool.
* [HTTPie](https://github.com/jkbr/httpie) - A command line alternative to cURL written in Python.
* [Backup](https://github.com/meskyanichi/backup) - A server backup tool written in Ruby.

## Web Tools
*Web-based tools.*

* [PuPHPet](https://puphpet.com/) - A web tool for building PHP development virtual machines.
* [Protobox](http://getprotobox.com/) - Another web tool for building PHP development virtual machines.
* [Phansible](http://phansible.com/) - A web tool for building PHP development virtual machines with Ansible.
* [3V4L](http://3v4l.org/) - An online PHP shell.
* [DBV](http://dbv.vizuina.com/) - A database version control application.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
* [Composer as a Service](http://composer.borreli.com/) - A tool for downloading Composer packages as a zip file.
* [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

## Websites
*Useful web and PHP-related websites and newsletters.*

* [PHP The Right Way](http://www.phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP Best Practices](http://phpbestpractices.org/) - A PHP best practice guide.
* [PHP Weekly](http://phpweekly.info/archive/) - A weekly PHP newsletter.
* [PHP Security](http://phpsecurity.readthedocs.org/en/latest/index.html) - A guide to PHP security.
* [PHP Internals](http://www.phpinternalsbook.com/) - A book about the PHP internals.
* [PHP FIG](http://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP UG](http://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - An open software security community.
* [WebSec IO](http://websec.io/) - A web security community resource.
* [Web Advent](http://webadvent.org) - An advent calendar for web developers.
* [Mozilla Developer Network](https://developer.mozilla.org/en-US) - A website of shared knowledge for the open web.
* [HTML5Rocks](http://www.html5rocks.com) - A resource for open web HTML5 developers.
* [Programming with Anthony](http://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [Seven PHP](http://7php.com/) - A website that interviews members of the PHP community.

## Books
*Fantastic books and e-books.*

* [Scaling PHP Applications](http://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](http://www.brandonsavage.net) - A book about object-orientated PHP by Brandon Savage.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [Understanding Computation](http://computationbook.com) - A book about computation theory by Tom Stuart.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - An ebook about common security terms and practices for PHP by Chris Cornutt.

## Web Reading
*General web-development-related reading materials.*

* [OWASP PHP Security Cheat Sheet](https://www.owasp.org/index.php/PHP_Security_Cheat_Sheet) - A PHP security cheatsheet.
* [C is for Cookie, H is for Hacker](http://www.troyhunt.com/2013/03/c-is-for-cookie-h-is-for-hacker.html) - An article about cookies and security.
* [You Blew It Loading Your Login Form Over HTTP](http://www.troyhunt.com/2013/05/your-login-form-posts-to-https-but-you.html) - An article about using HTTPS correctly with login forms.
* [How HTTPS Secures Your Connection](http://blog.hartleybrody.com/https-certificates/) - An article explaining how TLS/SSL secures your connection.
* [How to Build a Secure Remember Me Feature](http://www.troyhunt.com/2013/07/how-to-build-and-how-not-to-build.html) - An article on how to build a secure remember me feature.
* [A Beginners Guide to HTTP Cache Headers](http://www.mobify.com/blog/beginners-guide-to-http-cache-headers/) - An article about HTTP cache headers.
* Beyond Series [1](http://blog.ircmaxell.com/2013/09/beyond-design-patterns.html) [2](http://blog.ircmaxell.com/2013/11/beyond-inheritance.html) [3](http://blog.ircmaxell.com/2013/11/beyond-object-oriented-programming.html) [4](http://blog.ircmaxell.com/2013/11/beyond-clean-code.html) - A series of articles about programming by Anthony Ferrara.
* [Semantic Versioning](http://semver.org/) - A website explaining semantic versioning.
* [Atlassian Git Tutorials](https://www.atlassian.com/git) - A series of Git tutorials.
* [Hg Init](http://hginit.com/) - A series of Mercurial tutorials.

## PHP Reading
*PHP-releated reading materials.*

* [Create Your Own PHP Framework](http://fabien.potencier.org/article/50/create-your-own-framework-on-top-of-the-symfony2-components-part-1) - A series of articles on how to make your own PHP framework by Fabien Potencier.
* [Seven Ways to Screw Up BCrypt](http://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - An article about correct BCrypt implementation.
* [Preventing CSRF Attacks](http://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - An article on preventing CSRF attacks.
* [Don't Worry About BREACH](http://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - An article about the BREACH hack and CSRF tokens.
* [On PHP 5.3, Lamda Functions and Closures](http://fabien.potencier.org/article/17/on-php-5-3-lambda-functions-and-closures) - An article about lambda functions and closures.
* [Use Env](http://seancoates.com/blogs/use-env) - An article about using the unix environment helper.
* [Composer Primer](http://daylerees.com/composer-primer) - A Composer primer.
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - An article about Composer versioning.
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - An article about Composer stability flags.
* [Innocent Villagefolk or a Pillagin’ Pirate?](http://blog.astrumfutura.com/2012/04/php-innocent-villagefolk-or-a-pillagin-pirate/) - An article about PHP taking ideas from other language.
* [Predicting Random Numbers in PHP](http://blog.astrumfutura.com/2013/03/predicting-random-numbers-in-php-its-easier-than-you-think/) - An article about generating random numbers.
* [A 20 Point List for Preventing XSS in PHP](http://blog.astrumfutura.com/2013/04/20-point-list-for-preventing-cross-site-scripting-in-php/) - An article about preventing XSS.
* [PHP Sucks! But I Like It!](http://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - An article about the pros and cons of PHP.
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/article/64/php-is-much-better-than-you-think) - An article about the PHP language and ecosystem.

## PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [PHP Internals Book](http://www.phpinternalsbook.com) - An online book about PHP internals, written by three core developers.
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/article/8/print-vs-echo-which-one-is-faster) - An article about print and echo performance.
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/article/48/the-php-ternary-operator-fast-or-not) - An article ternary performance.
* [Disproving the Single Quotes Myth](http://nikic.github.com/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - An article about performance of single and double quoted strings.
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - An article about internal ZVALs.
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - An article about string internals.
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - An article about opcodes.
* [How Foreach Works](http://stackoverflow.com/questions/10057671/how-foreach-actually-works/14854568#14854568) - A detailed StackOverflow answer about foreach.
* [When Does Foreach Copy?](http://nikic.github.com/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - An article about the internals of foreach.
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.com/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - An article about array internals.
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - An article about evaluation order in PHP.
* PHP Source Code for Developers: [1](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers.html) [2](http://nikic.github.com/2012/03/16/Understanding-PHPs-internal-function-definitions.html) [3](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers_21.html) [4](http://nikic.github.com/2012/03/28/Understanding-PHPs-internal-array-implementation.html) - A series about the PHP source code.
* Collecting Garbage: [1](http://www.php.net/manual/en/features.gc.refcounting-basics.php) [2](http://www.php.net/manual/en/features.gc.collecting-cycles.php) [3](http://www.php.net/manual/en/features.gc.performance-considerations.php) - A series about the PHP garbage collection internals.

# Contributing
Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) for details.
