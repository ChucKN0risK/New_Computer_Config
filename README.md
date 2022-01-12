# New_Computer_Config
List of things to do with a new computer

💡 Enhance with https://gist.github.com/t-io/8255711

#### BetterTouchTool license & backup + Tower license

#### Things to install:
- Install [Homebrew](http://brew.sh/): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- Install Oh My Zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
- Install NVM : `curl -L https://github.com/creationix/nvm/raw/v0.33.11/install.sh | bash`
- Install tools
	- `brew install git node awscli ffmpeg`
	- [htop](https://hisham.hm/htop/) `brew install htop`
	- [Yarn](https://yarnpkg.com/en/) `brew install yarn`
	- [youtube-dl](https://rg3.github.io/youtube-dl/) `brew install youtube-dl`
	- [Mac App Store command line interface](https://github.com/mas-cli/mas) `brew install mas`
- Install [QuickLook Plugins](https://github.com/sindresorhus/quick-look-plugins)
	- `brew install --cask qlcolorcode qlstephen qlmarkdown quicklook-json betterzip qlimagesize webpquicklook qlvideo`
- Fix potential QL plugins: Example for webpquicklook `xattr -d com.apple.quarantine ~/Library/QuickLook/WebpQuickLook.qlgenerator`
- [Install main softs](https://caskroom.github.io/search)
	- `brew cask install google-chrome slack firefox visual-studio-code iterm2 flux bettertouchtool tower transmit soulseek mediahuman-audio-converter appcleaner android-file-transfer vlc webtorrent fontplop figma docker airtable notion megasync meta cleanshot ngrok deepl linear-linear telegram zoom raycast pitch loom tempo`
- Install Mac App Store Softs (iA Writer, The Unarchiver)
	- `mas install 507257563 775737590 425424353`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)
- [Paste 2.5](https://pasteapp.io/mac/legacy/download/)
- [Paste Helper](https://pasteapp.me/helper/)
- [Logi Options](https://www.logitech.fr/fr-fr/product/options)

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`

#### Todo
- Add BetterTouchTool, Flux, Mega at startup
- [Set VisualStudio Code $PATH](https://stackoverflow.com/a/29971430/3906770):
After installation, launch VS Code. Now open the Command Palette (F1 or ⇧⌘P on Mac) and type shell command to find the Shell Command: Install 'code' command in PATH command.
- Log in npm through the CLI: `npm login`
- Do this to automatically set the corresponding NPM version when you enter a project: https://github.com/nvm-sh/nvm#zsh
- Enable the `z` plugin for `zsh` by adding it in the plugins like so in the `.zshrc` file: `plugins=(git z)`
- Change keyboard key repeat rate to make it faster : System Preferences => Keyboard => Key Repeat Rate
- Disable sound effects for Paste
- Add margins to iTerm (Advanced > General): 30 for y and 50 for x margins

#### Soulseek config
- Import config
- Enable UPnP mapping
- Toggle "Don't create subfolders for single downloads"
- Toggle "Don't create username folders"

#### Tower config
1. Add Finder and Terminal shortcuts in the toolbar
2. Set iTerm2 as the default Terminal app

#### Update macOS preferences
- [Disable "Wake for WiFi access"](https://cln.sh/93Eswi) + [Other Settings](https://twitter.com/thorstenball/status/1088842854892482561)

#### Updates iTunes Preferences
1) Update music location folder
2) Disable "Keep iTunes folder media organized"
3) Disable "Copy files to iTunes media folder"
4) Disable notifications when song changes
