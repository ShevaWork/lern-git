# learn about git and github LOGS

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519):
Could not create directory '/c/Users/\316\353\345\352\361\340\355\344\360/.ssh' (No such file or directory).
Enter passphrase for "/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Saving key "/c/Users/\316\353\345\352\361\340\355\344\360/.ssh/id_ed25519" failed: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): c:/tem

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): /c/temp
/c/temp already exists.
Overwrite (y/n)? y
Enter passphrase for "/c/temp" (empty for no passphrase):
Enter same passphrase again:
Saving key "/c/temp" failed: Is a directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): c/temp/ssh-key
Enter passphrase for "c/temp/ssh-key" (empty for no passphrase):
Enter same passphrase again:
Saving key "c/temp/ssh-key" failed: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ mkdir -p /c/temp/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com" -f /c/temp/ssh-key
Generating public/private ed25519 key pair.
Enter passphrase for "/c/temp/ssh-key" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/temp/ssh-key
Your public key has been saved in /c/temp/ssh-key.pub
The key fingerprint is:
SHA256:XeVtKqy5cb+qt8LzMqaIOsEmJ5wyYVCoi8otLn/xCYg olexandr.sheva@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
| o.           .  |
|o            o . |
|o           . . o|
|o.       . o   o |
|+=..    S . o .  |
|Eo* o      o .   |
|+*.. + . .+ .    |
|oo....o.  B+..   |
|oo++. . .ooO+oo. |
+----[SHA256]-----+

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): /c/Users\/лександр
[1]+  Stopped                 ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): /c/users/Олександр/.ssh/ed25519
Enter passphrase for "/c/users/Олександр/.ssh/ed25519" (empty for no passphrase):
Enter same passphrase again:
Saving key "/c/users/\320\236\320\273\320\265\320\272\321\201\320\260\320\275\320\264\321\200/.ssh/ed25519" failed: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ echo $userprofile


Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^[[200~echo $USERPROFILE
bash: $'\E[200~echo': command not found

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ echo $USERPROFILE
C:\Users\Олександр

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com" -f "$USERPROFILE/.ssh/ed25519"
Generating public/private ed25519 key pair.
Enter passphrase for "C:\Users\Олександр/.ssh/ed25519" (empty for no passphrase):
Enter same passphrase again:
Saving key "C:\\Users\\\320\236\320\273\320\265\320\272\321\201\320\260\320\275\320\264\321\200/.ssh/ed25519" failed: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/▒▒▒▒▒▒▒▒▒/.ssh/id_ed25519): $USERPROFILE/.ssh/id_ed25519
Enter passphrase for "$USERPROFILE/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Saving key "\033[A\033[B$USERPROFILE/.ssh/ed25519\033[D\033[D\033[D\033[D\033[D\033[D\033[Did_ed25519" failed: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ $ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com" -f "$USERPROFILE/.ssh/id_ed25519"
bash: $: command not found

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com" -f "$USERPROFILE/.ssh/id_ed25519"
Generating public/private ed25519 key pair.
C:\Users\Олександр/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase for "C:\Users\Олександр/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Saving key "C:\\Users\\\320\236\320\273\320\265\320\272\321\201\320\260\320\275\320\264\321\200/.ssh/id_ed25519" failed: Is a directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ssh-keygen -t ed25519 -C "olexandr.sheva@gmail.com" -f "$USERPROFILE/.ssh/ed25519"
Generating public/private ed25519 key pair.
Enter passphrase for "C:\Users\Олександр/.ssh/ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\Олександр/.ssh/ed25519
Your public key has been saved in C:\Users\Олександр/.ssh/ed25519.pub
The key fingerprint is:
SHA256:5Hqs5LdOUZF6oek59g9DJClFwNxO36CjYqR+6G9aZi4 olexandr.sheva@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|     o.+o ..     |
|      o.o.+.     |
|      .o+*o+     |
|    .  +B+o .    |
|   o   oS+.      |
|  . o .o=o       |
| . o+.o.+oo      |
|  E=oo +. .o     |
| .o*o ooo. ..    |
+----[SHA256]-----+

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ cd C:\Users\Олександр\Desktop\Corses\GIT
bash: cd: C:UsersОлександрDesktopCorsesGIT: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ cd \C\Users\Олександр\Desktop\Corses\GIT
bash: cd: CUsersОлександрDesktopCorsesGIT: No such file or directory

Олександр@DESKTOP-8KSRVH2 MINGW64 ~
$ cd "C:\Users\Олександр\Desktop\Corses\GIT"

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ cd gitthree

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree
$ pwd
/c/Users/Олександр/Desktop/Corses/GIT/gitthree

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree
$ git status
fatal: not a git repository (or any of the parent directories): .git

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree
$ git init
Initialized empty Git repository in C:/Users/Олександр/Desktop/Corses/GIT/gitthree/.git/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git commit -am "create index"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git add index.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git commit -am "create index"
[master (root-commit) f9a502e] create index
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git branch
* master

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (master)
$ git branch -M main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git branch
* main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git remote -v

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git remote add origrn https://github.com/ShevaWork/lern-git.git

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git remote -v
origrn  https://github.com/ShevaWork/lern-git.git (fetch)
origrn  https://github.com/ShevaWork/lern-git.git (push)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push origrn main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 587 bytes | 587.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ShevaWork/lern-git.git
 * [new branch]      main -> main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git add index.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ got commit -m "add <p> in index"
bash: got: command not found

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git commit -m "add <p> in index"
[main eada91f] add <p> in index
 1 file changed, 2 insertions(+), 1 deletion(-)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git remote -v
origrn  https://github.com/ShevaWork/lern-git.git (fetch)
origrn  https://github.com/ShevaWork/lern-git.git (push)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origrn main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ ^[[200~git push --set-upstream origrn main
bash: $'\E[200~git': command not found

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push -u origrn main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 455 bytes | 455.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ShevaWork/lern-git.git
   f9a502e..eada91f  main -> main
branch 'main' set up to track 'origrn/main'.

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git add index.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git commit -m "index add navbar"
[main 989e2a0] index add navbar
 1 file changed, 5 insertions(+)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ShevaWork/lern-git.git
   eada91f..989e2a0  main -> main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ ^C

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git add readme.md

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git commit -m "add readme"
[main 900c0f3] add readme
 1 file changed, 184 insertions(+)
 create mode 100644 readme.md

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.58 KiB | 1.58 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ShevaWork/lern-git.git
   989e2a0..900c0f3  main -> main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/gitthree (main)
$ cd ..

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ git clone https://github.com/ShevaWork/work_refresh.git
Cloning into 'work_refresh'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 9 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), 5.38 KiB | 1.35 MiB/s, done.

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/  work_refresh/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/  work_refresh/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ git clone https://github.com/ShevaWork/open-source.git
Cloning into 'open-source'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 10 (delta 1), reused 1 (delta 1), pack-reused 6 (from 1)
Receiving objects: 100% (10/10), done.
Resolving deltas: 100% (1/1), done.

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/  open-source/  work_refresh/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ ls
gitone/  gitthree/  gittwo/  open-source/  work_refresh/

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT
$ cd open-source

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ lc
bash: lc: command not found

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ pwd
/c/Users/Олександр/Desktop/Corses/GIT/open-source

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ git branch
* main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ git checkout -v footer
error: unknown switch `v'
usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>] -- <file>...

    -b <branch>           create and checkout a new branch
    -B <branch>           create/reset and checkout a branch
    -l                    create reflog for new branch
    --[no-]guess          second guess 'git checkout <no-such-branch>' (default)
    --[no-]overlay        use overlay mode (default)
    -q, --[no-]quiet      suppress progress reporting
    --[no-]recurse-submodules[=<checkout>]
                          control recursive updating of submodules
    --[no-]progress       force progress reporting
    -m, --[no-]merge      perform a 3-way merge with the new branch
    --[no-]conflict <style>
                          conflict style (merge, diff3, or zdiff3)
    -d, --[no-]detach     detach HEAD at named commit
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -f, --[no-]force      force checkout (throw away local modifications)
    --[no-]orphan <new-branch>
                          new unborn branch
    --[no-]overwrite-ignore
                          update ignored files (default)
    --[no-]ignore-other-worktrees
                          do not check if another worktree is using this branch
    -2, --ours            checkout our version for unmerged files
    -3, --theirs          checkout their version for unmerged files
    -p, --[no-]patch      select hunks interactively
    --[no-]ignore-skip-worktree-bits
                          do not limit pathspecs to sparse entries only
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (main)
$ git checkout -b footer
Switched to a new branch 'footer'

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$ git add footer.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$ git commit -m "add footer"
[footer 341d8a1] add footer
 1 file changed, 1 insertion(+)
 create mode 100644 footer.html

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$ git remote -v
origin  https://github.com/ShevaWork/open-source.git (fetch)
origin  https://github.com/ShevaWork/open-source.git (push)

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$ git branch
* footer
  main

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$ git push origin footer
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 365 bytes | 365.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'footer' on GitHub by visiting:
remote:      https://github.com/ShevaWork/open-source/pull/new/footer
remote:
To https://github.com/ShevaWork/open-source.git
 * [new branch]      footer -> footer

Олександр@DESKTOP-8KSRVH2 MINGW64 ~/Desktop/Corses/GIT/open-source (footer)
$
