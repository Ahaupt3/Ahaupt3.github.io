# Code

![Screenshot](../img/tools/vs-code.jpg)

## Installation

### Import GPG Key & Add Repo to Sources

``` sh
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
```
``` sh
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
```

### Install VS Code

``` sh
sudo apt update
sudo apt install -y code
```
