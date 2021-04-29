# Version 3.0.0

## Features

* Fixed composer conflicts for phpdocumentor/phpdocumentor dependency

## Bugfixes

* None

# Version 2.0.0

## Features

* Remove phpdocumentor/phpdocumentor dependency + ant phpdoc target because of composer conflicts

## Bugfixes

* None

# Version 1.0.5

## Features

* Switch to PHPUnit 4.8.*
* Add libraries for a Robo.li build environment

## Bugfixes

* None

# Version 1.0.4

## Features

* Switch to PHPDocumentor version ~2.9

## Bugfixes

* None

# Version 1.0.3

## Features

* Make PHPLint target configurable

## Bugfixes

* None

# Version 1.0.2

## Features

* Added target for CodeClimate test reporting

## Bugfixes

* None

# Version 1.0.1

## Features

* Switch to latest version 2.2.* of squizlabs/php_codesniffer

## Bugfixes

* None

# Version 1.0.0

## Features

* Made final

## Bugfixes

* None

# Version 0.2.1

## Features

* None

## Bugfixes

* Removed "PEAR.Commenting.FileComment" and "PEAR.Commenting.ClassComment" PHPCS sniff as we do not longer maintain all of their aspects

# Version 0.2.0

## Features

* Switch to latest versions of phpdocumentor/phpdocumentor, squizlabs/php_codesniffer, phpunit/phpunit

## Bugfixes

* None

# Version 0.1.22

## Features

* Change order of default build target to optimize speed

## Bugfixes

* None

# Version 0.1.21

## Features

* Add default build properties for Windows environment (common.win.properties)
* Switch from target depends attribute to antcall to make build more generic

## Bugfixes

* None

# Version 0.1.20

## Features

* Switch latest phpmd version

## Bugfixes

* None

# Version 0.1.19

## Features

* Allowed for optional additional arguments when using the phpcs target

## Bugfixes

* None

## Bugfixes

* None

# Version 0.1.17

## Features

* Switch default deploy dir to instance.dir instead of instance.dir/app/code

## Bugfixes

* None

# Version 0.1.16

## Features

* Add ANT phplint target to run a syntax check on PHP source folder

## Bugfixes

* None

# Version 0.1.15

## Features

* None

## Bugfixes

* Switch to phpcs --report-full instead of --report-summary and ignore warnings

# Version 0.1.14

## Features

* Activate commandline output for phpcs target

## Bugfixes

* None

# Version 0.1.13

## Features

* None

## Bugfixes

* Bugfix invalid initialization of phpcpd-additional.args in common.default.properties file

# Version 0.1.12

## Features

* Make PHPDocumentor target dir configurable with phpdoc-target.dir
* Optimize phpcpd-exclude.dir by add new phpcpd-additional.args initialized with phpcpd-exclude.dir instead

## Bugfixes

* None

# Version 0.1.11

## Features

* Remove composer-install target as dependency from run-test target

## Bugfixes

* None

# Version 0.1.10

## Features

* None

## Bugfixes

* Bugfix missing = for phpcpd-exclude.dir in commong.default.properties

# Version 0.1.9

## Features

* Make exclude directories for tools configurable

## Bugfixes

* None

# Version 0.1.8

## Features

* Make source directory, to be parsed by tools, configurable

## Bugfixes

* None

# Version 0.1.7

## Features

* Ignore composer vendor directory when running tools

## Bugfixes

* None

# Version 0.1.6

## Features

* Switch to composer version of phploc, phpmd, phpcs, phpcpd, phpdocumentor

## Bugfixes

* None

# Version 0.1.5

## Features

* Rename os.family property from unix to linux (also default)

## Bugfixes

* None

# Version 0.1.4

## Features

* Add new properties for var/tmp, deploy + webapps directories

## Bugfixes

* None

# Version 0.1.3

## Features

* None

## Bugfixes

* Set correct deploy.dir in common.mac.properties
* Remove static app/code from deploy.dir in deploy target in common.xml

# Version 0.1.2

## Features

* Allow coding standard definition by build property coding.standard

## Bugfixes

* None

# Version 0.1.1

## Bugfixes

* Add basedir + bootstrap when calling phpunit
* Remove release.version property from common.default.properties

## Features

* None

# Version 0.1.0

## Bugfixes

* None

## Features

* Initial Release
