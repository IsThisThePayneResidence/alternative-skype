alternative-skype
==============
A sophisticated original Linux Skype client substitute made with [Electron runtime](http://electron.atom.io)

##Special thanks

- Shout-out to my man [szwacz](https://github.com/szwacz) and his [electron-boilerplate](https://github.com/szwacz/electron-boilerplate) project. Keep it up, homie. Your stuff is great.

## Install

### Building from source

This is basically altered info from the [electron-boilerplate](https://github.com/szwacz/electron-boilerplate) building from source guide.

```
git clone https://github.com/IsThisThePayneResidence/alternative-skype.git
cd alternative-skype
npm install
npm start
```
... and boom! You have running desktop application on your screen.

#### Windows only

###### Installer

The installer is built using [NSIS](http://nsis.sourceforge.net). You have to install NSIS version 3.0, and add its folder to PATH in Environment Variables, so it is reachable to scripts in this project. For example, `C:\Program Files (x86)\NSIS`.

###### 32-bit build on 64-bit Windows

There are still a lot of 32-bit Windows installations in use. If you want to support those systems and have 64-bit OS make sure you've installed 32-bit (instead of 64-bit) Node version. There are [versions managers](https://github.com/coreybutler/nvm-windows) if you feel the need for both architectures on the same machine.

### Binaries

You can download .deb package for
[Debian, Ubuntu, Mint, etc.](https://www.dropbox.com/s/3i8jcyx07i4zkir/alternative-skype-v0.0.1-linux-x64.deb?dl=0)

Or try this poorly written bash script
```
$ sudo wget -O.- https://www.dropbox.com/s/3i8jcyx07i4zkir/alternative-skype-v0.0.1-linux-x64.deb && sudo dpkg --install .-

```

## Known issues

- Skype calls don't work
- This is basically [web.skype.com](https://web.skype.com) in separate window

## In case you didn't notice

This is a joke
