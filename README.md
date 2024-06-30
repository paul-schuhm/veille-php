# Veille PHP

Un ensemble de ressources, d'outils et d'articles de l'écosystème PHP, mis à jour régulièrement.

- [Veille PHP](#veille-php)
  - [Officiel, Semi-officiel et core members](#officiel-semi-officiel-et-core-members)
  - [Implémentations](#implémentations)
  - [Tooling/Écosystème](#toolingécosystème)
  - [Actualités, recommandations](#actualités-recommandations)
  - [Conférences](#conférences)
  - [Articles](#articles)
  - [Misc](#misc)
  - [Livres](#livres)


## Officiel, Semi-officiel et core members

- [Site web officiel et central de PHP](https://www.php.net/)
- [Sites affiliés à php.net](https://www.php.net/sites.php), tous les sites affiliés au site officiel (bugs, [talks](http://talks.php.net/index.php), etc.)
- [The PHP Foundation](https://thephp.foundation/), groupe de travail sur l'écosystème PHP. [En savoir plus](https://www.youtube.com/watch?v=JBPtPy9iSP0).
- [PHP-FIG](https://www.php-fig.org/), le PHP Framework Interop Group, à l'origine des [PSR](https://www.php-fig.org/psr/)
- [Le blog de Fabien Potencier](http://fabien.potencier.org/)
- [Le blog de Kévin Dunglas](https://dunglas.dev/), membre core de Symfony, mainteneur de FrankenPHP et du [protocole Mercure](https://mercure.rocks/) (entre autres). Un grand développeur et contributeur de l'écosystème PHP notamment, plein d'humilité
- [Afup](https://afup.org/home), association française des utilisateurs de PHP


## Implémentations

- Zend Engine : une implémentation de PHP open source, par [Zend Technologies](https://www.zend.com/);
- [Hip Hop Virtual Machine for PHP (HHVM)](https://en.wikipedia.org/wiki/HHVM) : développé par Méta/Facebook, avec [le langage Hack](https://hacklang.org/), un dialecte PHP fortement typé

## Tooling/Écosystème

- [Composer](https://getcomposer.org/), le gestionnaire de dépendances et de gestion d'autoloading de PHP
- [packagist](https://packagist.org/), dépôt principal des composants PHP  
- [pecl](https://pecl.php.net/), le repertoire officiel des extensions de PHP ([Modernisation de la distribution et maintenance envisagée](https://externals.io/message/121927) par la communauté et initiée par la PHP Foundation et Derick Rethans)
- [phpCodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer/), l'outil puissant pour appliquer des standards de manière semi-automatisé à son code source. Composé de deux programmes: `phpcs` pour détecter les erreurs dans votre code et `phpcbs` pour corriger automatiquement celles qui peuvent l'être
- [phpStan](https://phpstan.org/), l'analyseur statique (*at compile time*) du code PHP par excellence. *Find bugs without writing tests*
- [psalm](https://psalm.dev/), analyseur statique de code, notamment inspiré de Hack
- [PHP Documentor](https://docs.phpdoc.org/), produire de la documentation directement à partir des sources
- [PHP Quality Assurance](https://qa.php.net/)
- [FrankenPHP](https://frankenphp.dev/), un serveur PHP moderne écrit en C et Go, maintenu par Kevin Dunglas, qui permet d'utiliser HTTP 1.1, 2 et 3, et supporte des réponses HTTP multiples. Remplace PHP-FPM
- [phpBench](https://phpbench.readthedocs.io/en/latest/), un framework de benchmark pour PHP, inspiré de PHPUnit
- [PHP Coding Standards Fixer](https://cs.symfony.com/), un outil de qualité de code (linter, fixer) qui analyse et corrige automatiquement les sources au regard des standards définis les règles des PSR. Développé par Fabien Potencier et Dariusz Rumiński
- [GrumPHP](https://github.com/phpro/grumphp), un outil qui se configure sur les git hooks pour tester et valider automatiquement le code commité via un ensemble de règles 
- [Snuffleupagus](https://snuffleupagus.readthedocs.io/), module PHP conçu pour réduire de manière drastique les coûts liés aux attaques de sites web PHP

## Actualités, recommandations

- [php.watch](https://php.watch/), news PHP, articles, changements à venir. Le blog officiel qui suit le développement de PHP
- [phpweekly](https://www.phpweekly.com/), newsletter hebdomadaire sur l'écosystème PHP
- [php.developpez.com](https://php.developpez.com/), actualités, ressources pour apprendre PHP
- [PHP: The Right Way](https://phptherightway.com/) référence accessible aux standards modernes de PHP
- [OWASP : PHP Configuration Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/PHP_Configuration_Cheat_Sheet.html)
- [Paragon Initiative Enterprises Blog : The 2018 Guide to Building Secure PHP Software ](https://paragonie.com/blog/2017/12/2018-guide-building-secure-php-software), le guide de la Paragon Initiative pour livrer des systèmes PHP sécurisés


## Conférences

- [PHP UK Conferences (en)](https://www.youtube.com/c/phpukconference), la chaîne de la conférence éponyme. Toutes les captations des conférences de chaque année sont présentes ici. Pour tous les dev qui veulent se maintenir informés sur PHP et son écosystème
- [AFUP PHP (fr)](https://www.youtube.com/@afupPHP), des tonnes de conférences de la communauté PHP française, beaucoup de conférences vraiment intéressantes et de qualité
- [Functional Programming in PHP](https://youtu.be/LZh4_q04aKo)

## Articles

- [Webperf: Boost Your PHP Apps With 103 Early Hints](https://dunglas.dev/2023/10/webperf-boost-your-php-apps-with-103-early-hints/), de Kévin Dunglas sur l'usage du code status 103 pour améliorer les performences des services web (minimiser la latence perçue)
- [Stop using old-fashioned closures in modern PHP. There are 4* ways to replace them.](https://medium.com/@vlreshet/stop-using-old-fashioned-closures-in-modern-php-there-are-4-ways-to-replace-them-51d8661e2f7e)
- [Elegant immutable object pattern in PHP ](https://dev.to/hbgl/elegant-immutable-object-pattern-in-php-1dg3)
- [PHP Sessions in Depth](https://www.phparch.com/2018/01/php-sessions-in-depth/)
- [Session timeouts in PHP: best practices](https://newbedev.com/session-timeouts-in-php-best-practices)
- [Borrowing Functional Concepts from Clojure in PHP](https://www.codementor.io/@blackwood/borrowing-functional-concepts-from-clojure-in-php-tj19wofx6)
- [Mastering binary and bitwise in PHP](https://thephp.website/en/issue/bitwise-php/)
- [10 Tips and Best Practices To Improve PHP Security](https://www.yeahhub.com/10-tips-best-practices-improve-php-security/)
- [Preventing Duplicate Form Submissions Using Atomic Locks](https://dev.to/daryllegion/preventing-duplicate-form-submissions-using-atomic-locks-42p0)
- [nginx: doing ip geolocation right in nginx ](https://dev.to/gbhorwood/nginx-doing-ip-geolocation-right-in-nginx-442h)
- [Using Models as Flags](https://alsterholm.com/blog/2024/using-models-as-flags), il y a mieux qu'un booléen pour maintenir l'auditabilité d'une donnée (quand, par qui et pourquoi a-t-elle été altérée)

## Misc

- [awesome PHP security](https://github.com/guardrailsio/awesome-php-security), une liste organisée de ressources pour la sécurité des applications PHP 
- [Awesome PHP](https://github.com/ziadoz/awesome-php), une liste organisée de ressources pour PHP (lib, books, podcasts, frameworks...)
- [Clean Code PHP](https://github.com/jupeter/clean-code-php), des principes de clean code appliqués à PHP
- [NativePHP](https://nativephp.com/docs/1/getting-started/introduction), framework PHP pour déployer des applications desktop, maintenu par Marcel Pociot. **Attention, outil toujours en alpha** (2023)
- [PHP Usergroup](https://php.ug/), trouvez des *usergroups* PHP près de chez vous
- [(The only proper) PDO tutorial](https://phpdelusions.net/pdo), un très bon site (maintenu) qui propose des tutoriels pour mieux comprendre le module PDO (la documentation n'est en effet pas toujours complète et explicite sur les différents paramètres du module) et d'autres sujets sur PHP;


## Livres

- *[Modern PHP: new features and good practices](https://www.oreilly.com/library/view/modern-php/9781491905173/)*, Josh Lochart, Edition O'Reilly Media, Inc., 2015. Excellent ouvrage
- *[Professional WordPress: Design and Development](https://www.wiley.com/en-hk/Professional+WordPress:+Design+and+Development,+3rd+Edition-p-9781118987247)*, Brad Williams et David Damstra, Edition Wrox, 3rd Edition, 2015
- *[Professional WordPress Plugin Development](https://www.oreilly.com/library/view/professional-wordpress-plugin/9781119666943/)*, Brad Williams et Justin Taldock, Edition Wrox, 2nd Edition, 2020
- *[Essential PHP Security](https://www.oreilly.com/library/view/essential-php-security/059600656X/)*, Chris Shiflett, O'Reilly Media, Inc., 2005. Excellente introduction à la sécurité des applications en PHP, d'une grande concision. Une bonne référence à garder auprès de soi
- [*PHP in Action : Objects, Design, Agility*](https://www.manning.com/books/php-in-action), Dagfinn Reiersol, Marcus Baker et Chris Shiflett, Manning, 2007 