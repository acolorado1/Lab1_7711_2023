# Laboratory 1: 7711 Fall 2023 

The purpose of this lab is to introduce you to practical tips and tricks when using ggplot and tidy data for creation of clean, informative, reproducible visualizations. 

## Getting Started with Github 

At this stage we're going to get a local copy of the Github repo and create our own branches that we will work in respectively. 

+ Go to a local directory in terminal 
+ Clone Github repo: https://github.com/acolorado1/Lab1_7711_2023.git
+ Go into local repo 
+ Make sure you are on the *main* branch
+ Make a branch named: FirstLast_lab1
+ Check that you are on the the new branch 

```
cd File/Path/On/Your/Computer 
git clone https://github.com/acolorado1/Lab1_7711_2023.git
cd Lab1_7711_2023
git branch -a 
git checkout -b FirstLast_lab1
git branch -a
```

Next in the file **GithubPractice.R** add a comment such as: *"Sofia Colorado was here"*

Now we create and push our changes to the remote version of the branch in Github. I as the owner of the repo will pull and merge them together. 

```
git add GithubPractice.R
git commit -m "commit message here" 
git push -u origin BranchName [e.g.,FirstLast_lab1]
```

To update your local repository

+ go to main branch on your computer
+ pull from remote repository

```
git checkout main 
git pull origin main 
```

## Let's look at some R scripts 

If you want to follow along, the script I will be going through is **Examples.R**

If you want to render your markdown into html for easier visualization, just press *knit* at the top in Rstudio. 

## Practice 

Open **Practice.R**. Each group will be assigned two problems, and each person should code the solution for one. 

Please collaborate with your partner. As you develop your figure ask their opinion and try to incorporate some changes they suggest. 