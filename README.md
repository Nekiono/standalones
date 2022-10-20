# hst.sh

*This contains the hst.sh script, adapted from [diethnis' hastebin standalone sh script](https://github.com/diethnis/standalones).*

## Install

`curl -sfL get.hst.sh | bash`

You need `curl` to install and use hst.

The binary will be saved to ~/.local/bin/hst - make sure it's in your $PATH.

## Usage

See `hst -h`.

Some examples: 

`echo $PWD | hst`

`hst /etc/nginx/sites-enabled/ravy.org`

## Why

Using hastebin shouldn't be a hassle.

This just makes it a one-liner and doesn't require anything apart from bash and curl.
