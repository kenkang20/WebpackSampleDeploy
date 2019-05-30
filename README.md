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