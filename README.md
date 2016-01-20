# steam-controller

To make a symlink in Windows:
`mklink /J %TARGET_LOCATION% %REPO_LOCATION%`

* For legacy configs, symlink `controller_config` directory to `%SteamLocation%\userdata\%steam_user_id%\241100\remote\controller_config`
* For beta configs, symlink `241100` directory to `%SteamLocation%\steamapps\workshop\content\241100`
