THIS IS A NEW FILE

digital001837@digital001837-XPS-15-9560:~$ git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialise an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
digital001837@digital001837-XPS-15-9560:~$ git config --global user.name"Connor Irvine"
error: invalid key: user.nameConnor Irvine
digital001837@digital001837-XPS-15-9560:~$ git config --global user.name"Connor Irvine"
error: invalid key: user.nameConnor Irvine
digital001837@digital001837-XPS-15-9560:~$ git config --global user.name "Connor.Irvine"
digital001837@digital001837-XPS-15-9560:~$ git config --global user.name "Connor Irvine"
digital001837@digital001837-XPS-15-9560:~$ git config --global user.email connor.irvine@hmrc.digital.gov.uk
digital001837@digital001837-XPS-15-9560:~$ mkdir git example 1
digital001837@digital001837-XPS-15-9560:~$ ls
1             Downloads             IdeaProjects        target
academy       example               Music               Templates
Applications  examples.desktop      Pictures            Videos
Desktop       git                   postinstall.sh.txt
Documents     idea-IC-163.15188.11  Public
digital001837@digital001837-XPS-15-9560:~$ mkdir gitexample1
digital001837@digital001837-XPS-15-9560:~$ ls
1             Downloads         idea-IC-163.15188.11  Public
academy       example           IdeaProjects          target
Applications  examples.desktop  Music                 Templates
Desktop       git               Pictures              Videos
Documents     gitexample1       postinstall.sh.txt
digital001837@digital001837-XPS-15-9560:~$ cg 
The program 'cg' is currently not installed. You can install it by typing:
sudo apt install cgvg
digital001837@digital001837-XPS-15-9560:~$ cd gitexample1
digital001837@digital001837-XPS-15-9560:~/gitexample1$ touch readme.txt
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git init
Initialized empty Git repository in /home/digital001837/gitexample1/.git/
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.txt

nothing added to commit but untracked files present (use "git add" to track)
digital001837@digital001837-XPS-15-9560:~/gitexample1$ vim readme.txt
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.txt

nothing added to commit but untracked files present (use "git add" to track)
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git add readme.txt
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   readme.txt

digital001837@digital001837-XPS-15-9560:~/gitexample1$ git commit-m "adding read me file to git"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
	commit-tree
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git commit -m "adding read me file to git"
[master (root-commit) 774f3d9] adding read me file to git
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt
digital001837@digital001837-XPS-15-9560:~/gitexample1$ git status
On branch master
nothing to commit, working tree clean
digital001837@digital001837-XPS-15-9560:~/gitexample1$ 

