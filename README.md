Here our code is in git - 

if dont have account in Heroku then create account in Heroku
New => Create New App
give app-name
click on "Create App Button"

if heroku cli not there then install it : for mac install heroku-cli using command ==> brew tap heroku/brew && brew install heroku


heroku login
 Now follow the commands as mentioned :

----------------
(when code is in git)
heroku git:remote -a deploy-create-react-app-2
----------------
git add .
git commit -am "make it better"
git push heroku master
----------------
once complete click on "Open App" button on top right

Now everytime we make changes to deploy the latest 
first commit and push in git using source tree (so that we dont need to change username in terminal) and then 

git push heroku master