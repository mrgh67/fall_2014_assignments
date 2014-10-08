We will be using the <a href="https://help.github.com/articles/using-pull-requests#fork--pull">Fork and Pull</a> git model for submitting labs and some assignments.

For the first assignment:

1. Fork the assignments repo for the class:

2. clone the repo to your newly created Data Science Toolbox

```sh
vagrant@data-science-toolbox:~$git clone git@github.com:<yourgithubusername>/fall_2014_assignments.git
```

in `<yourgithubusername>/fall_2014_assignments/lab01`, make a directory with your first initial/full last name.

```sh
vagrant@data-science-toolbox:~$export DIR=<"flastname">
vagrant@data-science-toolbox:~$mkdir $DIR; cd <yourgithubusername>/fall_2014_assignments/lab01/$DIR;
```

With a text editor, create and save a markdown file with the following content:

* Your name and what you do
* One liner about your coding and math background
* Any social web you use and don't mind sharing (e.g. linkedin, twitter)
* A data blog post you read recently for sharing with the class
create a branch of the repository with a unique name, and then commit to that repo

```sh
git checkout -b my_name_class_1
git add .
git commit -m 'my first git commit!'
git push origin my_name_class_1
```

Add a pull request. This is the actual submission of your work. You can do this on github by finding your branch and clicking "Create pull request." Developers, feel free to use some command line tool for this if you prefer it.

Again, a link to github documentation on the <a href="https://help.github.com/articles/using-pull-requests#fork--pull">Fork and Pull git model</a>.
