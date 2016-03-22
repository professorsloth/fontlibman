# fontlibman
![fontlibman](http://serene.springtime.space/content/fontlibman.jpg)

Manages user fonts in the `~/.fonts` directory. Fetches fonts from `fontlibrary.org`, `github.com`.

## Installation

    git clone https://github.com/professorsloth/fontlibman.git
    cd fontlibman
    ./fontlibman

## Example usage

Install the font "Fantasque Sans Mono" for your current user:

    fontlibman --install fantasque
    fontlibman --reload

See what fonts are installed:

    fontlibman --list

Delete unwanted font "Fantasque Sans Mono" installed by `fontlibman`:

    fontlibman --delete fantasque

