# PHP CLI

Quick scripts to use PHP CLI with docker, useful for PHP development on macOS

## Setup

These instructions assume the Docker is already installed.

Download the repository

```shell
cd ~
git clone git@github.com:haukurh/.php.git
```

don't forget to add `~/.php` to path

## Serve command

There is a `serve` script which spins up a PHP development server.

Possible flags:

- `-t` <docroot>	Specify document root <docroot> for built-in web server. (default working directory)
- `-p` port			Port which server runs on (default 8000)
- `-v` PHP version	PHP version which the server run on. (default 8.1)

```shell
server -v 8.1 -p 8001 -t pub
```
