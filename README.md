# git-commands


set the pull and push urls


### Set the primary URL (used for fetch, usually SSH):

```
git remote set-url origin git@github.com:your-user/your-repo.git
```

### Add the second URL (used for pushing, usually HTTPS):

```
git remote set-url --add --push origin https://github.com/your-user/your-repo.git
```

### Check urls

```
git remote -v
```
