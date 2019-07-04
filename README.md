## Install environment on Linux 

1. Install some package

    ```bash
    sudo apt update
    sudo apt upgrade
    sudo apt install -y python-pip curl git
    pip install docker-compose
    ```

2. Install Docker 

    Method 1: `sudo curl -sSL https://get.daocloud.io/docker | sh`  
    Method 2: `sudo curl -sSL get.docker.com | sh`
    
    More reference at： [https://docs.docker.com/install/](https://docs.docker.com/install/)

## Setting and configing system

1. Use root permission
    ```bash
    sudo apt passwd root
    su -
    cd ..
    cd home/youruser
    ```

2. Clone sources project

    ```bash
    git clone https://github.com/Greenhat1998/OnlineJudgeDeploy.git
    cd OnlineJudgeDeploy
    ```

3. Run docker-compose

    ```bash
    apt install docker-compose
    docker-compose up -d
    ```
