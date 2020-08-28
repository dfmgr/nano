## nano  
  
text editor which aims to introduce a simple interface and intuitive command options to console based text editing  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/nano/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install nano
```  

Fedora Based:

```shell
yum install nano
```  

Arch Based:

```shell
pacman -S nano
```  

MacOS:  

```shell
brew install nano
```
  
```shell
mv -fv "$HOME/.config/nano" "$HOME/.config/nano.bak"
git clone https://github.com/dfmgr/nano "$HOME/.config/nano"
ln -sf "$APPDIR/nanorc" "$HOME/.nanorc"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/nano" target="_blank" rel="noopener noreferrer">nano wiki</a>  |  
  <a href="nano" target="_blank" rel="noopener noreferrer">nano site</a>
</p>  
