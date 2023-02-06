# Blockers and solutions


## T
1.  Terrafom Providers constraints:

Could not retrieve the list of available versions for provider hashicorp/aws: no available releases match the given constraints ~> 3.0, >= 3.73.0, >= 4.45.0.

This was because the version constrain on the providers.tf file downloaded an aws version that is lower than the version on one of the aws/modules.

### Solution
Update the version to the required or appropriate version on the .terraform.lock.hcl file and run ' terraform init -upgrade '
