# Pre run commands:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install ansible

xcode-select --install
```

**Sign into the apple store**
# Running the playbook
checkout the repo and cd into it

```bash
git clone git@github.com:harbinger55/mac_setup.git
cd mac_setup
```

Then run the anible playbook

```bash
ansible-playbook ./mac_setup.yml
```

# Manual installs
## Caldigit
https://downloads.caldigit.com/
Docking station & apple superdrive, etc

## Obsidian
https://obsidian.md/


## Grammarly
https://app.grammarly.com/apps

## Setup iterm2 profile
After Dropbox is installed and synced
In iterm2 go to Preferencs -> General -> Preferences
Check the `Load preferences from a custum folder or URL`
Select your folder in Dropbox