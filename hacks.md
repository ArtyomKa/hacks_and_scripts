# Linux

Mount win folder on linux:
```
mount -t cifs //192.168.100.200/alg /mnt/alg_on_100_200 -o user=admin,pass=Pic72688,ro,file_mode=0555,dir_mode=0555,uid=yohai,gid=yohai
```

Mount linux remote linux folder:
```
```

# Docker
Prevent path conversion on windows
```
export COMPOSE_CONVERT_WINDOWS_PATHS=0
```

# Git
Set current branch to track a remote:
```
git branch -u upstream/foo
```

