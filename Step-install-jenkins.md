
## To install Debian/Ubuntu (LTS)

```bash

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \ https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \ https://pkg.jenkins.io/debian-stable binary/ | sudo tee \ /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

```
## Start Jenkins
```bash
sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
```
If everything has been set up correctly, you should see an output like this:

![output To Attach](https://github.com/devopssanthosh58/EKS-Full-Setup/blob/main/jenkins.png)

### Install Jenkins to Different flavours Linux Distribution.

[download link](https://www.jenkins.io/doc/book/installing/linux/.)
