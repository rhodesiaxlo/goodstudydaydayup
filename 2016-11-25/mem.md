# mem list
1. node.js toturial
2. npm install 
```
    cd %target_dir%
    npm init
    npm install %target_packet%
```
3.customerize xshell
    remapping home and end key
    customer shell command of `git add`, `git commit`, `git push`
    two way to store username and password in git

3.1.set credential.helper
```
    git config --global credential.helper store
````

3.2.user ssh key
remapping home and end key
    customer shell command of `git add`, `git commit`, `git push`
    two way to store username and password in git

3.2.1.set credential.helper
```
    git config --global credential.helper store
````

3.2.2.create ssh key ,add ssh private key to ssh agent ,add ssh key to github
```
ssh-keygen -t rsa -b 4096 -C %your_email%

eval "$(ssh-agent -s)"

```


