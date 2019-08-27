## Reload Bash
```bash
source ~/.bashrc
```

## Twig Debug
```yml
parameters:
  twig.config:
    debug: true
```

## VSCode
CONTROL + P - Quick mode

## Chrome
CONTROL + SHIFT + P - Command Mode

## Shell Commands

### Applying Patch
```bash
patch -p1 < patch
```

### Misc
drush uprm -rf - Remove all contents
chown devboxco:devboxco filename
sudo chown -R devboxco:nobody target

### Files
pwd
-r
ls (-l vs -al) -a shows hidden files (-k?)
autocomplete?
chmod(o/g/u)(-/+) -r   or a=r (all == read)
chown owner file  /chown owner:group file
chgrp group file

### Compress / Uncompress
zip new.zip filename.txt
unzip new.zip
gzip filename.txt
gunzip new.zip
tar -cvf (Create, verbose, file) file.tar file.txt
tar -xvf file.tar (x = extract, doesn't destroy tar)
tar -cvzf file.tar.gz (or .tgz) create, verbose, zip, file
tar -xvzf file.tar.gz (untar)

### Creating Symbolic Links
ln -s path newname(optional) (symbolic link) - Hard links?

### SCO Copy from server
ssh
scp -r -pPORTNO user@sever:remotepath localpath

### Searching (Files / Folders)
locate file (all directories) - requires sudo updatedb to update (quick)
find -name file (from where your located)
find path(i.e. /) -name file
find requires * wild card to find other files / locate doesn't

### Searching (within files)
grep 'string' file
grep 'string' * (Search files within current directory)
grep 'string' folder/* (Search within folder)
grep -r 'string' folder/* (Search within folder recursivly)
grep -r 'string' . (Search within folder recursivly from here)
-n (show line number)
-l (filenames only)
-v (not)
-i (ignore case)

## Command history
Ctrl + P (or up arrow) = go to previous command
Ctrl + N (or down arrow) = go to next command
Ctrl + R = search (Ctrl + R to scroll through, Esc to select but not execute)
!!	Print previous command

## Moving
- Ctrl + E = move to end of line
- Ctrl + A = move to beginning of line

## Deleting
- Ctrl + H (or back delete key) = one character backwards
- Ctrl + D = one character forward
- Ctrl + W = delete from cursor to beginning of word
- Ctrl + U = clear from cursor to beginning of line
- Ctrl + K = clear from cursor to end of line

