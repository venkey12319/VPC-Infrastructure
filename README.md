# VPC-Infrastructure to deploy python application with docker 


Create VPC Infrastructure Deployment with Terraform.

I've meticulously crafted an HCL script tailored to this task, executing it seamlessly within Terraform through VC (Visual Studio).

For further exploration and utilization, visit my GitHub repository to find the script: GitHub Repository Link.( https://lnkd.in/g2GvA7ti)

Following the repository, you can conveniently customize various parameters including VPC, subnets, instances, routing tables, internet gateways, security groups, load balancers, target groups, and network ACLs.

Here's a simplified guide to get started:

Step 1: Fork the repository and modify parameter names to suit your requirements.

Step 2: Open Visual Studio Code and create a new file, saving it with a .TF extension.

Step 3: Initiate backend and plugin initialization using the command 'terraform init' in your command-line interface.

Step 4: Validate the script integrity with 'terraform validate'.

Step 5: Preview the changes with 'terraform plan' to ascertain additions, modifications, and deletions.

Step 6: Execute the script seamlessly using 'terraform apply'. Voilà! Your infrastructure is deployed.

Bonus Tip: Ensure consistent formatting with 'terraform fmt' command.

Step 7: To remove all created infrastructure, utilize 'terraform destroy' command.

With Terraform, streamlining your infrastructure deployment has never been easier. Happy deploying!
