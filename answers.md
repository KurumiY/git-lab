Answer1 git version 2.30.0.windows.2
Answer2 diff.astextplain.textconv=astextplain
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
        credential.helper=manager-core
        credential.https://dev.azure.com.usehttppath=true
        init.defaultbranch=master
        user.name=Kurumi Yamada
        user.email=ky141817@ohio.edu
Answer3 usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

        These are common Git commands used in various situations:

        start a working area (see also: git help tutorial)
        clone             Clone a repository into a new directory
        init              Create an empty Git repository or reinitialize an existing one

        work on the current change (see also: git help everyday)
        add               Add file contents to the index
        mv                Move or rename a file, a directory, or a symlink
        restore           Restore working tree files
        rm                Remove files from the working tree and from the index
        sparse-checkout   Initialize and modify the sparse-checkout

        examine the history and state (see also: git help revisions)
        bisect            Use binary search to find the commit that introduced a bug
        diff              Show changes between commits, commit and working tree, etc
        grep              Print lines matching a pattern
        log               Show commit logs
        show              Show various types of objects
        status            Show the working tree status

        grow, mark and tweak your common history
        branch            List, create, or delete branches
        commit            Record changes to the repository
        merge             Join two or more development histories together
        rebase            Reapply commits on top of another base tip
        reset             Reset current HEAD to the specified state
        switch            Switch branches
        tag               Create, list, delete or verify a tag object signed with GPG

        collaborate (see also: git help workflows)
        fetch             Download objects and refs from another repository
        pull              Fetch from and integrate with another repository or a local branch
        push              Update remote refs along with associated objects

        'git help -a' and 'git help -g' list available subcommands and some
        concept guides. See 'git help <command>' or 'git help <concept>'
        to read about a specific subcommand or concept.
        See 'git help git' for an overview of the system.
Answer4 On branch master

        No commits yet

        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                README.md
                answers.md

        nothing added to commit but untracked files present (use "git add" to track)
Answer5 On branch master

        No commits yet

        Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
                new file:   README.md

        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                answers.md
Answer6 On branch master
        Changes to be committed:
        (use "git restore --staged <file>..." to unstage)
                new file:   answers.md
Answer7 On branch master
        nothing to commit, working tree clean
Answer8 commit 1f1b7178be1d267fb6765f0b2449a4ea9b6c9cf6 (HEAD -> master)
        Author: Kurumi Yamada <ky141817@ohio.edu>
        Date:   Tue Jan 26 19:09:01 2021 -0500

            initial commit

        commit 5ae5ca50224583ef2b7cff150c24da6b7d6a380e
        Author: Kurumi Yamada <ky141817@ohio.edu>
        Date:   Tue Jan 26 18:54:22 2021 -0500

            Initial commit
Answer9 info: please complete authentication in your browser...
        Enumerating objects: 6, done.
        Counting objects: 100% (6/6), done.
        Delta compression using up to 12 threads
        Compressing objects: 100% (5/5), done.
        Writing objects: 100% (6/6), 2.32 KiB | 2.32 MiB/s, done.
        Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
        To https://github.com/KurumiY/git-lab.git
        * [new branch]      main -> main
        Branch 'main' set up to track remote branch 'main' from 'origin'.
        On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Answer10 No
Answer11 To https://github.com/KurumiY/git-lab.git
        ! [rejected]        main -> main (fetch first)
        error: failed to push some refs to 'https://github.com/KurumiY/git-lab.git'
        hint: Updates were rejected because the remote contains work that you do
        hint: not have locally. This is usually caused by another repository pushing
        hint: to the same ref. You may want to first integrate the remote changes
        hint: (e.g., 'git pull ...') before pushing again.
        hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer12 To https://github.com/KurumiY/git-lab.git
        ! [rejected]        main -> main (fetch first)
        error: failed to push some refs to 'https://github.com/KurumiY/git-lab.git'
        hint: Updates were rejected because the remote contains work that you do
        hint: not have locally. This is usually caused by another repository pushing
        hint: to the same ref. You may want to first integrate the remote changes
        hint: (e.g., 'git pull ...') before pushing again.
        hint: See the 'Note about fast-forwards' in 'git push --help' for details.
        PS C:\Users\ky031\Desktop\cs2400\labs\git-lab> git pull
        remote: Enumerating objects: 5, done.
        remote: Counting objects: 100% (5/5), done.
        remote: Compressing objects: 100% (3/3), done.
        remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
        Unpacking objects: 100% (3/3), 702 bytes | 39.00 KiB/s, done.
        From https://github.com/KurumiY/git-lab
        1f1b717..2833e23  main       -> origin/main
        Updating 1f1b717..2833e23
        Fast-forward
        README.md | Bin 58 -> 53 bytes
        1 file changed, 0 insertions(+), 0 deletions(-)
Answer13   Directory: C:\Users\ky031\Desktop\cs2400\labs\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         1/26/2021   7:47 PM            302 .gitignore
-a----         1/26/2021   7:47 PM             11 README.md



