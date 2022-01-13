# New_Computer_Config
List of things to do with a new computer

💡 Enhance with https://gist.github.com/t-io/8255711

## 1. Install apps
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
	- `brew install --cask google-chrome slack firefox visual-studio-code iterm2 flux bettertouchtool tower transmit soulseek mediahuman-audio-converter appcleaner android-file-transfer vlc webtorrent fontplop figma docker airtable notion megasync meta cleanshot ngrok deepl linear-linear telegram zoom raycast pitch loom superhuman gather the-unarchiver obsidian`
- Install Mac App Store Softs (iA Writer, Paste)
	- `mas install 775737590 967805235`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)
- [Paste 2.5](https://pasteapp.io/mac/legacy/download/)
- [Logi Options](https://www.logitech.fr/fr-fr/product/options)
- [Texts](texts.com)

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`

## 2. Update macOS preferences
1. Disable natural scroll direction
2. Enable Dock hiding
3. Change right click to right bottom corner
4. Change keyboard key repeat rate to make it faster: System Preferences => Keyboard => Key Repeat Rate
5. [Disable "Wake for WiFi access"](https://cln.sh/93Eswi) + [Other Settings](https://twitter.com/thorstenball/status/1088842854892482561)
6. Update iTunes Preferences
	1. Update music location folder
	2. Disable "Keep iTunes folder media organized"
	3. Disable "Copy files to iTunes media folder"
	4. Disable notifications when song changes

## 3. Others
1. Open Firefox and connect Firefox account to sync settings
2. Connect to Lastpass
3. Install [MyMind Firefox extension](https://mymind.com/wp-content/uploads/2021/11/mymind_an_extension_for_your_mind-2.0.2-fx.xpi)
5. Enable Flux, Mega at startup
6. [Set VisualStudio Code $PATH](https://stackoverflow.com/a/29971430/3906770):
After installation, launch VS Code. Now open the Command Palette (F1 or ⇧⌘P on Mac) and type shell command to find the Shell Command: Install 'code' command in PATH command.
6. Log in npm through the CLI: `npm login`
7. Automatically set the corresponding NPM version when you enter a project: https://github.com/nvm-sh/nvm#zsh
8. Enable the `z` plugin for `zsh` by adding it in the plugins like so in the `.zshrc` file: `plugins=(git z)`
9. Disable sound effects for Paste
10. Add margins to iTerm (Preferences > Appearance): `30` for y and `50` for x margins
12. Import Tower license

### BetterTouchTool
1. Basic Settings > Open on startup
2. Import presets and license

### Paste
1. Set shortcuts
  - 

### Cleanshot
1. Configure Cleanshot by importing license from personal email address
2. Open on startup
3. Replace system shortcuts by Cleanshot X ones
4. Add OCR shortcut as: Command + Shift + 2
5. Preferences > Quick Access > Set Overlay size to 2
6. Preferences > Recording > Enable Highlight clicks
7. Preferences > Screenshots > Set File Format to JPG

### Soulseek config
- Import config
- Enable UPnP mapping
- Toggle "Don't create subfolders for single downloads"
- Toggle "Don't create username folders"

### Tower config
1. Add Finder and Terminal shortcuts in the toolbar
2. Set iTerm2 as the default Terminal app
