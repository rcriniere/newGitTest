# Session 3 
## *First steps*

### **Change Directory to cloned repo directory**
cd c:temper\newgittest

### **open VS code**
* code .
* git pull

### **Create a new file**
new-item -name 'rc-session'.md -Type File


## Merge feature branch into master

* git checkout master
* git pull origin maser
* git merge test
*     if issues persist - git merge --no-ff <feature branch>
* git push origin master



## Next session - covering pull request

### Create Pull Request 
*git request-pull master -p ./