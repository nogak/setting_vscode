# setting_vscode

##<Windows>
mklink /d %AppData%\Code\User {vscodeディレクトリの場所}

##<Linux>
ln -fnsv {vscodeディレクトリの場所} $HOME/.config/Code/User

##jsonファイルのパス
*Windows %APPDATA%\Code\User\settings.json
*ac $HOME/Library/Application Support/Code/User/settings.json
*inux $HOME/.config/Code/User/settings.json
