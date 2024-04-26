This is a webpage template designed to make simple websites using rmarkdown and github.


To get started on your own webpage follow these instructions:



1. Open a terminal and clone my template webpage repository:

```git clone https://github.com/nearinj/Template_webpage.git```


2. Rename it the folder so that its named after your github username


``` mv Template_webpage USERNAME.github.io ```

If your github username is JTNearing-broad you would want to rename the folder to ```JTNearing-broad.github.io```


3. Next we need to remove the previous git tracking information from the folder we just cloned.

``` cd USERNAME.github.io```
``` rm -rf .git```


4. Initialize it as a new repository.

```git init```

5. Next we want commit our files to this new github project and commit them to the staging area.

``` git add . ```
``` git commit -m "First commit"```

6. Now we need to navigate to the github webpage and make a new resposity with the same name as the folder we just made.

7. Link your new repository to the folder that we created and push our changes.

``` git remote add origin https://github.com/USERNAME/USERNAME.github.io.git```
``` git push -u origin main```


8. Wait a few minutes and then navtigate to: ```USERNAME.github.io```
9. 







