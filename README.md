# Resources
Repo for all the class materials and tex files to render them.

# Working with Overleaf.com

1. Go to [OverLeaf](http://www.overleaf.com) and click on upload
2. Upload a template folder available in `Resources/template/template.zip` using the github extension. Note the web link (step 5).
3. On local machine `git pull` the `Resources` project
4. If you want to add a chapter to `class_9/science`, then from `Resources $`
        ```bash
        mkdir ./class_9/science/{project_name}
        ```
5. ` git submodule add --force https://git.overleaf.com/{overleaf_project_id} ./class_9/science/{project_name}`
    Where you can get the git link from the web link of the overleaf project. The project link is of format `http://www.overleaf.com/{overleaf_project_id}`.
6. `git pull`
7. start working locally and push to see the results on the webpage.
8. Remember to pull from origin everytime you start to work.

    

