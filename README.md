# google-spicetify
Spotify with Google style

## Previews
#### Base
<img src="https://i.imgur.com/qguGx46.png" alt="img" align="center" width="600px">

#### Gow
<img src="https://i.imgur.com/XBnjRgk.png" alt="img" align="center" width="600px">

#### Dark
<img src="https://i.imgur.com/k6cIQik.png" alt="img" align="center" width="600px">

## How to install
1. Install [spicetify-cli](https://github.com/khanhas/spicetify-cli) and make sure it applies default theme succesfully.
2. Run these commands:
  
**Linux and MacOS** in Bash:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/khanhas/google-spicetify
```

**Windows** in Powershell:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/khanhas/google-spicetify
```

3. Finally, run:
```
spicetify config current_theme google-spicetify
spicetify apply
```

There are 4 color schemes you can choose: `Base`, `Dark`, `Gow`, `Spotify`. Change scheme with commands:
```
spicetify config color_scheme <scheme name>
spicetify apply
```
