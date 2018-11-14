# Tidy-up

Terminus Plugin to clean up Pantheon site repository of files which could present issues. Tidy-up command is for sites hosted on [Pantheon](https://www.pantheon.io) 

Adds a command 'tidyup' to Terminus which you can use just like 'drush' or 'wp'.  The results from the tidyup command
are automatically committed to your git repo.

Note that you can only run tidyup on dev or multidev environments as tidyup will almost always need to write to the 
filesystem.

## Examples
* `terminus tidyup --site=my-site --env=dev --gitfiles`


## Installation
For help installing, see [Terminus's Wiki](https://github.com/pantheon-systems/terminus/wiki/Plugins)

## Help
Run `terminus help tidyup` for help.
