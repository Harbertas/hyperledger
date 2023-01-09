# 13 Paskaita

## Prerequisites

### 1. git --version
![output](./prerequisites_git.png)

### 2. node --version
![output](./prerequisites_node.png)

### 3. npm --version
![output](./prerequisites_npm.png)

### 4. docker --version
![output](./prerequisites_docker.png)

### 5. docker-compose --version
![output](./prerequisites_docker-compose.png)
	Kadangi docker-compose versija yra 1.29.2, o skaidrėse 2.1.1, tai buvo nuspręsta paleisti (užtruko 15+min, nes viskas buvo outdated kaip reikalas)

	```console
	1. sudo apt update
	2. sudo apt upgrade
	```

### 6.  Fabric installation script
![output](./prerequisites_fabricdevinstall.png)

### 7. Changing Fabric installation script to executable file
![output](./prerequisites_fabricdevinstall_execute.png)

### 8. Executing Fabric installation script (naudoju sudo, nes kitaip permision denied :( )
![output](./prerequisites_run_fabricdevinstall_execute.png)

### 9. NPM install on chaincode/fabcar/javascript
![output](./prerequisites_fabricdevinstall_npm_install.png)

### 10.  Running startFabric.sh with javascript 
![output](./prerequisites_startFabric_using_javascript.png)

#EDIT_1 running like this does not work, missing permissions so SUDO again

#EDIT_2 after running the previous command with sudo, we came up with another problem, so we install **jq** using **sudo apt install jq** to fix it :)

![output](./prerequisites_jq_error.png)

### 11. Removing wallets

![output](./prerequisites_removing_wallets.png)

### 12. Making sure docker is installed

![output](./prerequisites_making_sure_docker_is_installed.png)

### 13. Peer chaincode

![output](./prerequisites_peer_chaincode.png)

### 14. Adding env variables

![output](./prerequisites_env_variables.png)

#EDIT_1 Giving permissions to folder (test-network) using sudo chmod 777 ./*

![output](./prerequisites_chmod_adding.png)

### 15. Running invokes

#EDIT_1 error after running first invoke so we use chmod 777 for the current folder.

![output](./prerequisites_1_command_screenshot.png)

![output](./prerequisites_1_working.png)

![output](./prerequisites_2_working.png)

![output](./prerequisites_3_working.png)

### 16. Dashboard 

![output](./prerequisites_database_WEB.png)

![output](./prerequisites_database_WEB2.png)

### 17. Final touches

![output](./prerequisites_node_script_installs.png)