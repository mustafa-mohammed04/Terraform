#### Terraform Installation

## Install the required dependencies for Terraform

``` bash
sudo apt install -y unzip wget
```

## Download the latest version of Terraform

``` bash

wget https://releases.hashicorp.com/terraform/0.15.4/terraform_0.15.4_linux_amd64.zip

```
## Unzip the downloaded file 
``` bash
unzip terraform_0.15.4_linux_amd64.zip

```
## Move the extracted Terraform binary to the /usr/local/bin   and Verify the installation by checking the Terraform version

``` bash

sudo mv terraform /usr/local/bin/
terraform --version
```
