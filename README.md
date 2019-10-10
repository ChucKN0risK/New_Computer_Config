# New_Computer_Config
List of things to do with a new computer

#### Get LastPass + AppStore passwords + (BetterTouchTool license & backup + Tower license + Sketch license)

#### Things to install:
- Install [Homebrew](http://brew.sh/)
	- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install Oh My Zsh
	_ `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
- Install tools
	- `brew install git`
	- `brew install node`
	- `brew install zsh`
	- [htop](https://hisham.hm/htop/) `brew install htop`
	- [Yarn](https://yarnpkg.com/en/) `brew install yarn`
	- [youtube-dl](https://rg3.github.io/youtube-dl/) `brew install youtube-dl`
	- [Mac App Store command line interface](https://github.com/mas-cli/mas) `brew install mas`
	- [Homebrew Cask](https://caskroom.github.io/) `brew tap cask/cask`
- Install [QuickLook Plugins](https://github.com/sindresorhus/quick-look-plugins)
	- `brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json betterzip qlimagesize webpquicklook qlvideo`
- [Install main softs](https://caskroom.github.io/search)
	- `brew cask install google-chrome cakebrew slack firefox skype mamp sketch sublime-text visual-studio-code iterm2 flux bettertouchtool tower transmit zeplin postman soulseek mediahuman-audio-converter appcleaner android-file-transfer vlc srware-iron webtorrent fontplop evernote sequel-pro figma docker airtable notion datagrip`
- Log In Mac App Store
	- `mas signin mas@example.com "password"`
- Install Mac App Store Softs (Sip, Pages, iA Writer, The Unarchiver, Paste 2)
	- `mas install 507257563 409201541 775737590 425424353 967805235`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)
- [Meta](https://www.nightbirdsevolve.com/meta/updates/latest/)
- [Loom](https://www.loom.com/desktop)
- [EasySubs](https://tucci.me/projects/easysubs/)
- [Tempo](https://www.yourtempo.co/)
- [svgo-gui](http://goo.gl/0Qu9B)

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade "brew outdated"`

#### Update app autolaunch during system startup
- add BetterTouchTool, Flux, Mega at startup

#### Set VisualStudio Code $PATH
- As explained [here](https://stackoverflow.com/a/29971430/3906770):
After installation, launch VS Code. Now open the Command Palette (F1 or ⇧⌘P on Mac) and type shell command to find the Shell Command: Install 'code' command in PATH command.

#### Install Sublime Text config
1) Install Package Manager and Open iTerm  
2) `cd /Users/louischenais/Library/Application\ Support/Sublime\ Text\ 3`  
3) `git init`  
4) `git remote add origin https://github.com/ChucKN0risK/st3-settings.git`  
5) `git fetch`  
6) `git checkout -t origin/master`  
7) Paste [these settings](https://gist.github.com/ChucKN0risK/1271219c30777d6f31d1)  
8) Create a `.bash_profile` in Username folder containing this [gist](https://gist.github.com/ChucKN0risK/f3052d944b074ff157b912fd197045c1)  
9) New sublime snippet from this [gist](https://gist.github.com/ChucKN0risK/777f52bc96b90087ab5998235be4d22c)

#### Updates iTunes Preferences
1) Update musuic location folder
2) Disable "Keep iTunes folder media organized"
3) Disable "Copy files to iTunes media folder"
