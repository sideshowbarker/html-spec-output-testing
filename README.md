To create and run a new web server to serve the contents of this repo,
run the following steps:

git remote remove heroku
heroku create --buildpack https://github.com/FriendCode/heroku-buildpack-static.git
git push heroku master

To view the contents on the web:

heroku apps:open
