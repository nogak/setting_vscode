# setting_vscode
<Windows>
mklink /d %AppData%\Code\User {vscodeディレクトリの場所}

<Linux>
ln -fnsv {vscodeディレクトリの場所} $HOME/.config/Code/User

Windows %APPDATA%\Code\User\settings.json
Mac $HOME/Library/Application Support/Code/User/settings.json
Linux $HOME/.config/Code/User/settings.json