# Overview

This tool reads a resin raspberry pi image from a file and prints the network configuration to stdout, or reads a network configuration from stdin and writes it in the image.

# Usage

1. Download an image from your dashboard 
2. Run `./resin-net-config get resin-foobar.img > foobar.config`
3. Modify `foobar.config` according to your needs as per the connman config format - More information -> http://docs.resin.io/#/pages/configuration/custom-network.md
4. After you're done run `cat foobar.config | ./resin-net-config set resin-foobar.img`
