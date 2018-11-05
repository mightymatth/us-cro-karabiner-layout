# us-cro-karabiner-layout

Croatian mapping with right_command for MacOS

## Setup

Install Karabiner-elements (https://pqrs.org/osx/karabiner/).

Set [this](https://bitbucket.org/mightymatth8/us-cro-karabiner-layout/raw/master/us-cro-layout-karabiner.json) file to `~/.config/karabiner/assets/complex_modifications` directory.

Open Karabiner-elements and go to: `Complex Modifications` > `Add rule` > `Enable All` under "Croatian letters on right command key"

This will work only on US keyboard.

For example, if you want type `ž` letter, press `right_command` with `\` (where `ž` would normally appear on Croatian keyboard)

### For Windows/Linux physical keyboards

Open `karabiner-Elements` and open _Simple modifications_ tab.

Set new Simple modifications:
```
left_alt > left_gui
left_gui > left_alt
right_alt > right_command
non_us_pound > backslash
```

Created by Matija Pevec (2018-11-05)