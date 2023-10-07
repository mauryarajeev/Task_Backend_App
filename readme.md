

# Installation
Run the following command to clone the repository
```
https://github.com/mauryarajeev/To-Do-App.git
```
Go to  ```backend``` directory to install packages

```
cd backend
npm install
```
# Configuration
Create ```.env``` file inside ```backend``` directory and copy the following code

```
MONGO_URI=Your mongodb URI
GMAIL_USERNAME=your gmail address 
GMAIL_PASSWORD=password created inside 'App Password' section under google accounts setting
PORT=8000
JWT_SECRET=a random secret key eg. thisisasecretkey
```
# Run the App
Go to ```backend``` directory and start the server
```
cd backend
nodemon server
```
```



