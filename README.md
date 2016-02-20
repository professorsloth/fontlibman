# fontlibman

Manages user fonts in the `~/.fonts` directory. Fetches fonts from `fontlibrary.org`.

## Installation

    git clone https://github.com/professorsloth/fontlibman.git
    cd fontlibman
    ./fontlibman

You could do a system wide install with something like:

    wget https://raw.githubusercontent.com/professorsloth/fontlibman/master/fontlibman
    chmod a+x fontlibman
    mv fontlibman /usr/local/bin/

## Example usage

Install the font "Fantasque Sans Mono" for your current user:

    fontlibman --install fantasque
    fontlibman --reload

See what fonts are installed:

    fontlibman --list

Remove unwanted font "Fantasque Sans Mono" installed by `fontlibman`:

    fontlibman --remove fantasque

