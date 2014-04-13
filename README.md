freshBuntu
==========

What to do when you have a fresh install of Ubuntu

GitHub Key Pair
==========
https://help.github.com/articles/generating-ssh-keys

SSH Client and Server
==========
`sudo apt-get install openssh-client`

`sudo apt-get install openssh-server`

Disable SSH password login
-----------
Change the line (51) `#PasswordAuthentication yes` to `PasswordAuthentication no`

Git
==========
`sudo apt-get install git`

`git config --global user.name "Your Name"`

`git config --global user.email you@example.com`

FileZilla
==========
`sudo apt-get install filezilla`

DropBox
==========
https://www.dropbox.com/download?dl=packages/ubuntu/dropbox_1.6.0_amd64.deb

Remove Sudo Password Prompt
==========
`sudo visudo`

Change the line (25) `%sudo ALL=(ALL) ALL` to `%sudo ALL=(ALL) NOPASSWD: ALL`

BashRC Prompt
===========
http://bashrcgenerator.com/

`export PS1="\[\e[00;31m\]\A\[\e[0m\]\[\e[00;37m\] [\w] : @\[\e[0m\]"`

Linux Terminal
===========
Background Tab - ~50% Transparent background

Color Tab: 
![alt text](https://github.com/mstokes5/freshBuntu/tree/master/images/color.png "Terminal Color Tab")

Color Tab: 
![alt text](https://github.com/mstokes5/freshBuntu/tree/master/images/term.png "Terminal Color Tab")

Gimp
===========
`sudo apt-get install gimp`

Bash Aliases
===========
`vim ~/.bash_aliases`

```alias get='sudo apt-get install```

VLC
============
`sudo apt-get install vlc`

Folder Bookmarks and ShortCuts
============

Color Tab: 
![alt text](https://github.com/mstokes5/freshBuntu/tree/master/images/book_before.png "Before")

Color Tab: 
![alt text](https://github.com/mstokes5/freshBuntu/tree/master/images/book_after.png "After")

