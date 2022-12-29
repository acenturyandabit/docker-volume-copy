# Docker Volume Copy

Bash script that allows to make a copy of exists volume to new one with a new name.

**Step 1**

Copy script to where you want use it

```
$ curl https://raw.githubusercontent.com/KOYU-Tech/docker-volume-copy/main/dvc.sh -o dvc.sh && chmod +x dvc.sh
```

**Step 2**

Check the correct name of exists volume by ```$ docker volume ls```

**Step 3**

Imagine a new volume name and use it with script

```
$ ./dvc.sh old-volume-name new-volume-name-that-better-than-previous
```

Press "Enter" and wait.

**Step 4**

Go back to Github and give us a star 😅