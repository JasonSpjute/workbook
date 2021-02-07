# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It holds various metadata relevant to the project. It also hold's the project dependancies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The top level, so it will be recognized by heroku
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Environment variables
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can get them via the CLI by using the $ heroku logs command. You can also use your heroku dashboard and select "view logs"
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Heroku will be monitoring the main branch of your github, so all you have to do is push to that branch and it will update automatically.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It is important to branch so that nothing get's deployed until it's tested and ready to go. This ensures that you have a functioning app up until you are ready to push the next version.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Prior to pushing to the main branch
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
