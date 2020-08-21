## neomutt  
  
neomutt  
  
requires:    
```
apt install neomutt mailsync notmuch-mutt msmtp pass isync
```  
```
yum install neomutt mailsync notmuch-mutt msmtp pass isync
```  
```
pacman -S neomutt mailsync notmuch-mutt msmtp pass isync
```  
Suggest: https://github.com/LukeSmithxyz/mutt-wizard  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/NAME/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/neomutt" "$HOME/.config/neomutt.bak"
git clone https://github.com/dfmgr/neomutt "$HOME/.config/neomutt"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/neomutt" target="_blank">neomutt wiki</a>  |  
  <a href="https://neomutt.org/" target="_blank">neomutt site</a>
</p>  
