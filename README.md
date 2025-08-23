# NOTE: 

- Remember to change `<THEME_CONFIG_PATH>`
- Remember to install
  - `Install-Package Terminal-Icons`
  - [CaskaydiaCove NF](https://www.nerdfonts.com/font-downloads)
  - `oh-my-posh`: `winget install JanDeDobbeleer.OhMyPosh --source winget --scope user --force`
- Remember to add new Path variable: `$env:Path += ";C:\Users\user\AppData\Local\Programs\oh-my-posh\bin"`
- Create the profile file if it doesn't exist: `New-Item -Path $PROFILE -Type File -Force`