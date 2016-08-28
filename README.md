# reneps
Bash script for renaming multiple episodes of a show without hassle. Place in folder currently in your $PATH (ex. /usr/local/bin) to allow execution without './' and without needing to place the script in each folder where you want to rename episodes.

## Usage
```
$ ./reneps -h
Usage: ./reneps [options]

Renames all files in the current folder to match specified naming conventions for osmc.

EXAMPLE:
    ./reneps -n "Best Show Ever"

OPTIONS:
   -h           Show this help message
   -n           Specify the name of the show, defaults to parent folder name.
   -s           Specify the season of the show, defaults to 1
   -e           Specify the episode number to start the count with,
                defaults to 1
   --dry-run    Dry run shows which files will be renamed and to what,
                without renaming any of them
```
