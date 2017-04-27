Git setup

# IF IN PAIRS #

#### _First, set up your pairs file_ ####

Touch .pairs file in the home directory, paste in pair text

    pairs:
      al: Ada Lovelace
      edlf: Enrique de la Fuente
    email:
      al: adanator@me.com
      edlf: queenrique@gmail.com

  2. $ git init to initialize repository in current folder path
  3. $ git pair [initials] [initials]
  4. $ git add [filename], or $git add . (to add all files)
  5. $ git-pair-commit -m"note"
  6. Create git hub repository or use existing, copy repository URL
  7. $ git remote add [any name for repository] [repository URL]
  8. $ git push [your name for repository] master

# IF SOLO #

#### _First, configure your user name and email_ ####

$ git config --global user.name "Padma Patil"
$ git config --global user.email padma@email.com

2. $ git init to initialize repository in current folder path
3. $ git add [filename], or $git add . (to add all files)
4. $ git commit -m"note"
5. create git hub repository or use existing
6. $ git remote add [any name for repository] [repository URL]
7. $ git push [your name for repository] master

# Git Branches #

$ git branch (view branch names)
$ git branch [new branch name] (to create new branch)
$ git checkout [branch name] (to go to branch)
$ git merge [branch name] (to merge to current branch)

End
