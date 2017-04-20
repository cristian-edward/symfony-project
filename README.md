Symfony application
========================
   For install:
   
**1.** composer update<space> \
**2.** npm install \
<space><space><space>**2.1** [**npm install --save-dev gulp**][1] \
<space><space><space>**2.2** npm install gulp-if \
<space><space><space>**2.3** npm install gulp-uglify \
<space><space><space>**2.4** npm install gulp-uglifycss \
<space><space><space>**2.5** npm install gulp-less \
<space><space><space>**2.6** npm install gulp-concat \
<space><space><space>**2.7** npm install gulp-sourcemaps \
<space><space><space>**2.8** create gulp.js \
<space><space><space><space><space><space>**2.8.1** [**configure file gulp.js**][2] \
**3.**

What's inside?
--------------

The Symfony Standard Edition is configured with the following defaults:

  * An AppBundle you can use to start coding;

  * Twig as the only configured template engine;

  * Doctrine ORM/DBAL;

  * Swiftmailer;

  * Annotations enabled for everything.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][6] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][7] - Adds support for the Doctrine ORM

  * [**TwigBundle**][8] - Adds support for the Twig templating engine

  * [**SecurityBundle**][9] - Adds security by integrating Symfony's security
    component

  * [**SwiftmailerBundle**][10] - Adds support for Swiftmailer, a library for
    sending emails

  * [**MonologBundle**][11] - Adds support for Monolog, a logging library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][13] (in dev/test env) - Adds code generation
    capabilities

  * **DebugBundle** (in dev/test env) - Adds Debug and VarDumper component
    integration

All libraries and bundles included in the Symfony Standard Edition are
released under the MIT or BSD license.

Enjoy!

[1]:  http://www.ymc.ch/de/blog/symfony-2-6-step-by-step-best-practice-guide-to-building-a-website-including-bower-bootstrap-jquery-and-gulp/
[2]:  https://github.com/cristian-edward/cofetaria-ioana/blob/master/gulpfile.js
[6]:  https://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/index.html
[7]:  https://symfony.com/doc/3.2/doctrine.html
[8]:  https://symfony.com/doc/3.2/templating.html
[9]:  https://symfony.com/doc/3.2/security.html
[10]: https://symfony.com/doc/3.2/email.html
[11]: https://symfony.com/doc/3.2/logging.html
[12]: https://symfony.com/doc/3.2/assetic/asset_management.html
[13]: https://symfony.com/doc/current/bundles/SensioGeneratorBundle/index.html
