# HelloWorld
First Repo


## BFG

BFG does not clean the Current HEAD!!! 

git clone --mirror https//Repo

git gc

java -jar bfg-1.14.0.jar --strip-blobs-bigger-than 100M repo.git

git reflog expire --expire=now --all && git gc --prune=now --aggressive

