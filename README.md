# github-lfs-example

```
$ cd github-lfs-example 
$ git lfs install
$ git lfs track "*.jpg" "*.jpeg" "*.png" "*.gif"
$ git add .gitattributes
$ git status
$ git commit -m "Enable Git LFS"
$ git push origin master
$ git status
$ git add .
$ git commit -m "Add an example picture"

1 file changed, 3 insertions(+)
create mode 100644 chia-seeds.jpg

$ git push origin master

Uploading LFS objects: 100% (1/1), 156 KB | 0 B/s, done.                                                                                                     
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 438 bytes | 438.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/jimthoburn/github-lfs-example.git
  ca46c7e..85d7dcb  master -> master
$
```
