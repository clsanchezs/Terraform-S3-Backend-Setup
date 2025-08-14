Using a Remote S3 Backend

1. A manually created S3 bucket used to store the state file, uniquely named and in the region of your choice.
2. S3 backend configured in the Terraform configuration file by referencing the created S3 bucket and providing a relevant key to store the state file.
3. Terraform successfully initialized with the S3 backend.
4. Terraform configuration successfully applied and state stored in the S3 bucket.
