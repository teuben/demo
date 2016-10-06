# demo

members can hack away if they want to test git features 

testing 1 2 3

If we're lucky, documentation from the gh-pages branch on https://astroumd.github.io/demo/

## GIT for CVS users

In cvs you would
```
     cvs checkout URL
     cvs update
     
     cvs commit FILE
```
but this simple but direct commit back to the server is a two stage process in GIT:
```
     git clone URL
     git pull
     
     git commit FILE
     git push
```
If everybody behaves you can almost now live with git, much like you did with CVS.
     

## Some comments on using git

* Some common and recommended workflows can be found in the *git.txt* document

* a ***git clone*** does not preserve original timestamps (which e.g. CVS does). See   http://stackoverflow.com/questions/2179722/checking-out-old-file-with-original-create-modified-timestamps for some comments on this

* a ***git add*** of a new directory tree convieniently adds the whole tree, so ***git commit** will then commit the whole tree.

* After a ***git clone*** it doesn't seem to see other branches until you've been there?   (***git branch -r*** will list remote branches)

* If you delete a file, git will be upset. ***git checkout -- file***

