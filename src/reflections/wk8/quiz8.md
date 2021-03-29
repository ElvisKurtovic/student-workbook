# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
@vue/cli
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Connections Strings
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Log retrieval via the web dashboard

Or through the command line
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
git pull origin master
git add .
git commit -am "pre-heroku"
git push heroku master
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Helps software development teams work in parallel. It separates out “in-progress work” from tested and stable code.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code reviews should happen after automated checks (tests, style, other CI) have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
git merge
```
