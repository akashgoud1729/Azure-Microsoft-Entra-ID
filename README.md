
# Automating-Microsoft-Entra-ID-with-Terraform

This project demonstrates how to automate Microsoft Entra ID (Azure AD) identity management using Terraform (Infrastructure as Code).
Users are dynamically created from a CSV file, organized into security groups based on departments and job roles, and automatically assigned to those groups — all without any manual portal work.

## FAQ

#### What This Project Does

✅ Creates Entra ID users from a CSV file

✅ Builds security groups for departments and job roles

✅ Automatically assigns users to groups using Terraform loops & conditions

✅ Uses Terraform IaC principles for clean, repeatable identity management


## users.csv

Users list and their data

```bash
first_name,last_name,department,job_title
Akhilesh,reddy,education,manager
gandla,nivas,education,engineer
sharatrh,kumar,education,engineer
```

## Project Structure

Commands 

```bash
.
├── main.tf        # User creation logic from CSV
├── group.tf      # Group creation and user assignments
├── users.csv     # Source file for user data
└── README.md

```



