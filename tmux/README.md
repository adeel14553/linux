## TMUX GUIDE
Install your tmux by

     sudo apt install tmux

Note : For starter the prefix is Ctrl + B

and the copy the .tmux.conf file to your user home directory. Don't forget to clone `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
Load it by `tmux source .tmux.conf` for first time.

Install the plugin and theme by `Prefix I`

Attaching to session : `tmux attach -t session` or `tmux a -t session`

Renaming session : `tmux rename-session` or `prefix $`

Renaming window : `Prefix ,`

Delete a window : `Prefix  x`

Switching session : `Prefix s`

Switching windows : `Prefix w`

Change between sessions shortcut : `Prefix (` or `)`


With above conf you can

Switch between windows by `shift + arrows`

Reorder windows by `Ctrl + Shift + arrows`


Prefix :`move-window current-window-name -t destination-session`  // -s is for source destination

Tpm link : https://github.com/tmux-plugins/tpm

The link for https://gist.github.com/andreyvit/2921703
