## Limelight

Port of the border system that used to be implemented in yabai (v2.4.3).

For the old version of limelight that was simply a focused border, see [focused_border_only](https://github.com/koekeishiya/limelight/tree/focused_border_only)

Requires access to the accessibility API. Supports macOS High Sierra and newer.

```sh
# add the following to the end of your yabairc to have it launch automatically when yabai starts.
# substitute the path to the limelight binary in the 3rd line below.

# kill any existing limelight process if one exists, before we launch a new one
killall limelight &> /dev/null
/path/to/bin/limelight &> /dev/null &
```

### Build

Requires xcode command line tools

```sh
# simply clone repo and run make
  make
```
