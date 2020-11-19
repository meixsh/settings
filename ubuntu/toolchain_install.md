# install sogoupinyin under Ubuntu 20.04

- `sudo apt update`
- `sudo apt upgrade` 
- `sudo apt install fcitx-bin`
- `sudo apt install fcitx-table`
- open firefox download sougou*.deb for linux according system bits
	+ `uname -a`
	+ `lsb_release -a`
- `sudo dpkg -i sougou*.deb`
	+ if showing errors like dependecies, using `sudo apt install -i` to fix
- settings &rarr; Region & Language &rarr; Manage Installed Languages &rarr; Install/Remove Languages...
&rarr; chinese simple  
keyboard... chose fcitx &rarr; Apply System-Wide
- reboot system
