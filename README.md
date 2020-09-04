# webdriverio-starter

### Reference Doc
- https://webdriver.io/docs/gettingstarted.html

### Install Dependency

#### 1. Install [Node.js](https://nodejs.org) LTS version, suggest to install via [nvm](https://github.com/nvm-sh/nvm)

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
nvm install --lts # This will install the latest LTS version.
```

### 2. Install Java via [Homebrew](https://brew.sh/index_zh-tw) if use WireMock service
```sh
brew tap AdoptOpenJDK/openjdk
brew cask install adoptopenjdk8
java -version
```