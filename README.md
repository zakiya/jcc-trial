# JCC Trial Court install profile. 

# Install
`git clone`
`composer install`
`drush si trial`
`drush pmu trial_content`
`drush en trial_content`

# @Todo
- Create example settings.local.php and services.local.php files.
- Default content doesn't get created on initial install. Need to `drush pmu trial_content` + `drush en trial_content`
