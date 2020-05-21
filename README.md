# Wiki Theme for OctoberCMS

**Background**  
A simple October theme for simple, flat-file informational websites.

**Features**  
- Provides a simple theme
- Content managed by adding directories and markdown files to the theme's `content` directory

**Install**  
There are two options:
- `git clone https://github.com/albrightlabs/wiki-theme.git themes/wiki` and run `php artisan october:up` or
- `git submodule add -b master https://github.com/albrightlabs/wiki-theme.git themes/wiki` and run `php artisan october:up`

**Update**  
- `git pull origin master` or
- `git pull --recursive-submodules`

**Usage**  
1. Install theme, activate via administration area settings or file based configuration.
2. Add directories to `content` directories--this is intended to be used as wiki categories.
3. Add markdown files either directly to the `content` directory or any of the directories inside.
*Note: directory support in the theme's content directory is limited to a single depth.*

**Contribute**  
Feel free to fork and contribute to this plugin! Please email support@albrightlabs.com with any and all questions.
