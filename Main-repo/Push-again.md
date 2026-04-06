git add .
git commit -m "Update files"
git push

###################################################

AND TERRAFORM

sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
sudo yum -y install terraform

terraform -version

