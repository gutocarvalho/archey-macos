# Archey for MacOS

An archey script for MacOS forked from obihann/archey-osx.

```sh

❯ ./archey -l

                 ###               User: gutocarvalho
               ####                Hostname: teletraan
               ###                 Distro: macOS 11.5
       #######    #######          Kernel: Darwin
     ######################        Uptime:  9 days, 12:42
    #####################          Load:  1.68 2.88 3.81
    ####################           Shell: /bin/zsh
    ####################           Terminal: xterm-256color iTerm.app
    #####################          CPU: Intel Core i5-5287U CPU @ 2.90GHz
     ######################        Logical Cores:  4
      ####################         Memory: 16 GB
        ################           Disk: 36%
         ####     #####            Battery: 99.98%
                                   Battery Cycles:  2
                                   Public IPv4: 186.195.34.120
                                   Local IPv4: 192.168.68.152
```

## Table Of Contents

* [Options](#options)
* [Credits](#credits)
* [License](#license)

## Options

* -b,  --nocolor : Use black & white logo
* -c,  --color   : Force using a color Logo
* -p   --packager  Use auto detected package system (default packager: homebrew)
* -m,  --macports : Use MacPorts instead of Homebrew to display package count
* -o   --offline : Disable the IP address check
* -l   --localip : Show the local IP address associated with the default adapter
* -h,  --help : Show help

## Credits

* [obihann](https://github.com/obihann/archey-osx) - Archey OSX
* [djmelik](https://github.com/djmelik/archey) - Archey
* [joshfinnie](https://github.com/joshfinnie/archey-osx) - A great OSX Python port of Archey
* [Gary00](https://github.com/Gary00/archey-osx) - A fork of joshfinnie's Archey port, and the base of this script.
* [rdlugosz](https://github.com/rdlugosz) - Fixing a math error with memory caculations.
* [docwhat](https://github.com/docwhat) - Shell expertise and cleanups.
* [slice27](https://github.com/slice27) - Shell wizardy allowing dynamic fields
* [vladshub](https://github.com/vladshub) - Custom logo support

## License

This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Author [Guto Carvalho](http://gutocarvalho.net) 2021
