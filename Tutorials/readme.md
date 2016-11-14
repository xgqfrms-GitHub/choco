# Chocolatey 

## install

https://chocolatey.org/install

```sh
# PowerShell v3+
> iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex

# CMD
> @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

``` 

## yarn install & usage (v0.16.1)

https://yarnpkg.com/en/docs/install
https://yarnpkg.com/en/docs/usage
https://github.com/yarnpkg/yarn

```sh
> choco install yarn

> yarn --version

> yarn init

> yarn
or
> yarn install

``` 


> Chocolatey - kind of like apt-get, but for Windows

https://github.com/chocolatey/choco/wiki

https://chocolatey.org/docs



## how check Powershell Version ?

https://social.technet.microsoft.com/Forums/windowsserver/en-US/c3453085-af45-46d2-ae3a-174b99e21554/how-check-powershell-version-?
forum=winserverpowershell

```sh
# To find the PowerShell version, in PowerShell, type the following command:
> Get-Host

or

> $PSVersionTable.PSVersion

# v5.1

Get-PSDrive
Get-PSProvider
Get-PSSnapin
Get-PSBreakpoint
Get-PSCallStack
Get-PSDrive
Get-PSProvider
Get-PSSession
Get-PSSessionConfiguration
Get-PSSnapin

``` 



##  Chocolatey Release Notes

0.10.3 (October 7, 2016)

https://github.com/chocolatey/choco/wiki/ReleaseNotes





## CommandsReference

https://github.com/chocolatey/choco/wiki/CommandsReference

```sh
 -?, --help, -h

-y, --yes, --confirm

-f, --force

``` 




## Commands

```sh
list - lists remote or local packages
search - searches remote or local packages (alias for list)
info - retrieves package information. Shorthand for choco search pkgname --exact --verbose
install - installs packages from various sources
pin - suppress upgrades for a package
outdated - retrieves packages that are outdated. Similar to upgrade all --noop
upgrade - upgrades packages from various sources
uninstall - uninstalls a package
pack - packages up a nuspec to a compiled nupkg
push - pushes a compiled nupkg
new - generates files necessary for a chocolatey package from a template
source - view and configure default sources
sources - view and configure default sources (alias for source)
config - Retrieve and configure config file settings
feature - view and configure choco features
features - view and configure choco features (alias for feature)
setapikey - retrieves or saves an apikey for a particular source (alias for apikey)
apikey - retrieves or saves an apikey for a particular source
unpackself - have chocolatey set it self up
version - [DEPRECATED] will be removed in v1 - use `choco outdated` or cup <pkg|all> -whatif instead
update - [DEPRECATED] RESERVED for future use (you are looking for upgrade, these are not the droids you are looking for)
download - downloads packages - optionally downloading and internalizing all remote resources (recompiling)

# Please run chocolatey with choco command -help for specific help on each command.

``` 

# Chocolatey & yarn
