#Backend Config for MERN Stack Implementation#

sudo apt update

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - (to locate where node.js is in ubuntu repository)

sudo apt-get install -y nodejs (this installs nodejs and npm)

To verify the node and npm

node -v

npm -v

Create a new Dir (Todo) for my project

mkdir Todo

cd Todo

npm init (to initailise my project and to create a new file called package.json)

ls (to confirm package.json was created)

Install Express js

npm install express

touch index.js (to create a file)

npm install dotenv

Use vim to open the file,

To close- Press ESC, :w to save and :qa to exit

node index.js

![Screenshot from 2022-07-16 06-51-42](https://user-images.githubusercontent.com/106885875/179342078-d79eab9b-7f1a-483f-b127-a2e499307358.png)

![Screenshot from 2022-07-16 06-27-29](https://user-images.githubusercontent.com/106885875/179341224-fa630514-8058-4086-bd36-1abab09a4bba.png)


Route

To create routes that will define various endpoints that the To-do app will depend on

mkdir routes

cd routes

touch api.js (to create the file)

vim api.js (to open)

MODELS

Model is the heart of JS, and it makes it interactive

npm install mongoose

mkdir models

cd models

touch todo.js

mkdir models && cd models && touch todo.js ( a command to create files and folders simultaneosly)

vim todo.js (to open the todo.js file)

vim api.js (to open, delete the exiting command via :%d)

NB: todo.js and api.js files updated appropriately

##Mongo Database##

Comment: I created my Monogdb account and activated a user accound and connected to a cluster

![Screenshot from 2022-07-16 06-42-57](https://user-images.githubusercontent.com/106885875/179341765-57744c22-70b9-4369-b5c5-58c2c6591f11.png)

updated index.js file to refelect .env, so that node.js can connect to the database

started node server to connect to the database

node index.js

![Screenshot from 2022-07-16 06-24-53](https://user-images.githubusercontent.com/106885875/179342040-f5cca6f2-415b-43a9-91f3-19f39d8abc58.png)



