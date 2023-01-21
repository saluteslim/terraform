## Required setup
Install the following:
- [AWS CLI](https://aws.amazon.com/cli/)
- [Terraform](https://www.terraform.io/downloads.html)

After installing the AWS CLI. Configure it to use your credentials.
This enables Terraform access to the configuration file and performs operations on your behalf with these security credentials.

```shell
$ aws configure
AWS Access Key ID [None]: <YOUR_AWS_ACCESS_KEY_ID>
AWS Secret Access Key [None]: <YOUR_AWS_SECRET_ACCESS_KEY>
Default region name [None]: <YOUR_AWS_REGION>
```


## How to use


```shell
$ terraform init
```

Execute the following to see what the infrastructure looks like (provide the necessary values):

```shell
$ terraform plan
```


Then, provision by running `terraform apply` (Ensure to pass necessary values). This will take approximately 10 minutes.

```shell
$ terraform apply
```