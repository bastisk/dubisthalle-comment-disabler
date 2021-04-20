# DuBistHalle comment disabler

A chrome extension to hide the entire comment section on DuBistHalle.de to get you away from the stupid comments and really focus on the content you are reading.
The extension currently has no "on/off" button, just install it and it will inject the script into every DuBistHalle.de page.

## Features

- on DuBistHalle.de pages: checks every 2 seconds for the `comments` element to appear and tries to hide it. This is because DuBistHalle.de sometimes takes a few moments to load the element. If the script is only checking this once at the beginning, the comment section does not always disappear.

**If you got a better way to do it, please create a PR!**
