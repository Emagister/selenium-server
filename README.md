Selenium server standalone
===============

This repository allows you to have the latest stable version of Selenium server integrated into your projects.
Selenium server standalone is a browser automation framework. 

Instructions:
-------------

1. Add the following line to your composer.json configuration file: ```"tilibom/selenium-server": "3.*"```. It should look like this:
```json
{
        "config": {
            "bin-dir": "bin/"
        },
        "minimum-stability": "stable",
        "require": {
            "tilibom/selenium-server": "3.*"
        }
}
```

2. Execute the following command in the home directory of your project: ```php composer.phar install```

3. And you're ready to go! Now you can launch the selenium server from the corresponding directory (in this case "bin"): ```java -jar bin/selenium-server.jar```


