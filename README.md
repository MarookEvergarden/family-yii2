Yii 2 Basic Application Template
================================

**NOTE** Yii 2 and the relevant applications and extensions are still under heavy
development. We may make significant changes without prior notices. Please do not
use them for production. Please consider using [Yii v1.1](https://github.com/yiisoft/yii)
if you have a project to be deployed for production soon.


Thank you for using Yii 2 Basic Application Template - an application template
that works out-of-box and can be easily customized to fit for your needs.

Yii 2 Basic Application Template is best suitable for small Websites which mainly contain
a few informational pages.


DIRECTORY STRUCTURE
-------------------

      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      models/             contains model classes
      runtime/            contains files generated during runtime
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      www/                contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by Yii is that your Web server supports PHP 5.3.?.


INSTALLATION
------------

### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may download it from
[http://getcomposer.org/](http://getcomposer.org/) or run the following command on Linux/Unix/MacOS:

~~~
curl -s http://getcomposer.org/installer | php
~~~

You can then install the Bootstrap Application using the following command:

~~~
php composer.phar create-project --stability=dev yiisoft/yii2-app-basic yii-basic
~~~

Now you should be able to access the application using the URL `http://localhost/yii-basic/www/`,
assuming `yii-basic` is directly under the document root of your Web server.


### Install from an Archive File

This is not currently available. We will provide it when Yii 2 is formally released.

# family-yii2
