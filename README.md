# my-first-progect.
UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git init
Reinitialized existing Git repository in C:/Users/UA/.git/

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git status
warning: could not open directory 'Application Data/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Local Settings/': Permission denied
warning: could not open directory 'My Documents/': Permission denied
warning: could not open directory 'NetHood/': Permission denied
warning: could not open directory 'PrintHood/': Permission denied
warning: could not open directory 'Recent/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
warning: could not open directory 'Start Menu/': Permission denied
warning: could not open directory 'Templates/': Permission denied
On branch development
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   example.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .bash_history
        .cache/
        .gitconfig
        .idlerc/
        .lesshst
        .oracle_jre_usage/
        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        IntelGraphicsProfiles/
        Links/
        Music/
        NTUSER.DAT
        NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TM.blf
        NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer000000000000
00000001.regtrans-ms
        NTUSER.DAT{1c3790b4-b8ad-11e8-aa21-e41d2d101530}.TMContainer000000000000
00000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Videos/
        dsp_stereo_tool.ini
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini
        source/


UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git add example.txt
fatal: Unable to create 'C:/Users/UA/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git add
fatal: Unable to create 'C:/Users/UA/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git rm example.txt
fatal: Unable to create 'C:/Users/UA/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git commit -m 'removed file'
fatal: Unable to create 'C:/Users/UA/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git checkout -b development
fatal: a branch named 'development' already exists

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git merge master development
Already up to date.

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$ git log
commit 5cc3e018fd45f47d327254a233686db851b7e5d6 (HEAD -> development, master)
Author: Денис <rudnikdenis80@gmail.com>
Date:   Wed Oct 1 20:51:45 2025 +0300

    removed file

commit 80c64476f0315395ac9b408387649448555003e1
Author: Денис <rudnikdenis80@gmail.com>
Date:   Wed Oct 1 20:49:05 2025 +0300

    Added file

UA@DESKTOP-MACJE8F MINGW64 ~ (development)
$

