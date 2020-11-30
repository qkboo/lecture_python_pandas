
```cmd
BIT@DESKTOP-MFM72BP MINGW64 ~
$ pwd
/c/Users/BIT

BIT@DESKTOP-MFM72BP MINGW64 ~
$ pwd
/c/Users/BIT

BIT@DESKTOP-MFM72BP MINGW64 ~
$ mkdir my-git

BIT@DESKTOP-MFM72BP MINGW64 ~
$ cd my-git/

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git
$ git init
Initialized empty Git repository in C:/Users/BIT/my-git/.git/

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git branch

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ rm -r .git

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git
$ git init
Initialized empty Git repository in C:/Users/BIT/my-git/.git/

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config --global list
error: key does not contain a section: list

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config --global
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-regex]
    --get-all             get all values: key [value-regex]
    --get-regexp          get values for regexp: name-regex [value-regex]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value_regex]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-regex]
    --unset-all           remove all matches: name [value-regex]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config -l --global
user.email=mhso.developer@gmail.com
credential.helper=manager

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config -l --global
user.email=mhso.developer@gmail.com
credential.helper=manager

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config --global user.email 'gangtai.goh@gmail.com'

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config --global user.^Cgangtai.goh@gmail.com'

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config --global user.name 'gangtai goh'

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git config -l --global
user.email=gangtai.goh@gmail.com
user.name=gangtai goh
credential.helper=manager

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l ~/.gitconfig
-rw-r--r-- 1 BIT 197121 89 Nov 30 13:26 /c/Users/BIT/.gitconfig

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l ~/.gitconfig
-rw-r--r-- 1 BIT 197121 89 Nov 30 13:26 /c/Users/BIT/.gitconfig

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ cat ~/.gitconfig
[user]
        email = gangtai.goh@gmail.com
        name = gangtai goh
[credential]
        helper = manager

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git branch

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ nano hello.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l
total 1
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ cat hello.txt
안녕하세요. 리눅스!
처음만나 반가와요.
git을 사용해 보아요.


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ cat hello.txt
안녕하세요. 리눅스!
처음만나 반가와요.
git을 사용해 보아요.


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ nano hello2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l
total 2
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:33 hello2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ cat hello2.txt
hello,,,
git,,,

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.txt
        hello2.txt

nothing added to commit but untracked files present (use "git add" to track)

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git add hello.txt hello2.txt ^C

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git add hello.txt hello2.txt
warning: LF will be replaced by CRLF in hello.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in hello2.txt.
The file will have its original line endings in your working directory

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.txt
        new file:   hello2.txt


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git commit
[master (root-commit) 851b8bb] 파일2개 입력!
 2 files changed, 6 insertions(+)
 create mode 100644 hello.txt
 create mode 100644 hello2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
nothing to commit, working tree clean

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git log
commit 851b8bbd5bfd431a836a577d144145e7295f4496 (HEAD -> master)
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:38:50 2020 +0900

    파일2개 입력!

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ nano newfile.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        newfile.txt

nothing added to commit but untracked files present (use "git add" to track)

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l
total 3
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:33 hello2.txt
-rw-r--r-- 1 BIT 197121 41 Nov 30 13:43 newfile.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ nano newfile2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        newfile.txt
        newfile2.txt

nothing added to commit but untracked files present (use "git add" to track)

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git add newfile.txt
warning: LF will be replaced by CRLF in newfile.txt.
The file will have its original line endings in your working directory

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   newfile.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        newfile2.txt


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git commit -m 'newfile 테스트'
[master b358f58] newfile 테스트
 1 file changed, 1 insertion(+)
 create mode 100644 newfile.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git log
commit b358f586874b8f80b879c4b0168fbc6ed9e694af (HEAD -> master)
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:46:34 2020 +0900

    newfile 테스트

commit 851b8bbd5bfd431a836a577d144145e7295f4496
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:38:50 2020 +0900

    파일2개 입력!

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        newfile2.txt

nothing added to commit but untracked files present (use "git add" to track)

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git add .
warning: LF will be replaced by CRLF in newfile2.txt.
The file will have its original line endings in your working directory

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git add .

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   newfile2.txt


BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git commit -m 'file2'
[master 3d66597] file2
 1 file changed, 1 insertion(+)
 create mode 100644 newfile2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git log
commit 3d66597aea43ee9fc644fad2caf2511836030949 (HEAD -> master)
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:50:09 2020 +0900

    file2

commit b358f586874b8f80b879c4b0168fbc6ed9e694af
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:46:34 2020 +0900

    newfile 테스트

commit 851b8bbd5bfd431a836a577d144145e7295f4496
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:38:50 2020 +0900

    파일2개 입력!

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -al
total 24
drwxr-xr-x 1 BIT 197121  0 Nov 30 13:44 ./
drwxr-xr-x 1 BIT 197121  0 Nov 30 13:26 ../
drwxr-xr-x 1 BIT 197121  0 Nov 30 13:50 .git/
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:33 hello2.txt
-rw-r--r-- 1 BIT 197121 41 Nov 30 13:43 newfile.txt
-rw-r--r-- 1 BIT 197121 15 Nov 30 13:44 newfile2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git checkout HEAD
~
BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ git checkout HEAD~2
Note: switching to 'HEAD~2'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 851b8bb 파일2개 입력!

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git ((851b8bb...))
$ ls -l
total 2
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:33 hello2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git ((851b8bb...))
$ git log
commit 851b8bbd5bfd431a836a577d144145e7295f4496 (HEAD)
Author: gangtai goh <gangtai.goh@gmail.com>
Date:   Mon Nov 30 13:38:50 2020 +0900

    파일2개 입력!

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git ((851b8bb...))
$

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git ((851b8bb...))
$ git checkout master
Previous HEAD position was 851b8bb 파일2개 입력!
Switched to branch 'master'

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
$ ls -l
total 4
-rw-r--r-- 1 BIT 197121 84 Nov 30 13:30 hello.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:33 hello2.txt
-rw-r--r-- 1 BIT 197121 42 Nov 30 13:52 newfile.txt
-rw-r--r-- 1 BIT 197121 16 Nov 30 13:52 newfile2.txt

BIT@DESKTOP-MFM72BP MINGW64 ~/my-git (master)
```
