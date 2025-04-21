https://liaoxuefeng.com/books/git/introduction/index.html

init: init Repository
mkdir: Make directory
touch: touch filename.txt

pwd: PrintWorkingDirectory

add       add to stage
commit -m ""

status
diff -- filename

git checkout -- filename
git reset HEAD <filename>

rm "filename"
git rm filename	//modify

git checkout -- filename	//cancel

git branch dev + git checkout dev == git checkout -b dev //创建并切换到分支
git branch dev + git switch dev == git switch -c dev //创建并切换到分支

dev_insert

git branck dev //创建dev分支

git checkout dev/master  //切换到 dev/master分支
git switch dev/master  //切换到 dev/master分支 和 checkout效果一样，但是好理解

git merge dev //将 dev 合并到 当前分支
*****merge是把 master指针 直接指向 dev的提交，所以merge也叫“快进模式”

