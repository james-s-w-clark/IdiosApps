# brew installs:

## [brew](https://brew.sh/)

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## various apps from "brew bundle dump"

```shell
curl -o ~/Brewfile https://raw.githubusercontent.com/james-s-w-clark/james-s-w-clark/master/%7E/.config/Brewfile
brew bundle install
```

# runtime installs w/ [mise](https://github.com/jdx/mise)

```shell
curl -o ~/config.toml https://raw.githubusercontent.com/james-s-w-clark/james-s-w-clark/master/%7E/.config/mise/config.toml

mise install
```
