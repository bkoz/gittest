Getting started with github

mkdir gittest
git init
vi README.txt
git add README.txt

git remote add origin git@github.com:bkoz/gittest.git
git push origin master
git push -u origin master


[koz@courante gittest]$ vim README.txt 
[koz@courante gittest]$ git commit README.txt -m "new"
[master 9729f4a] new
 1 files changed, 8 insertions(+), 0 deletions(-)
[koz@courante gittest]$ git push
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To git@github.com:bkoz/gittest.git
   c8117df..9729f4a  master -> master
[koz@courante gittest]$ 


