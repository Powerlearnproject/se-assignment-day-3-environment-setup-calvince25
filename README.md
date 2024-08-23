# se-assignment-day-3-environment-setup-calvince25

PC@calvince MINGW64 /
$ git init
Initialized empty Git repository in C:/Program Files/Git/.git/

PC@calvince MINGW64 / (master)
$ echo "# se-assignment-day-3-environment-setup-calvince25" >> README.md

PC@calvince MINGW64 / (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

PC@calvince MINGW64 / (master)
$ git commit -m "First commit"
[master (root-commit) 58ddb23] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

PC@calvince MINGW64 / (master)
$ git branch -M main

PC@calvince MINGW64 / (main)
$ git remote add origin https://github.com/PowerLearnProject/se-assignment-day-3-environment-setup-calvince25.git

PC@calvince MINGW64 / (main)
$ git remote set-url
usage: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    --[no-]push           manipulate push URLs
    --[no-]add            add URL
    --[no-]delete         delete URLs


PC@calvince MINGW64 / (main)
$ ^C

PC@calvince MINGW64 / (main)
$ git remote set-url https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-calvince25.git
usage: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    --[no-]push           manipulate push URLs
    --[no-]add            add URL
    --[no-]delete         delete URLs


PC@calvince MINGW64 / (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 280.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: This repository moved. Please use the new location:
remote:   https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-calvince25.git
To https://github.com/PowerLearnProject/se-assignment-day-3-environment-setup-calvince25.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
