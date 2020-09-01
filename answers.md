1. git version 2.28.0.windows.1
2.  diff.astextplain.textconv=astextplain
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    pull.rebase=false
    credential.helper=manager
    core.editor="C:\Users\Anthony\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
    user.name=Anthony D'Alessandro
    user.email=AA442317@ohio.edu
3. It opens an html file in my browser explaining the command.
4.  On branch master

    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

    nothing added to commit but untracked files present (use "git add" to track)
5.  On branch master

    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
        new file:   README.md

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        answers.md
6. On branch master

    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
7.  [master (root-commit) c8bb265] Initial commit
    2 files changed, 20 insertions(+)
     create mode 100644 README.md
     create mode 100644 answers.md
    PS C:\Users\Anthony\OneDrive - Ohio University\Junior Year (2020-2021)\CS2400\git-lab> git status
    On branch master
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
8.  commit c8bb265edf5a46413f676bf38b38c9890a4ab1aa (HEAD -> master)
    Author: Anthony D'Alessandro <AA442317@ohio.edu>
    Date:   Tue Sep 1 16:31:51 2020 -0400

    Initial commit
9.  On branch master
    Your branch is up to date with 'origin/master'.

    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
            modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
10. No they are how they were before.
11. To https://github.com/adalessandro42/git-lab.git
     ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/adalessandro42/git-lab.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12. Yes, they are updated with the class info.
13. PS C:\Users\Anthony\OneDrive - Ohio University\Junior Year (2020-2021)\CS2400\git-lab-2> ls -hidden


    Directory: C:\Users\Anthony\OneDrive - Ohio University\Junior Year (2020-2021)\CS2400\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
da-h-l          9/1/2020   4:48 PM                .git