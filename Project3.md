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

To Test the backend code

Installed Postman, activated accout and learnt CRUD operations

created a POST request on Postman

![Screenshot from 2022-07-16 07-01-34](https://user-images.githubusercontent.com/106885875/179342284-9fe9b818-677e-4b99-8384-f7f9a4c302f7.png)

created a GET request on Postman

![Screenshot from 2022-07-16 07-02-10](https://user-images.githubusercontent.com/106885875/179342325-b087fdca-f362-4775-92a0-772966d6ff87.png)

FrontEnd Creation

Commnet: This is to have a graphical user interface GUI for my webclient to interact with my API

Ran the following code command on my Root Directory

npx create-react-app client
(this creates Directory called client, which is where i ran my react codes)

Below Dependencies required before my react App can be succesfully tested

npm install concurrently --save-dev

npm install nodemon --save-dev

Updated my Package.json file on my Root Directory

![Screenshot from 2022-07-16 07-14-34](https://user-images.githubusercontent.com/106885875/179342660-d9437bb2-6b6d-4b94-9ff6-db02488d17db.png)

Started my development server from my Root

npm run dev

![Screenshot from 2022-07-14 09-31-43](https://user-images.githubusercontent.com/106885875/179342830-827e94b6-db1f-49dd-aa2b-c9590e697aa0.png)

Created my React components

Created a new Directory called components in my src directory (Todo/Client/src)

mkdir components

created three (3) files inside the new directory

touch Input.js ListTodo.js Todo.js

updated Input.js file and ran the below code in my client directory

npm install axios

updated ALL the files in my components directory and src directory with new codes

run npm run dev

![Screenshot from 2022-07-16 05-57-06](https://user-images.githubusercontent.com/106885875/179343215-75dc0ff3-8f6f-46be-a587-2bf4f8c7091c.png)

![Screenshot from 2022-07-16 06-07-37](https://user-images.githubusercontent.com/106885875/179343233-3a6d1c76-383b-4bfa-9a41-541b03dbed35.png)








