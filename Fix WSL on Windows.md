# Fix WSL on Windows - System cannot find the file specified | Guide

1. Open powershell as administrator
2. Enter this command

`wsl –-shutdown`

`wslconfig /unregister ubuntu`

`wsl --install --distribution ubuntu`
