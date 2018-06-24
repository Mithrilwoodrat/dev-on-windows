# [See the wiki.](https://github.com/orlp/dev-on-windows/wiki)

## Setup WSL
* [setup ssh service in WSL](https://gist.github.com/Mithrilwoodrat/6ec637f0b85e7e3cc733ffa7c106677a)

## Setup ConEmu
* Add/refresh default tasks After Install WSL or Msys2

## Setup Msys2 Home
* [Set up $HOME](https://github.com/valtron/llvm-stuff/wiki/Set-up-Windows-dev-environment-with-MSYS2) 
  Edit /etc/fastic add line `:/Users/<username> /home/<username> ntfs binary,noacl,auto 1 1` to enable ssh client find your config
  
## Install  Visual C++ Build Tools 2015
edit ~/.bashrc add `export PATH=$PATH:/c/Program\ Files\ \(x86\)/MSBuild/14.0/Bin`
