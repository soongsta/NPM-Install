'Cannot find module 'internal/util/types' error when running 'npm install'

rd %USERPROFILE%\AppData\Roaming\npm /s /q
rd %USERPROFILE%\AppData\Roaming\npm-cache /s /q

uninstall node

rd C:\Program Files\nodejs /s /q

re-install node