# Route53Updater
Upserts a specified name record with the IP of the current machine in Route 53. I am using it with Windows Task Scheduler to basically replace dyndns.

## Usage
Fill in config.yaml with your info and run exe. IAM user needs Route 53 create/update permissions.
  
## References
[AWS Go SDK](https://github.com/aws/aws-sdk-go)
