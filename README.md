# `git rev-parse HEAD` in dokku env

Lets you fetch the git revision hash used to build the app from the `GIT_REV`
environment variable.

## Installation

```
sudo git clone https://github.com/rodchyn/dokku-git-rev /var/lib/dokku/plugins/dokku-git-rev
sudo dokku plugins-install
```

The environment variable will be set next time you deploy.
