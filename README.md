# hst.sh

## Install

`curl -sfL get.hst.sh | bash`

You need `curl` to install and use hst. If you don't have it, the install usually looks like `apt install curl -y`, `pacman -S curl`, or similar. The binary will be saved to /usr/bin/hst - make sure you have the sufficient access permissions.

## Usage

See `hst -h`.

Some examples: 

`echo $PWD | hst`

`hst /etc/nginx/sites-enabled/ravy.pink.conf`

## Why

I found all other haste clients too hard to install or requiring too many dependencies (especially the official one).

This just makes it a one-liner and doesn't require anything apart from bash, inbuilt commands, and curl.

## Credit where it's due

This contains the hst.sh script, adapted from [diethnis' hastebin standalone sh script](https://github.com/diethnis/standalones).

The original is licensed under The Unlicense.
