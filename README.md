# OpenCERT website
A place to build a website for OpenCERT Eclipse project

## Structure
When you use Hugo, static html website is generated in the /public folder. Here on Github, we need those files to be in the "gh-pages" branch.

So, we use a .gitignore to tell Git to ignore the "oublic" folder when we push on master. Then, "gh-pages" is configured as en orphan branch, and as a separate tree. This way we can use the hugo command, then go to "public", and commit/push directly in "gh-pages".

You can read Hugo documentation about how to use Github pages:  
https://gohugo.io/tutorials/github-pages-blog/

## see the website
Just go to:  
https://ttoine.github.io/opencert-website/
