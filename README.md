# My-Cloud-
Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@syedtaalhahussain 
aasemquazi
/
MyCloud
Public
Code
Issues
Pull requests
1
Actions
Projects
Security
Insights
MyCloud/AWS CLI on Ubuntu
@aasemquazi
aasemquazi Update AWS CLI on Ubuntu
Latest commit 6495ce0 on Jan 18, 2017
 History
 1 contributor
51 lines (32 sloc)  829 Bytes

Check your Python installation:

$ python --version

Install python
$ sudo apt-get install python3

Install pip

Download the installation script from pypa.io:
$ curl -O https://bootstrap.pypa.io/get-pip.py

Run the script with Python:
$ sudo python3 get-pip.py

Install the AWS CLI Using pip

$ sudo pip install awscli

Test the AWS CLI Installation
$ aws help


## If you see an error regarding the version, use
$ sudo pip install awscli --ignore-installed six

## For more details go to below link
http://docs.aws.amazon.com/cli/latest/userguide/installing.html#install-bundle-other-os


Accessing S3 buckets
$ aws s3 ls

Configure aws cli
$ aws configure

Access S3 buckets
$ aws s3 ls


Locaate the credentials 
$ cd ~
$ ls
$ ll
$ cd .aws
$ nano credentials
 
Delete credentials
$ rm -rf credentials

Terminate the instance
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
You have no unread notifications
