# Crypto_Analysis Documentation
## JupyterLab files
- crypto_arbitrage.ipynb
This file demonstrates how to collect, prepare and analyze the data of bitcoin transactions between Jan to March 2018 from two exchanges - bitstamp and coinbase using JupyterLab.
- Resources/bitstamp.csv
This file contains trading data of bitcoin from bitstamp exchange. 
- Resources/coinbase.csv
This file contains trading data of bitcoin from coinbase exchange. 

## Git and terminal commands
nayan@NayanaWork MINGW64 ~
$ cd Fintech-Workspace/Challenge/
(base)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ conda activate dev
(dev)
### Create Repo

Created a repo via Github UI and clone to local
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ git clone https://github.com/nayananarayananp/Crypto_Analysis.git
Cloning into 'Crypto_Analysis'...
warning: You appear to have cloned an empty repository.
(dev)
```
### Switch to local git repo called Crypto_Arbitrage
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge
$ cd Crypto_Analysis/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ ls
crypto_arbitrage.ipynb  README.md  Resources/
(dev)

```

### Organize folders in starter code
Checked git status showing the organized starter code
```
$ git status
On branch master

```

### Add starter code files to git
```
No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        .ipynb_checkpoints/
        README.md
        Resources/
        crypto_arbitrage.ipynb

nothing added to commit but untracked files present (use "git add" to track)
(dev)
```

### Check the files got added
```
$ git status
On branch master
No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md
        Resources/
        crypto_arbitrage.ipynb

nothing added to commit but untracked files present (use "git add" to track)
nothing added to commit but untracked files present (use "git add" to track)
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ cd Resources/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis/Resources (main)
$ ls
bitstamp.csv  coinbase.csv
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis/Resources (main)
$ cd ..
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ ls
crypto_arbitrage.ipynb  README.md  Resources/
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git add *
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   Resources/bitstamp.csv
        new file:   Resources/coinbase.csv
        new file:   crypto_arbitrage.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git add .gitignore
warning: CRLF will be replaced by LF in .gitignore.
The file will have its original line endings in your working directory
(dev)
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   README.md
        new file:   Resources/bitstamp.csv
        new file:   Resources/coinbase.csv
        new file:   crypto_arbitrage.ipynb

(dev)
```

### Git commit
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git commit -m "Create Jupyter notebook for crypto analysis"
[main (root-commit) 98b334f] Create Jupyter notebook for crypto analysis
 5 files changed, 261483 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 Resources/bitstamp.csv
 create mode 100644 Resources/coinbase.csv
 create mode 100644 crypto_arbitrage.ipynb
(dev)
```
## Git push
Try pushing to github 
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 8.55 MiB | 2.94 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nayananarayananp/Crypto_Analysis.git
 * [new branch]      main -> main
(dev)
```
### Run program


Running the program with code completed
```
```

### Capture terminal history
```
nayan@NayanaWork MINGW64 ~/Fintech-Workspace/Challenge/Crypto_Analysis (main)
$ history 50 > terminal_history.txt
(dev)
```
Attached to [](./terminal_history.txt)

### Final commit and push