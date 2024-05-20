#### How to install Jenkins
```sh
https://www.jenkins.io/download/ => https://pkg.jenkins.io/redhat-stable/
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
sudo yum install java-17-amazon-corretto-devel # yum install fontconfig java-17-openjdk
yum install jenkins
sudo service jenkins start
chmod -R 777 /var/lib/jenkins/
```
