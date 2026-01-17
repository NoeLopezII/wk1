# wk1
bare-bone-basics

Today, Friday January 16, 2026(GMT+8) marks the begining of my path towards getting employed as a Junior Cloud Security Engineer.

Things I learnt/did today:
    + opened an AWS Free Tier account, configured it and got familiar with the UI.
    + Installed WSL, Terraform, Docker Desktop, VS Code extensions(GitLens, AWS Toolkit, HashiCorp Terraform), AWS CLI v2 and configured it.
    + Went over Git basics
    
    * second half of the day

    + CLI warm ups



    # EC2 SSH Hardening Lab

## Steps Performed
1. Launched Ubuntu 22.04 EC2 (t2.micro)
2. Created SSH key pair locally
3. Connected via SSH using key-based authentication
4. Disabled password authentication
5. Disabled root login
6. Verified SSH access using public key only

## Security Reasoning
- Password authentication disabled to prevent brute force attacks
- Root login disabled to reduce attack surface
- SSH access restricted by Security Group to my IP only
