Terraform Fundamentals (Tutorials 01–08)

This repository contains the completed Terraform assignment tutorials and proof screenshots for AWS infrastructure in region `ap-south-1`.

## 📁 Directory Structure


├── 01-install-terraform-cli/      # Terraform binary installation verification
├── 02-setup-aws-cli/              # AWS CLI authentication & IAM identity setup
├── 03-build-infrastructure/       # Initial EC2 provisioning config
├── 04-change-infrastructure/      # Resource updates & tag modifications
├── 05-destroy-infrastructure/     # Automated infrastructure teardown
├── 06-input-variables/            # Parametrized configuration files
├── 07-outputs/                    # Exposed resource metadata & public IPs
├── 08-remote-state/               # Backend state management logic
├── screenshots/                   # Complete CLI & AWS Console proof images
└── README.md                      # Project documentation

**Tutorial 01: Install Terraform CLI
 --> Verified local installation of the Terraform binary and ensured executable path mapping.
 --> Verification: terraform -v

**Tutorial 02: Setup AWS CLI & Access Keys
-->  Configured programmatic access credentials and default region (ap-south-1) via AWS CLI.
-->  Verification: aws sts get-caller-identity

**Tutorial 03: Build Infrastructure
-->  Provisioned an initial EC2 instance using dynamic Amazon Linux 2023 AMI data sources.

**Tutorial 04: Change Infrastructure
-->  Applied in-place updates, modifying resource tags without causing unwanted instance replacement.

**Tutorial 05: Destroy Infrastructure
-->  Executed complete infrastructure teardown (terraform destroy) to prevent unwanted AWS charges.

**Tutorial 06: Input Variables
-->  Refactored hardcoded parameters into dynamic input variables (variables.tf) for environment reusability.

**Tutorial 07: Outputs
--> Configured output blocks (outputs.tf) to extract and surface key instance details (Public IP, Instance ID).

**Tutorial 08: Remote State
--> Configured state tracking and verified state file management (terraform state list).
