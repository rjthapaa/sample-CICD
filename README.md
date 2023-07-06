
## Depolyagent installation steps for Centos & Amazon Linux 2 ##
sudo yum update
sudo yum install ruby -y
sudo yum install wget
wget https://aws-codedeploy-us-east-1.s3.amazonaws.com/latest/install
chmod +x ./install
sudo ./install auto
sudo service codedeploy-agent status

