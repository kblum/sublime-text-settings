# Sublime Text 3 User Settings

This repository contains my user settings directory for [Sublime Text 3](http://www.sublimetext.com/3).


## Installation

Install [Package Control](https://sublime.wbond.net/) by following the [installation instructions](https://sublime.wbond.net/installation).

This repository must be cloned into the Sublime Text 3 `Packages/User` directory or a symbolic link must be created to this directory.

Sublime Text 3 user directory location on OS X:

	~/Library/Application Support/Sublime Text 3/Packages/User

Sublime Text 3 user directory location on Windows 7:

	C:\Users\USERNAME\AppData\Roaming\Sublime Text 3\Packages\User

Missing packages will be downloaded the next time that the application is launched, during which time the styling will be broken.


## Additional Setup Options

Create a symbolic link to `subl` so that Sublime Text 3 can be launched from the command line on OS X:

    ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
