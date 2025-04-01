# 4640-w13-lab-start-w25

1. When is the state file created?

The state file is created after we run the command terraform apply and type yes when asked to allow Terraform to perform actions or not.

2. When is the lock file present?

The lock file is present only after we run the command terraform apply and before we type yes when asked to allow Terraform to perform actions or not.

3. Is the lock file always in the bucket after it is created?

No, it's created when we run the command terraform apply, but after we type yes when asked to allow Terraform to perform actions or not, the file is gone when Terraform is done.