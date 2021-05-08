# reinstall-DE-for-EndeavourOS

`git clone https://github.com/killajoe/reinstall-DE-for-EndeavourOS.git`

`cd reinstall-DE-for-EndeavourOS`

`ls`
will list the files

`sudo pacman -S --needed - < <de-wm-name to reinstall>`

where `<de-wm-name to reinstall>` is one of the text files from this repo including `eos-base-group` what will install needed packages would be there on a default install.

example:

`sudo pacman -S --needed - < xfce4`
