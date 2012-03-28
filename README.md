# frontail – tail -F output in browser

## Introduction

frontail is node.js application for serving `tail -F` output to browser using [socket.io](http://socket.io/).

## Usage

    frontail [options] [file ...]

    Options:

      -h, --help             output usage information
      -V, --version          output the version number
      -p, --port <port>      server port, default 9001
      -n, --number <number>  starting lines number, default 10
