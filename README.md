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
git commit -am "<message>"
git push (to commit in git repo)
git push heroku master