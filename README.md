# OmniStack

Node //https://nodejs.org/en/download/package-manager/#windows
React
ReactNative
Expo

PowerShell

others
chocolatey https://chocolatey.org
{
Run Get-ExecutionPolicy. If it returns Restricted, then run Set-ExecutionPolicy AllSigned or Set-ExecutionPolicy Bypass -Scope Process.
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
} 
Node
{
choco install nodejs-lts 
node -v
npm -v

}
yarn https://yarnpkg.com/en/
{
choco install yarn
yarn -v
}

Visual Studio Code https://code.visualstudio.com
Extensions{
Dracula
Material icon theme
}


Configurando Terminal: https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/

Configurando o VSCODE: https://www.youtube.com/watch?v=c7P03kkrEG8
