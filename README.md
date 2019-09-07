The DIY Blogger blog (based on Hugo Static Site Generator)

Running Locally
----------------

```$ hugo server -D```




Saving and Publishing your updates
-----------------------

from the /blog folder, run the following:

``` 
$ git status
```

add any new files added:

```
$ git add <filepath>
```

save your changes
```
$ git commit -a -m "<what you changed>"
$ git push
```

deploy all latest updates
```
$ ./deploy.sh 
```


To test this Github Deploy locally, you can run the following in your hugo site
------------------------

```
TARGET_REPO=travellingsky/travellingsky.github.io action.sh
```


Viewing your updates live
-------------------------

Once the deploy script has run, the website should update within a few seconds.

Go to https://www.skytravelblogger.com/ to view the latest published website.


