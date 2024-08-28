# brew installs:

## https://brew.sh/

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## various apps from "brew bundle dump"
curl -o ~/Brewfile https://raw.githubusercontent.com/james-s-w-clark/IdiosApps/master/%7E/.config/Brewfile

brew bundle install


# runtime installs w/ https://github.com/jdx/mise
curl -o ~/config.toml https://raw.githubusercontent.com/james-s-w-clark/IdiosApps/master/%7E/.config/mise/config.toml

mise install
