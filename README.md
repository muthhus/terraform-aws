# terraform-aws
Iaas using Terraform(0.9.40), AWS(S3, EC2 & CloudWatchLog), PostgreSQL, Docker and Linux(Ubuntu &amp; CentOS)

Terraform Commands:

$ terraform -version
$ terraform apply - Applies changes to our infrastructure
$ terraform show
$ terraform plan - Shows us what changes Terraform will make to our infrastrucuture
$ terraform destroy - Destroys infrastructure built with Terraform

To see the terraform command options:
$ terraform help


Using AWS on the command line:

$ echo ${AWS_ACCESS_KEY}
$ echo ${AWS_SECRET_KEY}
$ echo ${AWS_DEFAULT_REGION}

(OR)

$ export AWS_ACCESS_KEY = "ABC"
$ export AWS_SECRET_KEY = "GFCVR12"
$ export AWS_DEFAULT_REGION = "eu-west-1"



