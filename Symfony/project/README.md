# Symfony Full course

1. Install project 
```
$ composer create-project symfony/skeleton sfcourse (we'll be download last version of symfony)
```

2. Install specific version of symfony
```
$ composer create-project symfony/skeleton:"^5.4" my_project_directory 
$ composer create-project symfony/skeleton:"^4.4" project
$ composer create-project symfony/skeleton:"^4.2" project
```

3. Install server bundle or run local server
```
$ composer require server --dev
$ php -S 127.0.0.1:8000 -t public
```

4. Install symfony requirements checker
```
$ composer require symfony/requirements-checker
Tap in address: http://localhost:8000/check.php

Remove package
$ composer remove symfony/requirements-checker
```

5. Install Twig
```
$ composer require twig
```

6. List all commands
```
$ bin/console
```

