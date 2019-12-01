dotfiles
================

dotfiles that reside in my homes (yes my computation engines live in
several homes with friendly hosts):

  - on CentOS 7 on a 48 core VM with 1TB RAM, part of Big Lebowski and
    owned by ETH Zürich
  - on local Ubuntu 18 running on a hackintosh Pro, provided by ETH and
    in control of me

I am the same on both machines:

``` bash
whoami
```

    ## baumanph

``` bash
# This is my remote friend with blue fishes and cabal;
# cooking with elixir comes later
ls -la /media/vm/
```

    ## total 29700
    ## drwx------  1 61002 17350     4096 Nov 27 14:50 .
    ## drwxr-xr-x 14 root  root      4096 Okt 24 16:30 ..
    ## -rw-r--r--  1 61002 17350        0 Aug 29 16:51 %
    ## -rw-------  1 61002 17350    63962 Nov 28 09:24 .bash_history
    ## -rw-r--r--  1 61002 17350      852 Nov 10 14:19 .bashrc
    ## drwxr-xr-x  1 61002 17350     4096 Nov 10 15:18 bin
    ## drwxr-xr-x  1 61002 17350     4096 Nov 23 15:51 .bluefish
    ## drwxr-xr-x  1 61002 17350     4096 Nov  9 19:20 .cabal
    ## drwxr-xr-x  1 61002 17350     4096 Nov 20 16:30 .cache
    ## drwxrwsr-x  1 61002 17350     4096 Nov 20 16:28 .conda
    ## drwxr-xr-x  1 61002 17350     4096 Nov 12 00:02 .config
    ## drwx------  1 61002 17350     4096 Nov 12 00:02 .dbus
    ## drwxrwx---  1 61002 17350     4096 Okt 17 15:56 .docker
    ## drwxr-xr-x  1 61002 17350     4096 Nov 22 15:14 elixir
    ## drwxr-xr-x  1 61002 17350     4096 Nov  9 18:49 .ghc
    ## -rw-r--r--  1 61002 17350       42 Sep 24 10:20 .gitconfig
    ## drwxr-xr-x  1 61002 17350     4096 Nov 20 16:31 .keras
    ## -rw-------  1 61002 17350       35 Nov 10 23:26 .lesshst
    ## drwx------  1 61002 17350      252 Nov 21 11:20 local
    ## drwxr-xr-x  1 61002 17350     4096 Apr 30  2019 .local
    ## drwxr-xr-x  1 61002 17350     4096 Sep 24 12:12 miniconda3
    ## drwx------  1 61002 17350        0 Apr 30  2019 nashome
    ## drwxr-----  1 61002 17350     4096 Apr 30  2019 .pki
    ## drwx------  1 61002 17350        0 Nov 26 12:30 public
    ## -rw-------  1 61002 17350       93 Nov 20 16:32 .python_history
    ## drwxr-xr-x  1 61002 17350     4096 Apr 30  2019 R
    ## drwxr-xr-x  1 61002 17350     4096 Okt 10 09:06 .R
    ## -rw-r--r--  1 61002 17350       52 Aug 21 20:00 .Renviron
    ## -rw-r--r--  1 61002 17350        0 Okt 17 09:51 .Rhistory
    ## -rw-r--r--  1 61002 17350       63 Nov 10 08:49 .Rprofile
    ## drwxr-xr-x  1 61002 17350     4096 Okt 24 15:55 .rstudio
    ## -rw-r--r--  1 61002 17350 30217656 Mär 12  2013 scala-2.10.1.tgz
    ## drwx------  1 61002 17350     4096 Okt 16 16:17 .ssh
    ## drwxr-xr-x  1 61002 17350     4096 Nov 10 14:21 .TinyTeX
    ## -rw-------  1 61002 17350     3949 Nov 10 14:19 .viminfo
    ## -rw-r--r--  1 61002 17350       90 Sep 24 12:03 .wgetrc
    ## -rw-------  1 61002 17350      448 Nov 27 14:50 .Xauthority

``` bash
# Local machinery
# That commercial Dropbox will be deleted soon...
ls -la $HOME
```

    ## total 97244
    ## drwxr-xr-x 53 baumanph baumanph     4096 Dez  1 18:20 .
    ## drwxr-xr-x  4 root     root         4096 Aug  5 11:58 ..
    ## -rw-rw-r--  1 baumanph baumanph      840 Apr  6  2019 .alsaequal.bin
    ## -rw-rw-r--  1 baumanph baumanph      742 Okt 24 16:02 .anyconnect
    ## drwxrwxr-x  3 baumanph baumanph     4096 Aug  5 15:56 apps
    ## drwxrwxr-x  7 baumanph baumanph     4096 Nov 21 10:30 .atom
    ## -rw-------  1 baumanph baumanph    49857 Dez  1 15:23 .bash_history
    ## -rw-r--r--  1 baumanph baumanph      220 Jan 24  2019 .bash_logout
    ## -rw-r--r--  1 baumanph baumanph     4394 Okt  8 17:50 .bashrc
    ## -rw-r--r--  1 baumanph baumanph     3852 Mai  8  2019 .bashrc-anaconda3.bak
    ## drwxrwxr-x  3 baumanph baumanph     4096 Aug  5 15:53 bin
    ## drwx------ 39 baumanph baumanph     4096 Dez  1 16:32 .cache
    ## drwxrwxr-x  4 baumanph baumanph     4096 Mai 27  2019 caret2hex
    ## drwxrwxr-x  2 baumanph baumanph     4096 Jun  6 09:01 .cifex
    ## drwxrwxr-x  3 baumanph baumanph     4096 Mai 19  2019 .conda
    ## -rw-rw-r--  1 baumanph baumanph       71 Mai 20  2019 .condarc
    ## drwx------ 44 baumanph baumanph     4096 Dez  1 18:37 .config
    ## drwx------  3 root     root         4096 Jan 25  2019 .dbus
    ## drwxr-xr-x  2 baumanph baumanph     4096 Nov 14 11:57 Desktop
    ## -rw-------  1 baumanph baumanph       87 Nov 20 14:33 .directory
    ## drwxrwx---  2 baumanph baumanph     4096 Aug  8 10:38 .docker
    ## drwxr-xr-x  5 baumanph baumanph     4096 Nov 21 15:39 Documents
    ## drwxr-xr-x 10 baumanph baumanph    12288 Dez  1 14:29 Downloads
    ## drwx------  4 baumanph baumanph     4096 Nov 20 13:37 Dropbox
    ## -rw-rw-r--  1 baumanph baumanph        0 Nov 20 14:17 extract
    ## -rw-r--r--  1 baumanph baumanph      110 Jan 28  2019 .fonts.conf
    ## drwx------  2 baumanph baumanph     4096 Dez  1 16:28 .gconf
    ## -rw-r--r--  1 baumanph baumanph       16 Jan 25  2019 gidfile
    ## drwxrwxr-x  6 baumanph baumanph     4096 Nov 20 17:51 .git
    ## -rw-rw-r--  1 baumanph baumanph       98 Okt  1 14:35 .gitconfig
    ## -rw-rw-r--  1 baumanph baumanph       40 Nov 20 17:51 .gitignore
    ## -rw-rw-r--  1 baumanph baumanph 98435072 Dez  1 16:27 .gnotero.sqlite
    ## drwx------  4 baumanph baumanph     4096 Jun 17 18:40 .gnupg
    ## drwxr-xr-x  2 baumanph baumanph     4096 Feb 12  2019 .gphoto
    ## -rw-rw-r--  1 baumanph baumanph      336 Jan 24  2019 .gtkrc-2.0
    ## -rw-------  1 baumanph baumanph     1114 Jan 24  2019 .ICEauthority
    ## drwxr-xr-x  5 baumanph baumanph     4096 Aug  9 20:17 .ipython
    ## drwxrwxr-x  4 baumanph baumanph     4096 Mai  8  2019 .java
    ## drwxrwxr-x  3 baumanph baumanph     4096 Aug  9 20:20 .jupyter
    ## drwxrwxr-x  3 baumanph baumanph     4096 Jan 24  2019 .kde
    ## drwxrwxr-x  3 baumanph baumanph     4096 Mai 20  2019 .keras
    ## drwxrwxr-x  5 baumanph baumanph     4096 Sep 20 13:45 kwin-tiling
    ## drwx------  5 baumanph baumanph     4096 Apr 28  2019 .local
    ## -rw-rw-r--  1 baumanph baumanph     1281 Feb 13  2019 lsf.tmpl
    ## drwxrwxr-x 50 baumanph baumanph     4096 Aug  9 20:08 miniconda3
    ## drwx------  5 baumanph baumanph     4096 Jan 24  2019 .mozilla
    ## -rw-rw-r--  1 baumanph baumanph    12230 Mai 20  2019 msg-error
    ## drwxr-xr-x  2 baumanph baumanph     4096 Jan 24  2019 Music
    ## drwxr-xr-x  7 baumanph baumanph     4096 Jan 25  2019 .mutagen
    ## -rw-r--r--  1 baumanph baumanph       21 Jan 26  2019 .mutagen.toml
    ## drwx------  3 baumanph baumanph     4096 Aug  5 12:07 .org.jabref.JabRefMain
    ## drwxr-xr-x  2 baumanph baumanph     4096 Nov 22 10:51 Pictures
    ## drwx------  3 baumanph baumanph     4096 Jan 27  2019 .pki
    ## -rw-r--r--  1 baumanph baumanph      963 Aug  5 11:52 .profile
    ## drwxr-xr-x  2 baumanph baumanph     4096 Jan 24  2019 Public
    ## drwxrwxr-x  4 baumanph baumanph     4096 Mai  8  2019 .PyCharmCE2019.1
    ## drwxrwxr-x  4 baumanph baumanph     4096 Nov 22 14:57 .PyCharmCE2019.2
    ## -rw-------  1 baumanph baumanph       68 Aug  9 20:26 .python_history
    ## drwxrwxr-x  4 baumanph baumanph     4096 Nov 10 14:37 R
    ## drwxr-xr-x  3 root     root         4096 Aug 13 17:20 .R
    ## -rw-rw-r--  1 baumanph baumanph      118 Jun 22 16:42 .radian_history
    ## -rw-r--r--  1 baumanph baumanph       52 Aug 15 13:50 .Renviron
    ## -rw-r--r--  1 baumanph baumanph    12288 Aug 15 13:47 .Renviron.swp
    ## -rw-rw-r--  1 baumanph baumanph      166 Nov 21 07:52 .Rhistory
    ## -rw-rw-r--  1 baumanph baumanph      205 Nov 20 17:51 ~.Rproj
    ## drwxrwxr-x  4 baumanph baumanph     4096 Nov 20 14:21 .Rproj.user
    ## drwxrwxr-x 22 baumanph baumanph     4096 Dez  1 09:44 .rstudio-desktop
    ## -rw-rw-r--  1 baumanph baumanph        0 Sep 23 16:32 .selected_editor
    ## -rw-------  1 baumanph baumanph       41 Jan 25  2019 .smbcredentials
    ## drwxr-xr-x  8 baumanph baumanph     4096 Aug 12 10:04 snap
    ## drwx------  2 baumanph baumanph     4096 Okt 16 16:20 .ssh
    ## -rw-r--r--  1 baumanph baumanph        0 Jan 24  2019 .sudo_as_admin_successful
    ## drwxr-xr-x  2 baumanph baumanph     4096 Jan 24  2019 Templates
    ## drwxrwxr-x  3 baumanph baumanph     4096 Jan 26  2019 test1
    ## drwxrwxr-x  3 baumanph baumanph     4096 Jan 26  2019 test2
    ## drwxrwxr-x  4 baumanph baumanph     4096 Jun  3 10:56 texmf
    ## drwx------  5 baumanph baumanph     4096 Nov 28 10:52 .thunderbird
    ## drwxrwxr-x  3 baumanph baumanph     4096 Dez  1 18:20 tmp
    ## -rw-r--r--  1 baumanph baumanph       15 Jan 25  2019 uidfile
    ## drwx------  2 baumanph baumanph     4096 Jul 31 19:13 .unison
    ## drwxr-xr-x  2 baumanph baumanph     4096 Jan 24  2019 Videos
    ## -rw-------  1 baumanph baumanph     7313 Okt 21 08:38 .viminfo
    ## -rw-rw-r--  1 baumanph baumanph      215 Nov 12 15:45 .wget-hsts
    ## -rw-------  1 baumanph baumanph       64 Dez  1 16:27 .Xauthority
    ## -rw-rw-r--  1 baumanph baumanph      218 Sep 20 14:58 .Xmodmap
    ## -rw-------  1 baumanph baumanph   716624 Dez  1 18:50 .xsession-errors
    ## drwx------  3 baumanph baumanph     4096 Jan 26  2019 .zotero
    ## drwxr-xr-x  9 baumanph baumanph     4096 Dez  1 16:28 Zotero

# Recipe

## Work securely

``` bash
# be careful and set ownership:
# sudo chmod 600 ~/.smbcredentials 
```

``` bash
(base) baumanph@baumanph-MacBookPro:~$ gpg --list-keys --keyid-format long
/home/baumanph/.gnupg/pubring.kbx
---------------------------------
pub   rsa4096/E5881BA04CED4A9A 2019-04-29 [SC]
      2F0E4AEF51FDEF553D6D50C3E5881BA04CED4A9A
uid                 [ultimate] Philipp Baumann <baumann-philipp@protonmail.com>
sub   rsa4096/48A2D8D27705F72D 2019-04-29 [E]
```
