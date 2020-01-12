* npm install --save express
* npm install --save-dev nodemon


## install mongodb
sudo apt-get install mongodb
sudo apt-get update
 * start mongo db server
 sudo service mongodb start
 mango
 show dbs;
 use mydb;  // create or/and switch to it
db; // show the current db

db.posts.find(); // to show all data of posts;

## install mongnpm 
npm install --save mongoose

** increasing number of watchers on linux
echo fs.inotify.max_user_watches=582222 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p