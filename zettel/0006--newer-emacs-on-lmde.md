# Newer Emacs Version on Linux Mint Debian Edition 4

*And normal debian too...*

Taken from the [\<emacswiki\>](https://lite.duckduckgo.com/lite?kd=-1&kp=-1&q=emacswiki%20Emacs%20Snapshot%20And%20Debian) and a [\<Reddit thread\>](https://lite.duckduckgo.com/lite?kd=-1&kp=-1&q=reddit%20Desmesura%202020%20How%20to%20get%20Emacs%2027%20on%20Debian).


## Via ganeff.de

Maintains debian packages based upon emac git snapshots. Each’s build status can be reviewed at the developer’s [\<gitlab instance\>](https://git.nsb-software.de/joerg/emacs/pipelines).

#### Enable adding a private repository

```sh
sudo apt-get update
sudo apt-get install software-properties-common
```

#### Add the repository by creating the file `/etc/apt/sources.list.d/emacs.list` with the following contents:

```sh
deb http://emacs.ganneff.de/ buster main
```

#### Get the repository's Apt signing key

```sh
wget -q http://emacs.ganneff.de/apt.key -O- | sudo apt-key add
```

#### Update your software repositories

```sh
sudo apt-get update
```

#### Install the emacs snapshot

```sh
sudo apt-get install emacs-snapshot
```
