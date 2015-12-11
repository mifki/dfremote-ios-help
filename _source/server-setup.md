---
layout: kb
title: Server Setup
---

You need to have DFHack 0.40.24-r3 installed. You can get the package for your platform from `lazynewbpack.com`.

* Download `dfremote-updater` package from `mifki.com/df/setup` and follow instructions in README file.

* If that didn't work, download `dfremote` package and follow instructions in README file.
    
* Type `remote on` in the DFHack console to activate Remote (`remote off` to deactivate). You then should be able to connect from local network using IP address or hostname of your computer.
    
* If you want to access your server over Internet and do not have a public IP address, type <code>remote publish <i>name</i></code>, and specify this name in the Published Name field when adding a server. Currently names are not checked for uniqueness, so think of something non-trivial.

* You should protect your server with a password, especially if you're publishing it for external access. To do this, use `remote pwd` command.