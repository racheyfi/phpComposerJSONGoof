# example-php-composer
Example PHP repository containing fake data with vulnerable dependencies

There is at least one vulnerability to be reported:

* ZF2015-07: Filesystem Permissions Issues in Multiple Components (CVE-2015-5723, https://framework.zend.com/security/advisory/ZF2015-07)

Composer should know about this:

    $ composer install
    [...]
    $ composer outdated
    zendframework/zendframework 2.4.7 3.0.0 Zend Framework 2
