# Test EC2 for ELB target 

## Usgage

Run Amazon Linux 2023 instace with following User Data;
```
#!/bin/bash
sudo dnf -y upgrade --releasever=latest
sudo dnf -y update
sudo dnf -y install httpd
wget https://github.com/yuknak-aws/apache/archive/refs/tags/v3.zip
unzip v3.zip 
cd apache-3/
sudo bash ready.sh
```
