# New_Computer_Config
List of things to do with a new computer

💡 Enhance with https://gist.github.com/t-io/8255711

## 1. Install apps
- Install [Homebrew](http://brew.sh/): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- Install NVM: `curl -L https://github.com/creationix/nvm/raw/v0.33.11/install.sh | bash`
- Install tools
	- `brew install git node awscli ffmpeg`
	- [htop](https://hisham.hm/htop/) `brew install htop`
	- [Yarn](https://yarnpkg.com/en/) `brew install yarn`
	- [youtube-dl](https://rg3.github.io/youtube-dl/) `brew install youtube-dl`
	- [Mac App Store command line interface](https://github.com/mas-cli/mas) `brew install mas`
- Install [QuickLook Plugins](https://github.com/sindresorhus/quick-look-plugins)
	- `brew install --cask qlcolorcode qlstephen qlmarkdown quicklook-json betterzip qlimagesize webpquicklook qlvideo`
- Fix potential QL plugins: Example for webpquicklook `xattr -d com.apple.quarantine ~/Library/QuickLook/WebpQuickLook.qlgenerator`
- [Install main softs](https://caskroom.github.io/search) or use [Applite](https://github.com/milanvarady/Applite)
	- `brew install --cask google-chrome slack firefox visual-studio-code iterm2 flux bettertouchtool tower transmit soulseek mediahuman-audio-converter appcleaner android-file-transfer vlc webtorrent figma docker notion megasync meta cleanshot ngrok deepl linear-linear telegram zoom raycast pitch loom superhuman gather the-unarchiver obsidian zsh nicotine-plus`
- [Set zsh as default shell](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH#how-to-install-zsh-on-many-platforms): `chsh -s /usr/local/bin/zsh`
- Set `.zprofile`and `.zshrc` files from https://gist.github.com/ChucKN0risK/666d49b14fbccfab67d5ebc0f10caef5
- Install Mac App Store Softs (iA Writer, Paste, Gifski)
	- `mas install 775737590 967805235 1351639930`
- Update Potential outdated App Store apps such as Xcode
	- `mas upgrade`
- [Google Chrome Canary](https://www.google.fr/chrome/browser/canary.html)
- [Paste 2.5](https://pasteapp.io/mac/legacy/download/)
- [Logi Options](https://www.logitech.fr/fr-fr/product/options): to have all features of Logitech mouse and keyboard
- [Texts](texts.com)
- [Spek](https://www.spek.cc/) to detect fake reencoded mp3/flac files

📝 To update all outdated app installed via homebrew: `brew update && brew upgrade`

## 2. Update macOS preferences
1. Disable natural scroll direction
2. Enable Dock hiding
3. Change right click to right bottom corner
4. Change keyboard key repeat rate to make it faster: System Preferences => Keyboard => Key Repeat Rate
5. Always show scrollbars: System Preferences > General > Show scroll bars (to prevent UI issues when developping)
6. [Disable "Wake for WiFi access"](https://cln.sh/93Eswi) + [Other Settings](https://twitter.com/thorstenball/status/1088842854892482561)
7. Update iTunes Preferences
	1. Update music location folder
	2. Disable "Keep iTunes folder media organized"
	3. Disable "Copy files to iTunes media folder"
	4. Disable notifications when song changes
	5. Import all Music Playlist from MEGA (May have to update the tracks path in VS Code to match user name in macOS)

## 3. Others
1. Install [MyMind Firefox extension](https://mymind.com/wp-content/uploads/2021/11/mymind_an_extension_for_your_mind-2.0.2-fx.xpi)
2. Enable Flux, Mega at startup
3. [Set VisualStudio Code $PATH](https://stackoverflow.com/a/29971430/3906770): After installation, launch VS Code. Now open the Command Palette (F1 or ⇧⌘P on Mac) and type shell command to find the Shell Command: Install 'code' command in PATH command.
4. Log in npm through the CLI: `npm login`
5. Automatically set the corresponding NPM version when you enter a project: https://github.com/nvm-sh/nvm#zsh
6. Enable the `z` plugin for `zsh` by adding it in the plugins like so in the `.zshrc` file: `plugins=(git z)`
7. iTerm2:
  - Add margins (Preferences > Appearance): `30` for y and `50` for x margins
  - Make iTerm use previous session's directory (Preferences > Profile > Reuse previous session's directory)
8. [Import Tower license](https://account.git-tower.com/account/licenses)
9. Update global git config: `git config --global user.email "lchenais@gmail.com"; git config --global user.name "Louis Chenais"; git config --global pull.rebase true;`

### Firefox
1. Open Firefox and connect Firefox account to sync settings
2. Connect to Lastpass
3. Install Vue Devtools: https://devtools.vuejs.org/guide/installation.html
4. Set Firefox theme preferences to "System Theme"

### BetterTouchTool
1. Basic Settings > Open on startup
2. Import presets and license

### Paste
- Set shortcuts
- Disable sound effects

### Gather
- Disable minimize window: Preferences > Desktop

### Metabase
- Disable adblock for Metabase. Otherwise hompegae won't be accessible.

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
