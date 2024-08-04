# nextJS
### Instalar a Node.js
PowerShell
#### layouts.download.codeBox.installsFnm
winget install Schniz.fnm

#### layouts.download.codeBox.fnmEnvSetup
fnm env --use-on-cd | Out-String | Invoke-Expression

#### layouts.download.codeBox.downloadAndInstallNodejs
fnm use --install-if-missing 20

#### layouts.download.codeBox.verifiesRightNodejsVersion
node -v # layouts.download.codeBox.shouldPrint

#### layouts.download.codeBox.verifiesRightNpmVersion
npm -v # layouts.download.codeBox.shouldPrint
