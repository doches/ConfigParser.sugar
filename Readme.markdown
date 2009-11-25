# ConfigParser.sugar

This sugar provides syntax highlighting for configuration files following RFC 822. Among other things, 
it understands both Windows .ini files and config files produced by Python's ConfigParser module. 

## Installation

Clone this project somewhere, with the following:

    git clone git://github.com/doches/configparser.sugar.git ./ConfigParser.sugar

And then link it to your syntaxes directory:

    ln -s "$(pwd)/ConfigParser.sugar" "/Users/$(whoami)/Library/Application Support/Espresso/Sugars/"
