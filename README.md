

This is the sample config of .ebextensions to setup an Elastic Beanstalk PHP 5.4 container using Nginx and PHP-FPM


Using the non-legacy containers allows you to use Nginx (or any other services that you would like to) without the need of building a customised AMI.

Tested on ami-1624987f, PHP 5.4 default. Could work with others.


Many thanks to https://github.com/carboncoders/elasticbeanstalk-nginx-php for the base config of Nginx and PHP-FPM





