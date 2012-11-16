This is a starting point for all developers who want to create their own OntoWiki extensions. This includes basic PHP and Zend Skills as well as configuration and setup information for a developers PHP engine.

## Tutorials for PHP Beginners
If you are new to PHP, please have a look at one of these tutorials:
  * http://tut.php-q.net/ (en + de)
  * http://www.w3schools.com/PHP/ (en)
  * http://www.professionelle-softwareentwicklung-mit-php5.de/erste_auflage/index.html (de)

## Tutorials for Zend Beginners
If you know PHP but not Zend, we recommend these tutorial cause it refers to the newest Zend version:  
  * http://framework.zend.com/docs/quickstart

## PHP Configuration for Developers
All you need is to re-configure your OntoWiki Installation to use the **debug mode**. For this, add the following line to your `config.ini`.

    {{{
     debug = on
    }}}

In addition to this, we recommend the php extension [[xdebug|http://www.xdebug.org]] for all OntoWiki developer. **xDebug** provides stack traces and function traces in error messages with:
  * full parameter display for user defined functions
  * function name, file name and line indications
  * support for member functions

We recommend to re-configure some php runtime variables for OntoWiki. Please have a look at [[Deployment-Recommendations]]