<p align="center">
  <img src="https://user-images.githubusercontent.com/3791941/31036931-072760fe-a534-11e7-8cd7-0565bdc2727c.png" width="100" height="60">

  <h3 align="center">Electron: Start to Finish<br></h3>
</p>

**What This Session is About**

Getting up and running on Electron, a a framework to build cross platform desktop apps with JavaScript, HTML, and CSS. You'll walk away with a fully functional Electron desktop app that you can take apart and customize, along with the knowledge to confidently start building your own Electron apps. This repository houses a series of introductory-to-intermediate exercises to Git familiar with Electron by manipulating and extending a prebuilt weather app.

**Summary**

Built with the [photon](http://photonkit.com) user interface kit.
Uses the [Dark Sky Forecast API](https://developer.forecast.io) as a data source.

**Table of Contents**
- [Prerequisites](#prerequisites)
- [Cheat Sheets](#cheat-sheets)
- [End Product](#end-product)
- [Resources](#extended-resources)

## Prerequisites

- Install Git
- Get familiar with Git commands
- Install a text editor
- Install Node.js

#### Install Git

##### macOS
- Mac users, while you probably already have _a_ version of Git on your system, it may be out-of-date.
- Consider installing the latest stable version of Git with [Homebrew](https://brew.sh)  
  ```sh
  brew install git
  ```
- If you prefer a GUI, try [GitHub Desktop](https://desktop.github.com)

##### Windows
- [GitHub Desktop](https://desktop.github.com) is an easy way to install the Git command line tools on Windows.

##### Linux
- While some Linux distributions come with a version of Git installed, it's often out-of-date. [This guide](https://git-scm.com/download/linux) has recommended commands to install Git with your distribution's preferred package manager.

##### Get familiar with Git commands
You'll want to know how to [fork](https://help.github.com/articles/fork-a-repo/) and [clone](https://help.github.com/articles/cloning-a-repository/) a Git repository, and how to [check out a branch](https://git-scm.com/docs/git-checkout#git-checkout-emgitcheckoutemltbranchgt).

If you need a refresher, consider [exploring our free on-demand training](https://services.github.com/on-demand/).

#### Install a text editor

#### Install Node.js
> **Q:** Why do we need to install Node.js if Electron includes Node.js?
>
> **A:** While Electron does include its own version of Node.js, what we'll install first includes `npm`, the Node Package Manager. NPM is what powers our dependency installation and build processes.

##### macOS
- [Homebrew](https://brew.sh) (recommended) or [installer package](https://nodejs.org/en/download/)
  - [Treehouse has a Homebrew installation guide](http://treehouse.github.io/installation-guides/mac/homebrew.html)
  - …and a [Node.js installation guide](http://treehouse.github.io/installation-guides/mac/node-mac.html)
- Homebrew makes it easier to upgrade Node.js, and doesn't require admin privileges (`sudo`) or manually updating the `$PATH`.

##### Windows
- [Installer package](https://nodejs.org/en/download/)  
  - [Treehouse has a nice step-by-step guide](http://treehouse.github.io/installation-guides/windows/node-windows.html)

##### Linux
- Let's leave this up to users, making the assumption that as Linux users they can figure it out :grin:  
  - [Treehouse recommends](http://treehouse.github.io/installation-guides/linux/node-linux.html) installing via [Linuxbrew](http://linuxbrew.sh)

## Cheat-Sheets
The cheat sheets for each activity are linked here:

- [Exercise 1: Getting Started](cheat-sheets/1-getting-started.md)
- [Exercise 2: Diving In](cheat-sheets/2-diving-in.md)
- [Exercise 3: Electron Defaults](cheat-sheets/3-electron-defaults.md)
- [Exercise 4: Refactoring](cheat-sheets/4-refactoring.md)
- [Exercise 5: Packaging](cheat-sheets/5-packaging.md)
- [Exercise 6: Packaging Extensions](cheat-sheets/6-packaging-extensions.md)
- [Exercise 7: Refresh](cheat-sheets/7-refresh.md)
- [Exercise 8: CYOA](cheat-sheets/8-CYOA.md)

## End Product
At the end of all of our exercises, you should have an app that looks similar to this!
![screenshot](https://cloud.githubusercontent.com/assets/671378/15033544/97011f38-1220-11e6-9611-1571063fe107.png)

## Extended Resources
https://github.com/universeworkshops/electron-weather/issues/1
