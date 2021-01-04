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

### System Preferences

1. Trackpad -&gt; Tap to click
2. Sound -&gt; Play feedback when volume is changed
3. Dock & Menu Bar -&gt; WiFi -&gt; Unshow in Menu Bar
4. Dock & Menu Bar -&gt; Battery -&gt; Unshow in Menu Bar, Show in Control Centre, Show Percentage
5. Dock & Menu Bar -&gt; Spotlight -&gt; Unshow in Menu Bar

### First Time Setups

1. Xcode
2. Android Studio

### Git

1. `git config --global user.name <>`
2. `git config --global user.email <>`
3. `ssh-keygen`
4. Upload key to GitHub

### Work Projects

1. Clone work repositories

