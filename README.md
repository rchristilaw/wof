Forked from tboronczyk/pendumilo.

# Wheel of Fortune
For a friends' virtual baby shower, decided to do a Baby themed wheel of fortune. After exhausting other options of using powerpoint templates I stumbled across https://github.com/tboronczyk/pendumilo and decided to build off of his great start. My efforts have been to make it more dynamic and remove the need for a hardcoded background image to represent the squares.

  * `/` - advance to the next puzzle
  * spacebar - spin the wheel or dismiss the wheel
  * `\` - reveal all letters (solve the puzzle)
  * `A`...`Z` - select/show a letter

To serve the code locally, install [Docker](https://docker.com) and execute
`docker-composer up`.

Alternatively for development you run `npx http-server` inside the src/ folder.
