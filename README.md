# Seyi_Project3

## Backend Config for MERN Stack Implementation ##

sudo apt update

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - (to locate where node.js is in ubuntu repository)

sudo apt-get install -y nodejs  (this installs nodejs and npm)

To verify the node and npm

node -v

npm -v 

*Create a new Dir (Todo) for my project*

mkdir Todo

cd Todo

npm init  (to initailise my project and to create a new file called package.json)

ls (to confirm package.json was created)

Install Express js

npm install express

touch index.js (to create a file)

npm install dotenv

Use vim to open the file, 

To close- Press ESC, :w to save and :qa to exit

vim index.js

![image](https://user-images.githubusercontent.com/106885875/177346182-0683fe61-ab5b-473f-98cc-027c727ebad6.png)

http://![image](https://user-images.githubusercontent.com/106885875/177349204-e7c0707b-65bb-463d-83ba-46c93d44005e.png)

Route 

To create routes that will define various endpoints that the To-do app will depend on

mkdir routes

cd routes

touch api.js  (to create the file)

vim api.js  (to open)

MODELS

Model is the heart of JS, and it makes it interactive

npm install mongoose

mkdir models

cd models

touch todo.js

mkdir models && cd models && touch todo.js

vim todo.js (to open the todo.js file)

vim api.js (to open, delete the exiting command via :%d)








