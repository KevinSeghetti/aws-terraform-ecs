# aws-terraform-ecs

Taken from https://dev.to/txheo/a-guide-to-provisioning-aws-ecs-fargate-using-terraform-1joo

I fixed some issues, added a sample docker container, and have begun making it more portable by adding a region variable, 
and a prefix variable that is prepended to all service names, so it is possible to provision another set of services by just changing the prefix. 
