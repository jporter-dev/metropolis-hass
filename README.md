# metropolis-hass

> A minimal Home Assistant theme based on the popular GMK Metropolis keycap set

## Installation

### Manual Installation

1. Create a themes directory if it doesn't already exist
   * `mkdir ~/.homeassistant/themes`
2. Change into the themes directory
   * `cd ~/.homeassistant/themes`
3. Download the theme file
   * `wget https://raw.githubusercontent.com/jporter-dev/metropolis-hass/master/themes/metropolis.yaml`
4. Make sure your configuration is loading your themes directory

``` yaml
# configuration.yaml
frontend:
  themes: !include_dir_merge_named themes
```

* Enable the theme from your profile page

## Screenshots

## Color Palette

GMK Metropolis Pantone colors converted to hex

![image](https://user-images.githubusercontent.com/1226637/155897231-8f91e278-303f-4a3e-ba28-e5942a58145f.png)

| Pantone |   Hex   |
| ------- | ------- |
| 5395C   | #081F2C |
| 333C    | #3CDBC0 |
| 142C    | #F1BE48 |
| 179C    | #E03C31 |
