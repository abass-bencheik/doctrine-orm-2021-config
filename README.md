# doctrine-orm-2021-config
It's about solving the following issue.  Fatal error: Uncaught RuntimeException: Setup tool cannot configure caches without doctrine/cache 1.11 or symfony/cache.
Learn more on the [official website](https://www.doctrine-project.org/projects/doctrine-orm/en/current/tutorials/getting-started.html)

# Test
✔️ ```composer install ```

✔️ ``` vendor/bin/doctrine orm:schema-tool:create ```

✔️ ``` vendor/bin/doctrine orm:schema-tool:update --force ```
