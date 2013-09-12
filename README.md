# Sublime Text 2 User Settings

This repository contains my user settings directory for [Sublime Text 2](http://www.sublimetext.com/2).


## Dependencies

The following fonts should be installed on the system:

* [Meslo LG S](https://github.com/andreberg/Meslo-Font)
# [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro)


## Installation

Install [Package Control](http://wbond.net/sublime_packages/package_control) by bringing up the Sublime Text 2 console (``ctrl+` ``) and pasting in the following command:

	import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

The repository must be cloned into the Sublime Text 2 `Packages/User` directory or a symbolic link must be created to this directory.

Sublime Text 2 user directory location on OS X:

	~/Library/Application Support/Sublime Text 2/Packages/User

Sublime Text 2 user directory location on Windows 7:

	C:\Users\USERNAME\AppData\Roaming\Sublime Text 2\Packages\User
