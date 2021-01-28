# mac

![ShellCheck](https://github.com/haafiz-io/dotfiles/workflows/ShellCheck/badge.svg)

## pre-mac

1. Country -&gt; Netherlands
2. Preferred Languages -&gt; English \(UK\)
3. Input Sources -&gt; ABC - Extended
4. Disable Siri

## mac

Download setup script:

```bash
curl -OL haafiz.io/mac
```

Review the script:

```bash
cat mac
```

If everything looks good, start your engines:

```bash
sh mac
```

## post-mac

1. Remove all icons from Dock
2. In Finder, add ~/ to Favourites

### System Preferences

1. Trackpad -&gt; Tap to click
2. Sound -&gt; Play feedback when volume is changed
3. Dock & Menu Bar -&gt; WiFi -&gt; Unshow in Menu Bar
4. Dock & Menu Bar -&gt; Battery -&gt; Unshow in Menu Bar, Show in Control Centre, Show Percentage
5. Dock & Menu Bar -&gt; Spotlight -&gt; Unshow in Menu Bar
6. Desktop -&gt; Screen Saver -&gt; Start after: Never
7. Desktop -&gt; Screen Saver -&gt; Hot Corners
   1. Top right: Lock Screen
   2. Top left: Desktop

### First Time Setups

1. Xcode
   1. Preferences -&gt; Locations -&gt; Command Line Tools
   2. Preferences -&gt; Text Editing -&gt; Editing -&gt; Including whitespace-only lines
2. Android Studio
   1. File -&gt; Invalidate Caches / Restart
   2. Android Studio -&gt; Preferences -&gt; Emulator -&gt; Launch in a tool window
   3. Android Studio -&gt; Preferences -&gt; Appearance -&gt; Widescreen tool window layout
3. Dash
   1. Search Using Selected Text: ⇧⌘D
   2. Don't show dock icon
   3. Show menu bar icon
   4. Dismiss main window
4. Time Out
   1. General -&gt; Automatically start Time Out
   2. Normal - break for 10 minutes every 1 hour
   3. Micro - break for 15 seconds every 15 minutes

### Git

1. `git config --global user.name <>`
2. `git config --global user.email <>`
3. `ssh-keygen`
4. Upload key to GitHub

### Work Related

1. Clone work repositories
2. Download [Xcode beta](https://developer.apple.com/download/)

