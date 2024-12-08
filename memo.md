# 個人メモ

### ショートカットメモ
* ctrl + d: 選択した文字列と同じ文字列にカーソル複製
* ctrl + shift + l: 選択した文字と同じ文字列すべてに複製
* alt + 上下矢印: 選択している行をそのまま移動
* ctrl + alt + 上下矢印: カーソル複製
* alt + クリック: クリックしたところにカーソル複製

## 設定ファイルパス
### Windows
%APPDATA%\Code\User\settings.json 
### Mac
$HOME/Library/Application Support/Code/User/settings.json
### Linux
$HOME/.config/Code/User/settings.json

## なんのメモか忘れた。シンボリックリンクでなにかやってる。
### Windows
mklink /d %AppData%\Code\User {vscodeディレクトリの場所}
### Linux
ln -fnsv {vscodeディレクトリの場所} $HOME/.config/Code/User