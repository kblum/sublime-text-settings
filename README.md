# Sublime Text 3 User Settings

This repository contains my user settings directory for [Sublime Text](https://www.sublimetext.com).


## Installation

Reference:

- [Package Control - Syncing](https://packagecontrol.io/docs/syncing)

Download the [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) font and install the OpenType version.

Install [Package Control](https://packagecontrol.io) by following the [installation instructions](https://packagecontrol.io/installation).

This repository must be cloned into the Sublime Text 3 `Packages/User` directory or a symbolic link must be created to this directory.

Sublime Text 3 user directory location on OS X:

	~/Library/Application Support/Sublime Text 3/Packages/User

Sublime Text 3 user directory location on Ubuntu:

	~/.config/sublime-text-3/Packages/User

Sublime Text 3 user directory location on Windows 7:

	C:\Users\USERNAME\AppData\Roaming\Sublime Text 3\Packages\User

or

	%AppData%\Sublime Text 3\Packages\User

Missing packages will be downloaded the next time that the application is launched, during which time the styling will be broken.


## Additional Setup Options

Create a symbolic link to `subl` so that Sublime Text 3 can be launched from the command line on OS X:

    ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
