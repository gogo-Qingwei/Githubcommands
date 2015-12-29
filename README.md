Creating a repository online for the <b>first time!</b>
```
$touch README.md
$git init
$git add README.md
$git commit -m "first commit"
$git push add origin
$git oush -u origin master
```
#put in username&passport
```
When adding on to your repository online with changes

$git add .
$git commit -m 'what has changed'
$git push origin master
```

### No more username & password input for every push

# How to delete a file
s
$git add .
$git add -u # when you have deleted a local file you want to remove from your repo


###working together from perspective of person

``` sh
#fork repo you want to work on
$git clone git@github.com:gogo-Qingwei/builderqing.github.io.git
 
```

# want to change files in local computer
$git pull
>>>>>>> b2bc03fcfeec658758d4f948fb55716b102a287a
```
#want to remove a file from online github repo but keep it in local
$git rm --cached localFileName
```

### want to remove a file from online github repo but keep it locally

```sh
$git rm --cached localFile
#add locanfilename to .gitignore file $ commit
```

```sh
$git reset --hard commitSHA------
#be back to any commit list in commitlist

#removing 3 commits from online repor

$git push -f origin HEAD----
```
// add really really stupid stuff