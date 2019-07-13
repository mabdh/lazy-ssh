# lazy-ssh

Shell function to fuzzy search a remote ssh address, connect to it automatically, and copy command to clipboard.

Inspired by [lazy-connect](https://github.com/thecasualcoder/lazy-connect) library.

## Prerequisite

1.  [fzf](https://github.com/junegunn/fzf)
2.  [kv-bash](https://github.com/damphat/kv-bash)

```
brew install fzf
```

## Install

### Using Homebrew

<!-- ```
brew tap thecasualcoder/stable
brew install lazy-connect
``` -->

### Manual

<!-- ```
git clone https://github.com/thecasualcoder/lazy-connect.git ~/.lazy-connect
sudo ln -s ~/.lazy-connect/lazy-connect /usr/local/bin/lazy-connect
``` -->

### Usage

```
lazy-ssh - Shell function to fuzzy search remote ssh address
            , connect to it automatically, and copy command to clipboard.

-s    - Set key value of remote name and its address, 'lazy-ssh -s MyRemote-1 192.168.0.1'.
-l    - List all key value remote name and its address.
-c    - Clear all kv pairs.
-u    - Get default username to connect to the remote.
-y    - Set default username to connect to the remote, 'lazy-ssh -y remote_user'.
-h    - Show this help.
```