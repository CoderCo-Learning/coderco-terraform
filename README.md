# CoderCo Terraform Project

**Goal**: Build a **production-like WordPress deployment** using Terraform, plus a Vault server to store sensitive information. This assignment is meant to give you hands-on practice with real-world infrastructure-as-code principles.

---

## **Assignment Overview**

You are tasked with creating a **fully functional** infrastructure for WordPress, backed by Amazon RDS (bonus) otherwise you may run the database on the same instance as the WordPress application and using HashiCorp Vault to store secrets (like DB credentials). 

What you need:

- Vault & Wordpress must be created via AMIs. (Packer or not you decide. Bonus points for Packer)
- New VPC with all required components. 
- Database in RDS gets bonus points. Otherwise, you may run the database on the same instance as the WordPress application.
- ALL secrets must be stored in Vault.
- Separate EC2 instances for Vault and WordPress.
- Localstack usage/demonstration is optional but a BONUS.
- The application must be accessible via a public IP address.
- The application must be accessible via a public domain name.
- BONUS: Use Packer to create AMIs for Vault and WordPress.
- BONUS: Create a CICD pipeline to deploy the infrastructure and to build the AMIs.
- BONUS: Automate as much as possible. Even local run of scripts. 

---

## Guidelines**

1. **ALL CLOUD INFRASTRUCTURE MUST BE CREATED VIA TERRAFORM**

2. **No Spoonfeeding**  
   - This assignment expects you to research best practices (e.g., how to set up Vault properly, how to secure WordPress, RDS, create AMIs properly).  
   - Do **not** store secrets in Git. Use Vault or variable files that aren’t committed.

## Tips

- Use a sandbox AWS environment to spin up your infrastructure. If you're using AWS, setup billing. 
- Use Localstack where possible to test your infrastructure. 

---

**Good luck!** Keep your solution modular, well-documented and follow best practices as much as possible.
