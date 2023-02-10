# nicov-cli
A cli tool around yt-dlp to interact with nicovideo.jp website

## Install
```
git clone https://github.com/meowowner/nicov-cli && cd ./nicov-cli
sudo chmod +x nicov-cli
sudo cp nicov-cli /usr/local/bin
cd .. && rm -rf ./nicov-cli
```

## Uninstall
```
sudo rm /usr/local/bin/nicov-cli
```

## Usage
This project is a simple interface with history being stored in device to enjoy videos from nicovideo.jp website using yt-dlp.
<br>
<b>Use of yt-dlp, interaction with website and use of content are at user's own risk.</b>
<br>

## Dependencies
 - yt-dlp
 - mpv
 - curl
 - sed
 - grep
 - awk
 - diff (diffutils)
 - coreutils
 - fzf [optional]
 - dmenu [optional]

## Files

### History:
 - $HOME/.local/share/nicov-cli/nicov-cli-history
 - $HOME/.local/share/nicov-cli/nicov-cli-history-links
 - $HOME/.local/share/nicov-cli/nicov-cli-backup (stores names of directories containing backups of nicov-cli-history)

### Cache directory:
 - $HOME/.cache/nicov-cli
