# screenshot2latex
1) takes screenshot
2) converts it to latex (using https://mathpix.com)
3) pastes latex to clipboard

## Run
`screenshot2latex`

## Requirements
- Python 3.X (recommended distribution: Anaconda)
- gnome-screenshot
- [Mathpix credentials](https://dashboard.mathpix.com)

## Install
```bash
pip install git+ssh://git@github.com/rmst/screenshot2latex.git
```

Add Mathpix credentials to bash `.bashrc`

```bash
export MATHPIX_ID="MATHPIX_ID"
export MATHPIX_KEY="MATHPIX_KEY"
```

## Tips

On Ubuntu/Gnome: assing a keyboard shortcut to screenshot2latex go to `Settings/Keyboard/Custom Shortcuts` click on `+` and add `screenshot2latex` as command.

You might have to restart the computer to make the credentials available to the shell (e.g. gnome).
