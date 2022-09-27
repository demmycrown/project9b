## Continous Integration Pipeline For Tooling Website

1. Install Jenkins

`sudo apt update`

`sudo apt install default-jdk-headless`

`wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`

`sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'`

`sudo apt-get install jenkins`

`sudo systemctl status jenkins`

2. Open port 80:80

[Jenkins](http://<Jenkins-Server-Public-IP-Address-or-Public-DNS-Name>:8080


3. Congfigure Jenkins to receive codes from github

- Install "Publish Over SSH" plugin.

`sudo chmod 777 /mnt/apps`


`sudo chown nobody:nobody /mnt/apps`

`cat /mnt/apps/README.md`
