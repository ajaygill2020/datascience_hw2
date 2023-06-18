# homeworkTwo

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:ajaygill2020/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named homeworkTwo, then do;

```bash
git remote add origin git@github.com:ajaygill2020/homeworkTwo.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── homeworkTwo	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───logs						<- Here, you will find the necessary logs
		│
		├───docs
		│      └───whatIf.py						<- Here is the python file that has important functions for us to use.
        └───aap_hw2__excel_python_s23_docx						<- Here is the instructions for the assignment.     
		│
		└───output


Documentation
--------------

This assignment contains two types of analyses done in Python using data from .csv files. 


