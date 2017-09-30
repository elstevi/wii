## Auto deploy git repo
### Syntax
```
git --git-dir=<repo>/.git pull -f <remote> <branch>
```

### Example
```
*/15 * * * * /usr/local/bin/git --git-dir=/usr/local/www/wiki/.git pull -f github-ssh master
```
