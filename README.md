## neomutt  
  
NeoMutt is a command line mail reader  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/neomutt/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install neomutt mailsync notmuch-mutt msmtp pass isync
```  

Fedora Based:

```shell
yum install neomutt mailsync notmuch-mutt msmtp pass isync
```  

Arch Based:

```shell
pacman -S neomutt mailsync notmuch-mutt msmtp pass isync
```  

MacOS:  

```shell
brew install neomutt mailsync notmuch-mutt msmtp pass isync
```
  
```shell
mv -fv "$HOME/.config/neomutt" "$HOME/.config/neomutt.bak"
git clone https://github.com/dfmgr/neomutt "$HOME/.config/neomutt"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/neomutt" target="_blank" rel="noopener noreferrer">neomutt wiki</a>  |  
  <a href="https://neomutt.org" target="_blank" rel="noopener noreferrer">neomutt site</a>
</p>  
