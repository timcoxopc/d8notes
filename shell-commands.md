---
date: 2019-08-29 09:10:10 +1000
title: Shell Commands
body: "### Applying Patch\n\n    patch -p1 < patch\n\n### Misc\n\ndrush uprm -rf -
  Remove all contents chown devboxco:devboxco filename sudo chown -R devboxco:nobody
  target\n\n### Files\n\npwd -r ls (-l vs -al) -a shows hidden files (-k?) autocomplete?
  chmod(o/g/u)(-/+) -r   or a=r (all == read) chown owner file  /chown owner:group
  file chgrp group file\n\n### Compress / Uncompress\n\nzip new.zip filename.txt unzip
  new.zip gzip filename.txt gunzip new.zip tar -cvf (Create, verbose, file) file.tar
  file.txt tar -xvf file.tar (x = extract, doesn't destroy tar) tar -cvzf file.tar.gz
  (or .tgz) create, verbose, zip, file tar -xvzf file.tar.gz (untar)\n\n### Creating
  Symbolic Links\n\nln -s path newname(optional) (symbolic link) - Hard links?\n\n###
  SCO Copy from server\n\nssh scp -r -pPORTNO user@sever:remotepath localpath\n\n###
  Searching (Files / Folders)\n\nlocate file (all directories) - requires sudo updatedb
  to update (quick) find -name file (from where your located) find path(i.e. /) -name
  file find requires * wild card to find other files / locate doesn't\n\n### Searching
  (within files)\n\ngrep 'string' file grep 'string' * (Search files within current
  directory) grep 'string' folder/* (Search within folder) grep -r 'string' folder/*
  (Search within folder recursivly) grep -r 'string' . (Search within folder recursivly
  from here) -n (show line number) -l (filenames only) -v (not) -i (ignore case)\n\n##
  Command history\n\nCtrl + P (or up arrow) = go to previous command Ctrl + N (or
  down arrow) = go to next command Ctrl + R = search (Ctrl + R to scroll through,
  Esc to select but not execute) !!\tPrint previous command\n\n## Moving\n\n* Ctrl
  + E = move to end of line\n* Ctrl + A = move to beginning of line\n\n## Deleting\n\n*
  Ctrl + H (or back delete key) = one character backwards\n* Ctrl + D = one character
  forward\n* Ctrl + W = delete from cursor to beginning of word\n* Ctrl + U = clear
  from cursor to beginning of line\n* Ctrl + K = clear from cursor to end of line"
published: false

---
