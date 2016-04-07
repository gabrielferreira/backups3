# backups3
## Requirements
* wget (to know if you have pip installed execute which wget)
  * For Mac execute
    * With brew -> brew install wget
    * With MacPort -> port install wget
  * For Debian execute apt-get install wget
  * For RedHat execute yum install wget
* python2.7 (to know if you have pip installed execute which python and python --version)
  * Follow this link if you don't have python installed https://www.python.org/downloads/
* pip (to know if you have pip installed execute which pip)
  * Follow this link if you don't have pip installed https://pip.pypa.io/en/stable/installing/
  * pip install pip --upgrade (if you already have awscli installed)
* awscli
  * pip install awscli --upgrade

```sh
$ aws configure
AWS Access Key ID [None]: Enter your Access Key here
AWS Secret Access Key [None]: Enter your Secret Key here
Default region name [None]: Enter the region of the bucket here
Default output format [None]: Press Enter
$ aws s3 sync origin_path destination_path --delete
```
