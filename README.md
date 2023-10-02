# Terraform_Drift-Detection_Notes

1. Using cron job to everytime run the `terraform refresh` to detect the drift every minute but this command may be soon deprecated by terraform 

2. Configure Strict IAM Policies and prevent un-authorized access to AWS

3. Setting up Audit Logs (like CloudWatch) if someone performs a manual change using IAM belonging to IAM user but not the Terraform role then Lambda function can be configured to trigger notifications
