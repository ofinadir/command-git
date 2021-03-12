# Git
macam-macam fungsi git

## Git Command
* git help

* git init

* git add <file(s)>

* git status

* git commit

* git config

### git branch
* git branch. : melihat dan membuat branch.
* git branch -d [nama branch] : menghapus branch

### git merge
terdiri dari 2 jenis merge yaitu:
1. fast forward merge
2. three way merge 'recursive' : apabila tidak ada direct path, istilaha lain ~merge commit, merge sambil commit
* git merge : menggabung branch
* git --merged : mengecek branch yang sudah tergabung

### git checkout
* git checkout [nama branch] : pindah branch
* git checkout : kembali ke sebuah commit. contoh, git checkout [5 digit hash] -- [file]

### git log
* git log. contoh: git log -3 (melihat 3 log terakhir), 
* menampilkan graph: git log --all --decorate --oneline --graph


## peritah shell
alias [nama]="command"
..lain-lain
