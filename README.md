# Sublime Text 3 - Promela Spin Syntax Highlighting and Build System

### Syntax highlighting for [Promela Spin](http://spinroot.com/spin/whatispin.html) in [Sublime Text 3](http://www.sublimetext.com/3).


## Getting Started

### 1. Installation

While the syntax highlighting should work on any OS with no dependencies, the build system is Windows only, and requires that [jSpin](https://code.google.com/p/jspin/)'s `bin` directory (default: `C:\jspin\bin`) be added to the PATH variable.

Go to `Preferences -> Browse Packages`, and then either download and unzip this plugin into that directory, or:

``` bash
git clone https://github.com/corbanmailloux/sublime-promela-spin.git "sublime-promela-spin"
```

### 2. Activate this Language
**After installing this package**, open an PML file and switch the language to `Promela`, using one
of the following methods:

* Select from the list of supported languages in your status bar at the bottom right corner of your editor
* <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> and search for "Promela"

### 3. Make "Promela" the default
To make `Promela` the default highlighting for the current extension:

1. Open a file with the extension you want to set a default for (i.e. `.pml`)
2. Navigate through the following menus in Sublime Text: `View -> Syntax -> Open all with current extension as... -> Promela`

### 3. Test the Build System
The "Promela - Random" build system should be automatically selected when a Promela file is open. 

To run the build, press <kbd>Ctrl</kbd>+<kbd>B</kbd> or select "Build" from the "Tools" menu.



## Author

**Corban Mailloux**

+ [http://corb.co](http://corb.co)
+ [http://twitter.com/corbco](http://twitter.com/corbco)
+ [http://github.com/corbanmailloux](http://github.com/corbco)


## Copyright and License
Copyright 2014 Corban Mailloux

[MIT License](LICENSE-MIT)
