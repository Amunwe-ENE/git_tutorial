
username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.html


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ mkdir css

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.html


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ cd css/

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial/css (master)
$ touch style.css

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial/css (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ../hello.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial/css (master)
$ cd ..

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        css/


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git add css/

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   css/style.css
        new file:   hello.html


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git rm --cached css/style.css
rm 'css/style.css'

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hello.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        css/


username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git commit -m "Created landing page"
[master (root-commit) c4ea32b] Created landing page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hello.html

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        css/

nothing added to commit but untracked files present (use "git add" to track)

username@HP MINGW64 /c/Users/username/Desktop/Freelance/git_tutorial (master)
$ 

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        gitcommand.md

nothing added to commit but untracked files present (use "git add" to track)

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (master)
$ git remote -v

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (master)
$ git remote add origin git@github.com:Amunwe-ENE/git_tutorial.git

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (master)
$ git remote -v
origin  git@github.com:Amunwe-ENE/git_tutorial.git (fetch)
origin  git@github.com:Amunwe-ENE/git_tutorial.git (push)

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (master)
$ git branch -M main

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 219 bytes | 109.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Amunwe-ENE/git_tutorial.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Fredrika@HP MINGW64 /c/Users/Fredrika/Desktop/Freelance/git_tutorial (main)
$
