
Admin@DESKTOP-276840B MINGW64 ~
$ git --version
git version 2.51.0.windows.2

Admin@DESKTOP-276840B MINGW64 ~
$ mkdir git_project
mkdir: cannot create directory ‘git_project’: File exists

Admin@DESKTOP-276840B MINGW64 ~
$ git --project
unknown option: --project
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy
-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envva
r>]
           <command> [<args>]

Admin@DESKTOP-276840B MINGW64 ~
$ git --project
unknown option: --project
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy
-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envva
r>]
           <command> [<args>]

Admin@DESKTOP-276840B MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 DSA
 Desktop/
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Microsoft/
 Music/
'My Documents'@
 NM_mern_stack_E-Commerce_application/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Tracing/
 Untitled-2.py
 Untitled.ipynb
 Videos/
 anaconda3/
 clone.html
'coding basics.py'
 edb_mtk.exe*
 edb_npgsql.exe*
 edb_pem_agent.exe*
 edb_pem_agent_8.exe*
 edb_pem_server.exe*
 edb_pem_server_8.exe*
 edb_pgagent_pg17.exe*
 edb_pgbouncer.exe*
 edb_pgjdbc.exe*
 edb_psqlodbc.exe*
 edb_psqlodbc.exe-20250302110749*
 edb_psqlodbc.exe-20250302110848*
 edb_psqlodbc.exe-20250302110852*
 edb_sqlprofiler_pg17.exe*
 edb_xdb_62.exe*
 edb_xdb_7.exe*
'flask api'
 git_project/
 html
 index.html
 mentalmentor/
 newproj/
 node_modules/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 one.html
 package-lock.json
 package.json
 pemhttpd.exe*
 postgis_3_5_pg17.exe*
 postgresql_13.exe*
'python foundation.ipynb'
 sample.py
 trial.py
'{'

Admin@DESKTOP-276840B MINGW64 ~
$ cd git_project

Admin@DESKTOP-276840B MINGW64 ~/git_project
$ ^C

Admin@DESKTOP-276840B MINGW64 ~/git_project
$ ^C

Admin@DESKTOP-276840B MINGW64 ~/git_project
$ git init -b main
Initialized empty Git repository in C:/Users/Admin/git_project/.git/

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git init -b main
warning: re-init: ignored --initial-branch=main
Reinitialized existing Git repository in C:/Users/Admin/git_project/.git/

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ ls

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ echo "writing the first line in new file">> report.doc

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        report.doc

nothing added to commit but untracked files present (use "git add" to track)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        report.doc

nothing added to commit but untracked files present (use "git add" to track)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ cat report.doc
writing the first line in new file

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        report.doc

nothing added to commit but untracked files present (use "git add" to track)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ cat report.doc
writing the first line in new file

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$


/////Day 2 //////



Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        report.doc

nothing added to commit but untracked files present (use "git add" to track)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git config --global user.name "keerthana-ship-it"

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ ls
report.doc

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git config --global user.email "keerthanabuis03@gmail.com"

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git add report.doc
warning: in the working copy of 'report.doc', LF will be replaced by CRLF the ne
xt time Git touches it

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   report.doc


Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git commit -m " created a new file - first commit"
[main (root-commit) fb443d5]  created a new file - first commit
 1 file changed, 1 insertion(+)
 create mode 100644 report.doc

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main
nothing to commit, working tree clean

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git log
commit fb443d5448304f4dff1b4bd143d105185a18aff1 (HEAD -> main)
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:12:34 2026 +0530

     created a new file - first commit

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ echo "updating the  file........- second line ">> report.doc

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ cat report.doc
writing the first line in new file
updating the  file........- second line

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   report.doc

no changes added to commit (use "git add" and/or "git commit -a")

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git add report.doc
warning: in the working copy of 'report.doc', LF will be replaced by CRLF the ne
xt time Git touches it

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   report.doc


Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git log
commit fb443d5448304f4dff1b4bd143d105185a18aff1 (HEAD -> main)
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:12:34 2026 +0530

     created a new file - first commit

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git commit -m " added new line --- second commit "
[main 8f2c238]  added new line --- second commit
 1 file changed, 1 insertion(+)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git status
On branch main
nothing to commit, working tree clean

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git log
commit 8f2c2387b20f30b5a4fd07013d7b357fef1ed2bd (HEAD -> main)
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:41:38 2026 +0530

     added new line --- second commit

commit fb443d5448304f4dff1b4bd143d105185a18aff1
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:12:34 2026 +0530

     created a new file - first commit

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ ^C

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git commit -m"added second line"
On branch main
nothing to commit, working tree clean

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git log
commit 8f2c2387b20f30b5a4fd07013d7b357fef1ed2bd (HEAD -> main)
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:41:38 2026 +0530

     added new line --- second commit

commit fb443d5448304f4dff1b4bd143d105185a18aff1
Author: keerthana-ship-it <keerthanabuis03@gmail.com>
Date:   Tue Jan 13 21:12:34 2026 +0530

     created a new file - first commit

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git remote add origin "https://github.com/keerthana-ship-it/project_smartapp_k.git"

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git remove -v
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
        remote

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git remote -v
origin  https://github.com/keerthana-ship-it/project_smartapp_k.git (fetch)
origin  https://github.com/keerthana-ship-it/project_smartapp_k.git (push)

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 549 bytes | 61.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/keerthana-ship-it/project_smartapp_k.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Admin@DESKTOP-276840B MINGW64 ~/git_project (main)
$
