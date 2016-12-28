# Test-the-REST

This repository contains the example code used the tutorial [Using Guzzle and PHPUnit for REST API Testing](https://blog.cloudflare.com/using-guzzle-and-phpunit-for-rest-api-testing/)
on the Cloudflare Blog.

## How do I run this?

If you want to use this yourself, simply ensure you have [Composer](https://getcomposer.org/)
installed on your system. Once you have cloned the repository you can then run ````composer install````
to pull the depdendencies (Guzzle and PHPUnit) into the ````vendor```` directory.

Should you wish to run the tests, you can simply use ````composer test````, and the tests in the ````tests````
directory will run.