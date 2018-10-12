# Packer AMI build for Windows instance
This script creates an AMI with windows instance
This is just a basic example for creating windows instance with PACKER 

## Requirements
* An AWS account with permissions to create EC2 instances and AMIs
* [Packer] Installed (https://www.packer.io/)

## Usage Instructions

1. Ensure your aws credentials have been configured. 
1. Clone or download this repo using git clone 
1. In the repo go to desired folder 
    ```
    packer build windows-server.json
    ```
1. Go make a cup of coffee
1. Once finished, check the output for successful test results.
1. Your AMI is now ready to launch

