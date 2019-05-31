# UpStarMusic
Starter Repo for a Webpack course on Udemy

You can download this repository by using the green `Clone or Download` button on the right hand side of this page.  This will present you with the option to either clone the repository using Git, or to download it as a zip file.

If you want to download it using git, copy paste the link that is presented to you, then run the following at your terminal:

```
git clone https://github.com/StephenGrider/WebpackProject.git
cd WebpackProject
npm install
```


For github Pages

git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/kenkang20/WebpackSampleDeploy.git
git checkout -b gh-pages
git subtree push --prefix dist origin gh-pages

https://kenkang20.github.io/WebpackSampleDeploy/#/


For AWS S3

npm install -g s3-website
s3-website create webpack-deploy(whatever)
s3-website deploy dist


To Run Server
set NODE_ENV=production&node server.js

For Heroku
procfile
install heroku cli
heroku create
git remote -v
git push heroku master
heroku logs
heroku open

For AWS Elastic Beanstalk
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-windows.html

You have not yet set up your credentials or your credentials are incorrect
You must provide your credentials.
(aws-access-id): A0K3I7AJJUEX5HCOZMWS2DA
(aws-secret-key): k8o0V0ozOPLGykTKYfK5G2ebxGN3VXnI/yl/awtWzmD

Enter Application Name
(default is "WebpackProject"):
Application WebpackProject has been created.

It appears you are using Node.js. Is this correct?
(Y/n): y
Do you wish to continue with CodeCommit? (y/N) (default is n):
Do you want to set up SSH for your instances?
(Y/n): y

eb setenv NODE_ENV=production
eb open
eb terminate
