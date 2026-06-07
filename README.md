$ ls -la /workspace
$ ls -la /workspace
total 16
drwxrwxr-x 3 root root 4096 Jun  7 15:19 .
drwxr-xr-x 1 root root 4096 Jun  7 15:19 ..
drwxr-xr-x 8 root root 4096 Jun  7 15:38 .git
-rw-r--r-- 1 root root  156 Jun  7 15:19 README.md
$ cat /workspace/README.md
$ cat /workspace/README.md
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/RCordeiro7/Camila.git
git push -u origin main
$ git -C /workspace remote -v
git -C /workspace remote -v
