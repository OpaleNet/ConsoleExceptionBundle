[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/OpaleNet/ConsoleExceptionBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/OpaleNet/ConsoleExceptionBundle/?branch=master)

# ConsoleExceptionBundle

Deprecation notice: Please note that since Symfony 3.3 this is not needed anymore http://symfony.com/doc/current/console/logging.html

Symfony console exception logger bundle is a simple implementation of http://symfony.com/doc/current/cookbook/console/logging.html

##Usage
Just register the bundle in your AppKernel.php

```php

$bundles = array(
    //...
    new Opale\ConsoleExceptionBundle\OpaleConsoleExceptionBundle(),
);
```


