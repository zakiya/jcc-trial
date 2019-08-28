# JCC Trial Court install profile. 

# Install
1. `git clone git@github.com:zakiya/jcc-trial.git folder`

1. `cd folder`

2. `composer install`

3. Create localhost and database and add to `settings.php` and/or `settings.local.php` and/or `services.local.yml`

4. `drush si trial`

5. `drush pmu trial_content`

6. `drush en trial_content`

7. Modify `/drush/drush.yml`

8. Add`/web/.htaccess`

# @Todo
- Create example settings.local.php and services.local.php files and scripts.
- Default content doesn't get created on initial install. Need to `drush pmu trial_content` + `drush en trial_content`.
- Handle dev dependencies better.
- Delete composer.lock?
