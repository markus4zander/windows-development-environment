## Setup Windows 10 for Modern Web Development
A fresh Windows isn't entirely ready for modern web development, but all the tools you need are available. A good terminal, popular bash tools, Git, a decent package manager - when properly setup, modern web development on Windows can be a lot of fun.

## Automate it!
All needed Tools and some important Windows settings and features can be installed automatically thanks to the magic of [Boxstarter](http://boxstarter.org/). Simply start PowerShell as Administrator and run:

```powershell
START http://boxstarter.org/package/nr/url?https://raw.githubusercontent.com/markus4zander/windows-development-environment/master/boxstarter
```

#### Node and npm
A bunch of tools are powered by Node and installed via npm. This applies to you even if you don't care about Node development. If you want to install tools for React, Azure, TypeScript, or Cordova, you'll need this.

In the future, you might want to update `npm`. On Windows, just running `npm i -g npm` doesn't always do what it should, so use `npm-windows-upgrade` instead:

```
npm install -g npm-windows-upgrade
npm-windows-upgrade
```
