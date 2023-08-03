## Step 1 - Backend Configuration
### Update Ubuntu
`sudo apt update`
### Upgrade Ubuntu
`sudo apt upgrade`
### Lets get the location of node.js software from ubuntu repositories.
`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`
### Install node.js on the server
`sudo apt-get install -y nodejs`
### Verify the node installation with
`node -v`
### Verify the node installation with
`npm -v`
![node-installation](./images/node-installation.png)
### Create a new directory for your To-Do project:
`mkdir Todo`
### Verify if the Todo directory is created
`ls`
### Change directory to Todo
`cd Todo`
### Initialise Project
`npm init`
### To Confirm that you have package.json file created
`ls`
   ![package.json](./images/package.json.png)

