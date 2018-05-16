# Image Processing Application

## create-env.sh usage
### You must pass 6 parameters to the script, include them in this order: security-group id, key-name, IAM instance profile, security-group name, github account username, github account password
 
## destroy-env.sh usage
### This script destroys created load balancers, launch configs, auto-scaling groups, S3 bucket, and created DB instances.

## Assumptions/Clarifications
#### There is a cloudwatch php script included in this repo. After running the project, you can simply run the script and it will display the top 3 Datapoints from the EC2 Cloudwatch Metrics Array as well as the number of jobs processed and not processed via the status fields in the DB.
