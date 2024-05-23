# GitLearning
This repo is to learn the git commands

#!/bin/bash
# the bleow code is to install ansible <br>
sudo apt update<br>
sudo apt install software-properties-common<br>
sudo add-apt-repository --yes --update ppa:ansible/ansible<br>
sudo apt install ansible -y<br>


# the bleow code is to install docker <br>

sudo apt-get update<br>
sudo apt-get install ca-certificates curl<br>
sudo install -m 0755 -d /etc/apt/keyrings<br>
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc<br>
sudo chmod a+r /etc/apt/keyrings/docker.asc<br>

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update<br>

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y<br>
sudo groupadd docker<br>
sudo usermod -aG docker $USER<br>
newgrp docker<br>

-----------------------------------------------------------------------------------------------------------------

