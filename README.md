![](images/excalidraw_shawshank_redemption.jpg)

# StaticBoard

I wanted an Excalidraw-style whiteboard that I could use on machines where I could not install software or paste sensitive information into an online service.

Running Excalidraw locally is possible, but it still requires some setup. I wanted something simpler: one HTML file that I could open in a browser and use offline.

That became StaticBoard.

**[Try it live](https://dwdas9.github.io/staticboard/)**

## Run it

For fully offline use:

1. Download `index.html`.
2. Open it in your browser.

There is nothing to install and no server to start.

## Features

![](images/Whiteboard_Annotated.jpg)

StaticBoard includes the drawing tools I use most often:

* Shapes, arrows, text, and freehand drawing
* Images and screenshots
* Undo and redo
* Zoom and canvas navigation
* PNG and SVG export
* Editable Excalidraw file support
* Local saving in the browser

It also has a few additions for working with screenshots and annotations:

* Paste screenshots directly onto the board
* A set of hand-drawn brushes including ink pen, fountain pen, pencil, marker, highlighter, and crayon, each colourable using Excalidraw's own colour picker
* A soft drop shadow for images, rectangles, ellipses, diamonds, and text, with controls for blur, distance, and opacity
* A broad, hand-drawn Snagit-style annotation arrow, separate from the regular Excalidraw arrow
* A hand-drawn callout or speech bubble with editable text and a pointer tip you can drag in any direction
* Draw arrows from inside an image to the surrounding canvas

## What is not included

StaticBoard does not have:

* User accounts
* Real-time collaboration
* Cloud storage
* Team administration
* Backend services

## How it fits into one file

StaticBoard is built with React and uses Excalidraw as its drawing engine.

A normal web application keeps its JavaScript, CSS, and other files separately. StaticBoard bundles its application code and styling into `index.html`, allowing the browser to run it directly from that file.

Images are processed in the browser, and the current board is saved locally. StaticBoard does not send your drawings to its own server.

## Credits

StaticBoard uses the open-source [Excalidraw](https://github.com/excalidraw/excalidraw) editor.

## Project status

StaticBoard is still being improved.
