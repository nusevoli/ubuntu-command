

## vm tools desktop
```
sudo apt install open-vm-tools-desktop
```

## docker & docker-compose
```
sudo apt install -y apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
sudo apt update
sudo apt install -y docker-ce
sudo usermod -aG docker $USER
sudo curl -L "https://github.com/docker/compose/releases/download/v2.32.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker-compose --version
```

## node 22
https://joshtronic.com/2024/05/26/ubuntu-nodejs-22-install/
