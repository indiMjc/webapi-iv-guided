## Jargon

Single Responsibility Principle

Do one thing really well. Only one reason to change

## Deployment

- extract configuration into environment variables
- set up continuous deployment from Github to Heroku
  - connect heroku to github
    - create app
    - on `Deploy Tab`, select github and answer yes to security prompt
    - search for repo
    - pick branch to deploy
    - click `Enable Automatic Deploys`
    - click `Deploy Branch` button
  - commit and push to githubb
  - add start script to package.json
  - make the port dynamic

## Git Post-Lecture

- create new **empty** repository on GitHub
- `git remote rm origin`
- `git remote add origin url to our new repository
- `git add .
- `git commit -m "commit message"`
- `git push -u origin master` // sets origin remote and master branch as default when pushing.
  After using `-u` we can push using `git push`, no need for `origin master`
