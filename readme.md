# Terraform AWS Instance

## Resources
* EC2 Instance

## Inputs
* projest (Required) - User should pass their project name(string)
* environment (Required) - User should pass the environment of their insta(string)
*component (Required) - User should pass the component they are creating for infra(string)
* instance_type (optional) - User should pass the instance type they need. Default is t3.micro. users can pass either t3.micro or t3.small or t3.medium.
* sg_ids (required) - User should pass the sg IDs they want to associate with the instance (list)
* ec2_tags (optional) - Users can pass the extra tags they can add to the instance (map)

## Outputs
* public_ip - Public IP of the instance created
* private_ip - Private IP of the instance created

