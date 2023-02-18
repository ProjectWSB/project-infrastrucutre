# Moduł Terraform dla instancji AWS EC2

Ten moduł tworzy instancję EC2 na platformie AWS.

# użycie - przykład

```hcl
module "ec2_instance" {
  source = "github.com/example/terraform-aws-ec2-instance"

  region        = "us-west-2"
  instance_type = "t3.small"
  ami           = "ami-0c55b159cbfafe1f0"
}
