# 🛳️ Onboarding
Tips, tricks and requirements for setting up your development environment

> Onboarding for software teams is the process of getting new developers setup to be able to work in our codebase. For this bootcamp we're assuming that we have a Macintosh workstation with no previous configuration or coding related software. I will describe a list of configuration options and software tools here, and note whether they are required or optional.

## macOS Settings 
### Dock ️️
☑️  Automatically hide and show the Dock 
>More often than not, I use Spotlight (⌘ Space) or the terminal to launch applications instead of the dock — it’s hard to justify dedicating such display real estate to it. Besides, you can easily access it by moving your mouse to the bottom of the screen or by pressing ⌃ F3. 
### Finder Preferences Preferences > Advanced > 
 ☑️  Show all filename extensions 
### View options 
- View > Show Path Bar
- View > Show Status Bar 
### Show hidden files 
Type `defaults write com.apple.Finder AppleShowAllFiles true` in the terminal.

## macOS Shortcuts
> These are the mac shortcuts I use the most (I won’t list the very basic ones like ⌘ C, ⌘ V, ⌘ Tab, etc.).

### System wide
- Spotlight search: **⌘ Space**   
- Character Viewer: **⌃⌘ Space** (Quickly find emojis and special characters)
- Force quit an app: **⌥⌘ Esc**  
- Lock screen: **⌃⌘ Q ** 
- Show or hide the Dock: **⌃ F3** or **⌥⌘ D**  
- Show all windows: **⌃ Arrow-Up**  
- Show all windows of the front app: **⌃ Arrow-Down**  
- Forward delete: **fn delete**
- Paste without formatting: **⇧⌘ V**

### Screenshot
- Open Screenshot app: **⇧⌘ 5**
- Save screenshot of the screen: **⇧⌘ 3**
- Save screenshot of a portion of screen: **⇧⌘ 4**
- Save screenshot of a window: **⇧⌘ 4 + Space**
- Copy screenshot of the screen: **⇧⌃⌘ 3**
- Copy screenshot of a portion of screen: **⇧⌃⌘ 4**
- Copy screenshot of a window: **⇧⌃⌘ 4 + Space**

### Finder
- Open the home folder: **⇧⌘ H**
- Open the desktop folder. **⇧⌘ D**
- Open the parent folder: **⌘ Arrow-Up**
- Go to the previous folder: **⌘ [**
- Go to the next folder: **⌘ ]**
- Show or hide hidden files: **⇧⌘ .**


## Command-line Tools
> Before you start, open `Terminal` application and install **Xcode command-line tool**. This step is required, it installs most of the compilers and languages you'll need to be able to develop software.

```shell
xcode-select --install
```

### HomeBrew
> This is the package manager. It allows you to install, uninstall, and update command-line tools and Mac applications.
> To install it, open the terminal, and run this command:
```shell
curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh"
```

### Oh My Zsh
> Oh My Zsh is a community-driven framework for managing your Zsh configuration. It provides hundreds of plugins and themes and makes configuring Zsh a breeze.
> To install Oh My Zsh, run:
```shell
curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh"
```

## Package Installs
> Some language utlities provide installable packages that may be installed similar to any downloaded application.

### Node.js / NPM
> Node.js is a javascript engine that runs on any general purpose computer rather than only in the browser. This is necessary for any frontend projects, and can be used to build a backend as well.
- Visit https://nodejs.org/en/ and download & install the latest version.

## Required Software
> Some applications are necessary in order to write software and interact with github, there are many options for which applications you can choose, but we've selected some industry standards here that we can standardize on so we can be on the same page when working on bootcamp projects. You may choose other options according to your preference once you are able to make those choices.

### Visual Studio Code
> The best IDE/editor for web development at the moment (in my opinion). It’s fast with tons of extensions, and it’s open-source. 
- https://code.visualstudio.com/download

### Github Desktop
> This is a graphical user interface for github, and it allows us to not spend too much time learning git and still be able to use version control effectively.
- https://desktop.github.com/

### Docker Desktop
> This is a container orchestration platform. You can think of it as an instant server that you can run & deploy to locally greatly simplifying deployment of the applications that you develop. (more about this later)
- https://www.docker.com/products/docker-desktop  

## 🎉🎉 That's it Congratulations! You're ready to start Coding Bootcamp 🎉🎉
