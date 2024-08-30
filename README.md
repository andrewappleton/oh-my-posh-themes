# oh-my-posh-themes

## Install
winget install JanDeDobbeleer.OhMyPosh -s winget

## Configure:
Place json file in a location used for your oh-my-posh themes, for instance $env:POSH_THEMES_PATH

## Add following to $PROFILE
oh-my-posh --init --shell pwsh --config $env:POSH_THEMES_PATH/ara-atomic.json | Invoke-Expression
