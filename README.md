# fbecart's PPA repository

## Usage

```shell script
curl -SsL https://fbecart.github.io/ppa/debian/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/fbecart.list https://fbecart.github.io/ppa/debian/fbecart.list
sudo apt update
# sudo apt install ...
```

## Available packages

### [Žinoma](https://github.com/fbecart/zinoma/blob/master/README.md)

Installation:

```shell script
sudo apt install zinoma
```

## Repository setup documentation

https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html
