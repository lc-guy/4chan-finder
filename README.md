4chan-finder
======
**4chan-finder** is a ruby script for searching threads on 4chan from your terminal.

```
Usage: ./4chan-finder [options] <search term>
    -v, --verbose                    Run verbosely
    -b, --board [BOARD NAME]         Board to search
    -d, --dump-mode                  Run in dump mode (dumps the result links directly for easy piping)
    -l, --limit [NUMBER]             Number of results limit
    -U, --update-cache               Update boards list cache
    -h, --help                       Display this screen
```

## TODO
* ~~Make it work~~
* ~~Implement dump mode (easy)~~
* ~~Make it look better~~
* ~~Make it interactive (Display a small snippet of the OP, the last reply date, and allow the user to choose the thread he wants to access if multiple results are present)~~

This is now in a working state. Future changes will probably only be bugfixes or feature requests.

## Dependencies 
* Ruby Versions older than 1.9.3 are not supported (releases older than 2011).
* The xdg gem is necessary for handling config and cache folders location. To install it, enter `[sudo] gem install xdg`.
* The colorize gem is necessary for output generation. To install it, enter `[sudo] gem install colorize`.
* The nokogiri gem is necessary for cleaning the 4chan api's output. To install it, enter `[sudo] gem install nokogiri`.

## Contact
* e-mail: aptyget@gmail.com
* IRC: apt-get on SynIRC and Rizon