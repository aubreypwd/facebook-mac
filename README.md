# Facebook

![](screenshot.png)

An (unofficial) native MacOS App for Facebook.

# Install

## Homebrew Cask

### Install

```bash
brew tap aubreypwd/homebrew-cask
brew update
brew cask install facebook
```

### Upgrade

```
brew update
brew upgrade facebook
```

## Download

Or download the `.dmg` in [releases](https://github.com/aubreypwd/facebook-mac/releases/latest) and install per usual.

*_Note, you will have to Right-click on the Facebook to open for the first time._*

---

# Development

1. Clone repo
2. `npm install`
3. `npm run build`

`npm run build` will built the application to `build/` and  `npm run dist` to generate a `.dmg` in `dist/` for distribution and installation.
