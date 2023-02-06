# Blockers and solutions


##P
1. Providers constraints:
Could not retrieve the list of available versions for provider hashicorp/aws: no available releases match the │ given constraints ~> 3.0, >= 3.73.0, >= 4.45.0.
This was because the version constrain on the providers.tf file downloaded an aws version that is lower
