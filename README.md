# soundcloud2000

The next generation SoundCloud client. Without all these stupid CSS files. Runs on OSX and Linux.

![Screen Shot 2013-01-20 at 15 37 03](https://f.cloud.github.com/assets/3432/81282/06c44c7e-630f-11e2-9a91-85c9b917835c.png)
![Screen Shot 2013-01-20 at 15 37 54](https://f.cloud.github.com/assets/3432/81281/06b05df4-630f-11e2-8b55-7f3c18126831.png)

This hack was built at the [Music Hack Day Stockholm 2013](http://stockholm.musichackday.org/2013).

## Requirements

  * Ruby (1.9)
  * Portaudio (19)
  * Mpg123 (1.14)

## Installation

Assuming you have Ruby/Rubygems installed, you need portaudio and mpg123 as
library to compile the native extensions.

### OSX

    brew install portaudio
    brew install mpg123
    gem install soundcloud2000

### Debian / Ubuntu

    apt-get install portaudio19-dev libmpg123-dev libncurses-dev ruby1.9.1-dev
    gem install soundcloud2000

## Usage

  In order to use soundcloud2000, you need to [acquire a client credential for your application](http://soundcloud.com/you/apps/new). soundcloud2000 expects a valid client id to be set in the SC_CLIENT_ID environment variable.

  You can either set this up in your `.bashrc` or equivalent or you can specify it on the command line:

    SC_CLIENT_ID=YOUR_CLIENT_ID soundcloud2000

## Features

  * stream SoundCloud tracks in your terminal (`enter`)
  * scroll through sound lists (`down` / `up`)
  * play / pause support (`space`)
  * forward / rewind support (`right` / `left`)
  * play tracks of different users (`u`)
  * play favorites from a user (`f`)
  * play sets/playlists from a user  (`s`)
  * level meter

## Planned

  * play any streams, sets or sounds
  * better browsing between users and sound lists

## Authors

  * [Matthias Georgi](https://github.com/georgi) ([@mgeorgi](https://twitter.com/mgeorgi))
  * [Tobias Schmidt](https://github.com/grobie) ([@dagrobie](https://twitter.com/dagrobie))

## Contributors

 *  [Travis Thieman](https://github.com/tthieman) ([@tthieman](https://twitter.com/thieman))
 *  [Sean Lewis](https://github.com/sophisticasean) ([@FricSean](https://twitter.com/fricsean))
