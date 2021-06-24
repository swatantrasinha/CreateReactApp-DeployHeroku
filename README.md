Here our code is in git - 

if dont have account in Heroku then create account in Heroku
New => Create New App
give app-name
click on "Create App Button"

if heroku cli not there then install it : for mac install heroku-cli using command ==> brew tap heroku/brew && brew install heroku


heroku login
----------------
heroku git:clone -a deploy-sample-ceate-react-app
cd deploy-sample-ceate-react-app
----------------
git add .
git commit -am "make it better"
git push heroku master
----------------
once complete click on "Open App" button on top right

Now everytime we make changes to deploy the latest 
git commit -am "<message>"
git push heroku master