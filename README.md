# lazy-ssh

Shell function to store and fuzzy search a remote ssh address locally, and copy command to clipboard.

Inspired by [lazy-connect](https://github.com/thecasualcoder/lazy-connect) library.

## Prerequisite

1.  [fzf](https://github.com/junegunn/fzf)

```
brew install fzf
```

## Install

### Using Homebrew

```
brew tap mabdh/repo
brew install lazy-ssh
```

### Manual

```
git clone https://github.com/mabdh/lazy-ssh ~/.lazy-ssh
sudo ln -s ~/.lazy-ssh/lazy-ssh /usr/local/bin/lazy-ssh
```

### Usage

```
lazy-ssh - Shell function to store and fuzzy search a remote ssh address locally
           , connect to it automatically, and copy command to clipboard.

-s    - Set key value of remote name and its address, 'lazy-ssh -s MyRemote-1 192.168.0.1'.
-l    - List all key value remote name and its address.
-c    - Clear all kv pairs.
-u    - Get default username to connect to the remote.
-y    - Set default username to connect to the remote, 'lazy-ssh -y remote_user'.
-h    - Show this help.
```
