# Builder

## Install

```
sudo curl -L https://raw.githubusercontent.com/FSPNET/builder/master/scripts/publish.sh -o /usr/local/bin/docker-publish
sudo chmod +x /usr/local/bin/docker-publish
```

## Usage

```
~ docker-publish
usage: docker-publish repo[:tag] repo:tag [prefix count]
   ie: docker-publish build:travis FSPNET/php:7.3.4
       docker-publish build FSPNET/php:7.3.4 2
```
