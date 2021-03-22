# EXERCISE 0: Clone Git Repository

For that you can use my provided git repository.

    clone the git repository and
    create your own project/git repo from it

Steps: Clone Gitlab to Github
- Click + on Github - import repository
- Open with Github desktop
- Terminal type: Git init
- Terminal: Git add .
- Terminal: git commit -m "first-commit"
- Go to GitHub desktop and push changes

# EXERCISE 1: Package NodeJS App

To have just 1 file, you create an artifact from the Node App. So you do the following:

    Package your Node app into a tar file (npm pack)

Steps:
- Npm install, npm build, npm pack
After the npm pack command it'll create a .tgz file
In this case it created: bootcamp-node-project-1.0.0.tgz

# EXERCISE 2: Create a new server

Your company uses DigitalOcean as Infrastructure as a Service platform, instead of having on-premise servers. So you:

    Create a new droplet server on DigitalOcean

Steps:
1. Droplets --> Ubuntu --> Basic --> Regular --> $5/mo --> Choose a datacenter closest to your region
2. SSH keys. Follow Digital ocean instructions to create an SSH key.
3. Create a Firewall. Networking --> Firewalls --> Create Firewall

# EXERCISE 3: Prepare server to run Node App

Now you have a new fresh server nothing installed on it. Because you want to run a NodeJS application you need to install Node and npm on it:

    Install nodejs & npm on it


# EXERCISE 4: Copy App and package.json

Having everything prepared for the application, you finally:

    Copy your simple Nodejs app tar file and package.json to the droplet

Steps: 
Right-click tgz to copy the path 
Copy ipv4
-  scp bootcamp-node-project-1.0.0.tgz root@111.111.111.1:/root


# EXERCISE 5: Run Node App

    Start the node application in detached mode (npm install and node server.js commands)
    
