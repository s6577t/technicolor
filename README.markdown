# Technicolor

Use node to remind you of Teletext.

## Install

    npm install technicolor

## Use

    var technicolor = require('technicolor');

    var message = "Hello, Darling."
    var prettyMessage = technicolor(message, {
      color           : 'red',
      backgroundColor : 'white',
      bold            : true,
      underline       : true
    });

    console.info(prettyMessage);

## Possibilities

    var technicolor = require('technicolor');
    technicolor.showAll();

## Supported Colours

* black
* red
* green
* yellow
* blue
* purple
* cyan
* darkGrey
* lightGrey
* brightRed
* brightGreen
* brightYellow
* brightBlue
* brightPurple
* brightCyan
* white