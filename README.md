# Sulu Hello World Application

## Installation

```
[piotr@piotr-pc Development]$ composer create-project sulu/skeleton sulu-hello-world -n
Creating a "sulu/skeleton" project at "./sulu-hello-world"
Installing sulu/skeleton (2.1.0)
  - Installing sulu/skeleton (2.1.0): Downloading (100%)         
Created project in /home/piotr/Development/sulu-hello-world
> php -r "file_put_contents('.env.local', 'APP_ENV=dev' . PHP_EOL);"
> php -r "file_put_contents('.env', str_replace('APP_SECRET=', 'APP_SECRET=' . bin2hex(random_bytes(16)), file_get_contents('.env')));"
Loading composer repositories with package information
Updating dependencies (including require-dev)
Package operations: 152 installs, 0 updates, 0 removals
  - Installing symfony/flex (v1.9.1): Loading from cache
Symfony operations: 1 recipe (344394e639bf7c52e76a76d324293459)
  - Configuring symfony/flex (>=1.0): From github.com/symfony/recipes:master
Loading composer repositories with package information
Updating dependencies (including require-dev)

Prefetching 28 packages 🎶 💨
  - Downloading (100%)

Package operations: 151 installs, 0 updates, 0 removals
  - Installing ocramius/package-versions (1.9.0): Loading from cache
  - Installing symfony/thanks (v1.2.9): Loading from cache
  - Installing handcraftedinthealps/zendsearch (2.0.0): Loading from cache
  - Installing twig/twig (v3.0.4): Loading from cache
  - Installing symfony/polyfill-mbstring (v1.18.0): Loading from cache
  - Installing psr/log (1.1.3): Loading from cache
  - Installing symfony/polyfill-php80 (v1.18.0): Loading from cache
  - Installing symfony/polyfill-php73 (v1.18.0): Loading from cache
  - Installing symfony/deprecation-contracts (v2.1.3): Loading from cache
  - Installing symfony/http-foundation (v5.1.2): Loading from cache
  - Installing symfony/polyfill-intl-normalizer (v1.18.0): Loading from cache
  - Installing symfony/polyfill-intl-idn (v1.18.0): Loading from cache
  - Installing symfony/mime (v5.1.2): Loading from cache
  - Installing psr/event-dispatcher (1.0.0): Loading from cache
  - Installing symfony/event-dispatcher-contracts (v2.1.3): Loading from cache
  - Installing symfony/event-dispatcher (v5.1.2): Loading from cache
  - Installing symfony/var-dumper (v5.1.2): Loading from cache
  - Installing symfony/error-handler (v5.1.2): Loading from cache
  - Installing symfony/http-kernel (v5.1.2): Loading from cache
  - Installing symfony/translation-contracts (v2.1.3): Loading from cache
  - Installing psr/container (1.0.0): Loading from cache
  - Installing psr/cache (1.0.1): Loading from cache
  - Installing symfony/twig-bridge (v5.1.2): Loading from cache
  - Installing symfony/filesystem (v5.1.2): Loading from cache
  - Installing symfony/config (v5.1.2): Loading from cache
  - Installing symfony/twig-bundle (v5.1.2): Loading from cache
  - Installing symfony/service-contracts (v2.1.3): Loading from cache
  - Installing symfony/dependency-injection (v5.1.2): Loading from cache
  - Installing doctrine/lexer (1.2.1): Loading from cache
  - Installing egulias/email-validator (2.1.18): Loading from cache
  - Installing swiftmailer/swiftmailer (v6.2.3): Loading from cache
  - Installing symfony/swiftmailer-bundle (v3.4.0): Loading from cache
  - Installing symfony/polyfill-intl-grapheme (v1.18.0): Loading from cache
  - Installing symfony/string (v5.1.2): Loading from cache
  - Installing symfony/property-info (v5.1.2): Loading from cache
  - Installing symfony/inflector (v5.1.2): Loading from cache
  - Installing symfony/property-access (v5.1.2): Loading from cache
  - Installing symfony/security-core (v5.1.2): Loading from cache
  - Installing symfony/security-http (v5.1.2): Loading from cache
  - Installing symfony/security-guard (v5.1.2): Loading from cache
  - Installing symfony/security-csrf (v5.1.2): Loading from cache
  - Installing symfony/security-bundle (v5.1.2): Loading from cache
  - Installing monolog/monolog (2.1.0): Loading from cache
  - Installing symfony/monolog-bridge (v5.1.2): Loading from cache
  - Installing symfony/monolog-bundle (v3.5.0): Loading from cache
  - Installing symfony/routing (v5.1.2): Loading from cache
  - Installing symfony/finder (v5.1.2): Loading from cache
  - Installing symfony/var-exporter (v5.1.2): Loading from cache
  - Installing symfony/cache-contracts (v2.1.3): Loading from cache
  - Installing symfony/cache (v5.1.2): Loading from cache
  - Installing symfony/framework-bundle (v5.1.2): Loading from cache
  - Installing symfony/dotenv (v5.1.2): Loading from cache
  - Installing sulu/sulu (2.1.0): Loading from cache
  - Installing jackalope/jackalope-doctrine-dbal (1.4.1): Loading from cache
  - Installing jackalope/jackalope (1.4.0): Loading from cache
  - Installing symfony/console (v5.1.2): Loading from cache
  - Installing phpcr/phpcr (2.1.5): Loading from cache
  - Installing phpcr/phpcr-utils (1.4.1): Loading from cache
  - Installing doctrine/event-manager (1.1.0): Loading from cache
  - Installing doctrine/cache (1.10.2): Loading from cache
  - Installing doctrine/annotations (1.10.3): Loading from cache
  - Installing doctrine/reflection (1.2.1): Loading from cache
  - Installing doctrine/collections (1.6.6): Loading from cache
  - Installing doctrine/persistence (1.3.7): Loading from cache
  - Installing doctrine/inflector (1.4.3): Loading from cache
  - Installing doctrine/common (2.13.3): Loading from cache
  - Installing doctrine/dbal (2.10.2): Loading from cache
  - Installing php-http/discovery (1.9.1): Loading from cache
  - Installing clue/stream-filter (v1.4.1): Loading from cache
  - Installing psr/http-message (1.0.1): Loading from cache
  - Installing php-http/message-factory (v1.0.2): Loading from cache
  - Installing php-http/message (1.8.0): Loading from cache
  - Installing php-http/promise (1.1.0): Loading from cache
  - Installing symfony/options-resolver (v5.1.2): Loading from cache
  - Installing psr/http-factory (1.0.1): Loading from cache
  - Installing psr/http-client (1.0.1): Loading from cache
  - Installing php-http/httplug (2.2.0): Loading from cache
  - Installing php-http/client-common (2.3.0): Loading from cache
  - Installing symfony/http-client-contracts (v2.1.3): Loading from cache
  - Installing symfony/http-client (v5.1.2): Loading from cache
  - Installing ralouphie/getallheaders (3.0.3): Loading from cache
  - Installing guzzlehttp/psr7 (1.6.1): Loading from cache
  - Installing guzzlehttp/promises (v1.3.1): Loading from cache
  - Installing guzzlehttp/guzzle (6.5.5): Loading from cache
  - Installing php-http/guzzle6-adapter (v2.0.1): Loading from cache
  - Installing friendsofsymfony/http-cache (2.9.2): Loading from cache
  - Installing friendsofsymfony/http-cache-bundle (2.8.0): Loading from cache
  - Installing symfony/doctrine-bridge (v5.1.2): Loading from cache
  - Installing doctrine/instantiator (1.3.1): Loading from cache
  - Installing doctrine/orm (v2.7.3): Loading from cache
  - Installing doctrine/sql-formatter (1.1.0): Loading from cache
  - Installing doctrine/doctrine-bundle (2.1.0): Loading from cache
  - Installing doctrine/data-fixtures (1.4.3): Loading from cache
  - Installing doctrine/doctrine-fixtures-bundle (3.3.1): Loading from cache
  - Installing doctrine/phpcr-bundle (2.1.1): Loading from cache
  - Installing phpcr/phpcr-migrations (1.2.0): Loading from cache
  - Installing dantleech/phpcr-migrations-bundle (1.2.0): Loading from cache
  - Installing symfony/lock (v5.1.2): Loading from cache
  - Installing toflar/psr6-symfony-http-cache-store (2.3.1): Loading from cache
  - Installing symfony/yaml (v5.1.2): Loading from cache
  - Installing symfony/validator (v5.1.2): Loading from cache
  - Installing symfony/translation (v5.1.2): Loading from cache
  - Installing webimpress/safe-writer (2.0.1): Loading from cache
  - Installing laminas/laminas-zendframework-bridge (1.0.4): Loading from cache
  - Installing laminas/laminas-eventmanager (3.2.1): Loading from cache
  - Installing laminas/laminas-code (3.4.1): Loading from cache
  - Installing ocramius/proxy-manager (2.8.1): Loading from cache
  - Installing symfony/proxy-manager-bridge (v5.1.2): Loading from cache
  - Installing symfony/process (v5.1.2): Loading from cache
  - Installing symfony/intl (v5.1.2): Loading from cache
  - Installing symfony/polyfill-intl-icu (v1.18.0): Loading from cache
  - Installing symfony/form (v5.1.2): Loading from cache
  - Installing symfony/expression-language (v5.1.2): Loading from cache
  - Installing symfony/dom-crawler (v5.1.2): Loading from cache
  - Installing symfony/css-selector (v5.1.2): Loading from cache
  - Installing symfony/asset (v5.1.2): Loading from cache
  - Installing symfony-cmf/slugifier-api (2.0.0): Loading from cache
  - Installing symfony-cmf/routing (2.3.2): Loading from cache
  - Installing symfony-cmf/routing-bundle (2.4.0): Loading from cache
  - Installing ramsey/uuid (3.9.3): Loading from cache
  - Installing mustangostang/spyc (0.6.3): Loading from cache
  - Installing piwik/device-detector (3.12.6): Loading from cache
  - Installing pagerfanta/pagerfanta (v2.3.0): Loading from cache
  - Installing oro/doctrine-extensions (1.3.0): Loading from cache
  - Installing jms/metadata (2.3.0): Loading from cache
  - Installing massive/search-bundle (2.2.3): Loading from cache
  - Installing massive/build-bundle (0.5.0): Loading from cache
  - Installing layershifter/tld-support (1.1.1): Loading from cache
  - Installing layershifter/tld-database (1.0.69): Loading from cache
  - Installing layershifter/tld-extract (2.0.1): Loading from cache
  - Installing jms/serializer (3.8.0): Loading from cache
  - Installing jms/serializer-bundle (3.7.0): Loading from cache
  - Installing imagine/imagine (1.2.3): Loading from cache
  - Installing goodby/csv (1.3.0): Loading from cache
  - Installing behat/transliterator (v1.3.0): Loading from cache
  - Installing gedmo/doctrine-extensions (v2.4.41): Loading from cache
  - Installing handcraftedinthealps/rest-routing-bundle (1.0.0): Loading from cache
  - Installing willdurand/jsonp-callback-validator (v1.1.0): Loading from cache
  - Installing willdurand/negotiation (v2.3.1): Loading from cache
  - Installing friendsofsymfony/rest-bundle (3.0.2): Loading from cache
  - Installing symfony/serializer (v5.1.2): Loading from cache
  - Installing friendsofsymfony/jsrouting-bundle (2.6.0): Loading from cache
  - Installing dragonmantank/cron-expression (v3.0.0): Loading from cache
  - Installing contao/imagine-svg (1.0.1): Loading from cache
  - Installing antishov/doctrine-extensions-bundle (v1.4.2): Loading from cache
  - Installing aferrandini/urlizer (1.0.0): Loading from cache
  - Installing dantleech/glob-finder (1.0.0): Loading from cache
  - Installing phpcr/phpcr-shell (1.2.0): Loading from cache
  - Installing symfony/debug-bundle (v5.1.2): Loading from cache
  - Installing symfony/phpunit-bridge (v5.1.2): Loading from cache
  - Installing symfony/web-profiler-bundle (v5.1.2): Loading from cache
Package layershifter/tld-support is abandoned, you should avoid using it. No replacement was suggested.
Package layershifter/tld-extract is abandoned, you should avoid using it. No replacement was suggested.
Writing lock file
Generating autoload files
ocramius/package-versions: Generating version class...
ocramius/package-versions: ...done generating version class
84 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
Symfony operations: 26 recipes (344394e639bf7c52e76a76d324293459)
  - Configuring symfony/framework-bundle (>=5.1): From github.com/symfony/recipes:master
  - Configuring symfony/twig-bundle (>=5.0): From github.com/symfony/recipes:master
  - Configuring symfony/swiftmailer-bundle (>=2.5): From github.com/symfony/recipes:master
  - Configuring symfony/security-bundle (>=5.1): From github.com/symfony/recipes:master
  - Configuring symfony/monolog-bundle (>=3.3): From github.com/symfony/recipes:master
  - Configuring symfony/routing (>=5.1): From github.com/symfony/recipes:master
  - Configuring symfony/console (>=5.1): From github.com/symfony/recipes:master
  - Configuring doctrine/annotations (>=1.0): From github.com/symfony/recipes:master
  - Configuring friendsofsymfony/http-cache-bundle (>=2.8.0): From auto-generated recipe
  - Configuring doctrine/doctrine-bundle (>=2.0): From github.com/symfony/recipes:master
  - Configuring doctrine/doctrine-fixtures-bundle (>=3.0): From github.com/symfony/recipes:master
  - Configuring doctrine/phpcr-bundle (>=2.0): From github.com/symfony/recipes-contrib:master
  - Configuring dantleech/phpcr-migrations-bundle (>=1.2.0): From auto-generated recipe
  - Configuring symfony/validator (>=4.3): From github.com/symfony/recipes:master
  - Configuring symfony/translation (>=3.3): From github.com/symfony/recipes:master
  - Configuring symfony-cmf/routing-bundle (>=2.4.0): From auto-generated recipe
  - Configuring massive/search-bundle (>=2.2.3): From auto-generated recipe
  - Configuring massive/build-bundle (>=0.5.0): From auto-generated recipe
  - Configuring jms/serializer-bundle (>=3.0): From github.com/symfony/recipes-contrib:master
  - Configuring handcraftedinthealps/rest-routing-bundle (>=1.0.0): From auto-generated recipe
  - Configuring friendsofsymfony/rest-bundle (>=2.2): From github.com/symfony/recipes-contrib:master
  - Configuring friendsofsymfony/jsrouting-bundle (>=2.3): From github.com/symfony/recipes-contrib:master
  - Configuring antishov/doctrine-extensions-bundle (>=1.4): From github.com/symfony/recipes-contrib:master
  - Configuring symfony/debug-bundle (>=4.1): From github.com/symfony/recipes:master
  - Configuring symfony/phpunit-bridge (>=4.3): From github.com/symfony/recipes:master
  - Configuring symfony/web-profiler-bundle (>=3.3): From github.com/symfony/recipes:master
Executing script cache:clear [OK]
Executing script assets:install public [OK]
Executing script bin/websiteconsole cache:clear [OK]
Executing script bin/adminconsole sulu:media:init [OK]
Executing script bin/adminconsole massive:search:init [OK]

Some files may have been created or updated to configure your new packages.
Please review, edit and commit them: these files are yours.

Some files may have been created or updated to configure your new packages.
Please review, edit and commit them: these files are yours.

              
 What's next? 
              

  * Run your application:
    1. Go to the project directory
    2. Create your code repository with the git init command
    3. Download the Symfony CLI at https://symfony.com/download to install a development web server

  * Read the documentation at https://symfony.com/doc

                        
 Database Configuration 
                        

  * Modify your DATABASE_URL config in .env

  * Configure the driver (mysql) and
    server_version (5.7) in config/packages/doctrine.yaml

              
 How to test? 
              

  * Write test cases in the tests/ folder
  * Run php bin/phpunit

[piotr@piotr-pc Development]$ 
```

## Translation of the Admin Interface

https://docs.sulu.io/en/2.1/book/getting-started.html

```
[piotr@piotr-pc sulu-hello-world]$ bin/console sulu:admin:download-language

                                                                                                                        
 [WARNING] This command will be executed in the "admin" context. For the "website" context, run ./bin/websiteconsole    
                                                                                                                        


Language: en
------------

 ! [NOTE] Download skipped because Sulu includes a translation for the language "en" per default.                       


Language: pl
------------

Starting download for the "sulu/sulu" project in "pl"
Extract ZIP archive...

 ----------- -------------- 
  Package     Translations  
 ----------- -------------- 
  sulu/sulu   454           
 ----------- -------------- 

Writing language pl into translations folder
[piotr@piotr-pc sulu-hello-world]$ 
```

## Setup the Database

https://docs.sulu.io/en/2.1/book/getting-started.html#setup-the-database

```
[piotr@piotr-pc sulu-hello-world]$ ./bin/adminconsole sulu:build dev
Build Targets
=============

+---+--------------------+-----------------------------------------------------------------------+
| # | Builder            | Deps                                                                  |
+---+--------------------+-----------------------------------------------------------------------+
| 0 | database           |                                                                       |
| 1 | phpcr              | database                                                              |
| 2 | phpcr_migrations   | phpcr                                                                 |
| 3 | fixtures           | database, phpcr                                                       |
| 4 | user               | fixtures, database                                                    |
| 5 | system_collections | database, fixtures                                                    |
| 6 | dev                | database, fixtures, phpcr, user, phpcr_migrations, system_collections |
+---+--------------------+-----------------------------------------------------------------------+

Options:

  - nodeps: false
  - destroy: false
  - help: false
  - quiet: false
  - verbose: false
  - version: false
  - ansi: false
  - no-ansi: false
  - no-interaction: false
  - env: 'dev'
  - no-debug: false

Look good? (y)y

Executing builders
==================

Target: database

    doctrine:schema:update  ({"--force":true})
    
        
                 Updating database schema...
        
                     213 queries were executed
        
                                                                                                                                        
         [OK] Database schema updated successfully!                                                                             
                                                                                                                                
        
                
Target: phpcr

    sulu:document:initialize
    
        sulu_document_manager.initializer.workspace
          [+] workspace: "default"
          [+] workspace: "default_live"
        sulu_document_manager.initializer.root_path_purge_initializer
          [ ] Purging workspaces
        sulu_page.document_manager.content_initializer
          content namespaces:
          [+] sulu:http://sulu.io/phpcr
          [+] sec:http://sulu.io/phpcr/sec
          [+] settings:http://sulu.io/phpcr/settings
          [+] i18n:http://sulu.io/phpcr/locale
          content node types:
          [*] sulu:base
          [*] sulu:path
          [*] sulu:content
          [*] sulu:snippet
          [*] sulu:page
          [*] sulu:home
          content namespaces:
          [ ] sulu:http://sulu.io/phpcr
          [ ] sec:http://sulu.io/phpcr/sec
          [ ] settings:http://sulu.io/phpcr/settings
          [ ] i18n:http://sulu.io/phpcr/locale
          content node types:
          [*] sulu:base
          [*] sulu:path
          [*] sulu:content
          [*] sulu:snippet
          [*] sulu:page
          [*] sulu:home
        sulu_core.webspace.document_manager.webspace_initializer
          [+] homepage: [homepage] /cmf/sulu-hello-world/contents (en)
          [+] route: /cmf/sulu-hello-world/routes/en (en)
        sulu_snippet.document.snippet_initializer
          [+] snippet path:: /cmf/snippets 
          [+] snippet path:: /cmf/snippets 
        sulu_custom_urls.initializer
          Sulu Hello World Application:
          [+] items path:: /cmf/sulu-hello-world/custom-urls/items 
          [+] items path:: /cmf/sulu-hello-world/custom-urls/routes 
        
                * Legend: [+] Added [*] Updated [-] Purged [ ] No change
        
Target: phpcr_migrations

Target: fixtures

    doctrine:fixtures:load  ({"--no-interaction":true,"--append":true})
    
        
           > loading App\DataFixtures\AppFixtures
           > loading [2] Sulu\Bundle\ContactBundle\DataFixtures\ORM\LoadDefaultTypes
           > loading [3] Sulu\Bundle\MediaBundle\DataFixtures\ORM\LoadCollectionTypes
           > loading [4] Sulu\Bundle\MediaBundle\DataFixtures\ORM\LoadMediaTypes
           > loading [5] Sulu\Bundle\SecurityBundle\DataFixtures\ORM\LoadSecurityTypes
        
    sulu:document:fixtures:load  ({"--no-interaction":true})
    
        Could not find any fixtures.
        
Target: user

    sulu:security:role:create  ({"name":"User","system":"Sulu"})
    
        Created role "User" in system "Sulu".
        
        Created role "User" in system "Sulu"
    sulu:security:user:create  ({"username":"admin","firstName":"Adam","lastName":"Ministrator","email":"admin@example.com","locale":"en","role":"User","password":"admin"})
    
        Created user "admin" in role "User"
        
        Created user "admin" with password "admin"
Target: system_collections

Target: dev

    Done (40.87s)
[piotr@piotr-pc sulu-hello-world]$ 
```
