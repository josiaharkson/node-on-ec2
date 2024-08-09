# Node Hello World

Simple node.js app that servers "A Monk in Cloud"

Great for testing simple deployments on Cloud

## Step 1: Setup EC2 Instance
Install node version manager (nvm) by typing the following at the command line.

```bash

```

## Step 2: Connect to EC2 Instance
Install node version manager (nvm) by typing the following at the command line.

```bash

```


## Step 3: Upgrade and update packages

```bash
sudo apt update
sudo apt upgrade
```

## Step 4: Install Node.js

```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
node -v
```


## Step 5: Install Git

```bash
sudo apt-get install git
git --version
```

Create a personal access token on your Github account if you dont have one already
run the command to save any future username and token.
```bash
git config --global credential.helper store
```
Clone your repo
```bash
git clone yourproject.git
```

## Step 6: Install Caddy
Visit https://caddyserver.com/docs/install

run the below commands
```bash
sudo ufw allow proto tcp from any port 80,443
sudo ufw status
```
if stsatus is inactive, run
```bash
sudo ufw enable
```
 The command 
```bash
sudo ufw allow proto tcp from any port 80,443
sudo ufw status
```

should now show
```
Status: active

To                         Action      From
--                         ------      ----
Anywhere                   ALLOW       80,443/tcp                
Anywhere (v6)              ALLOW       80,443/tcp (v6)   
```






