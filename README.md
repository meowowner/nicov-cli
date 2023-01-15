# nicov-cli
Cli tool around yt-dlp to interact with nicovideo.jp website
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
This project is a simple interface with history being stored in device to interact with nicovideo.jp website through yt-dlp.
<br>
<b>Use of yt-dlp, interaction with website and use of content are at user's own risk.</b>
<br>
#### Files that are being used by this project:
  $HOME/.nicov_history
<br>
  $HOME/.nicov_history_cache
<br>
  $HOME/.nicov_cache
<br>
<b>  [if cache files exist, then they will be truncated!]</b>
