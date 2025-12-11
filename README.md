# Azure-Microsoft-Entra-ID
Automating-Microsoft-Entra-ID-with-Terraform.git


This project demonstrates how to automate Microsoft Entra ID (Azure AD) identity management using Terraform (Infrastructure as Code).
Users are dynamically created from a CSV file, organized into security groups based on departments and job roles, and automatically assigned to those groups — all without any manual portal work

What This Project Does

✅ Creates Entra ID users from a CSV file
✅ Builds security groups for departments and job roles
✅ Automatically assigns users to groups using Terraform loops & conditions
✅ Uses Terraform IaC principles for clean, repeatable identity management

.
├── main.tf        # User creation logic from CSV
├── group.tf      # Group creation and user assignments
├── users.csv     # Source file for user data
└── README.md
