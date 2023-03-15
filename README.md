```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "alisametsari/docker-instance/aws"
    key_name = "alikey"
}
```