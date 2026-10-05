# AWS-IAM-SUMMARY-AND-BEST-PRACTICES
Summary of IAM and a collection of guidelines and best practices for managing AWS Identity and Access Management

SUMMARY:

USERS - represent individual people or applications, and they get passwords to access the AWS Management

GROUPS - strict collections for organizing multiple users, making it much easier to manage permissions for many people at once

POLICIES - sets of permissions defined in JSON format that specify exactly what someone is allowed or denied to do

ROLES - a secure identity with specific permissions that temporary users, apps, or services borrow rather than permanent human logins

SECURITY - the enforcement of MFA and strong password policies

AWS CLI - allows you to control and manage cloud services directly from your computer's terminal

AWS SDK -  a collection of tools and libraries that lets you build apps using your favorite programming language

ACCESS KEYS - credentials used for secure programmatic access when interacting with AWS resources via the CLI or SDK

AUDIT - for auditing and compliance, you should regularly review IAM Credential Reports and use the Access Advisor to monitor the permissions that are actually being used

BEST PRACTICES:

1. Restrict the use of the AWS root user strictly to initial account configuration

2. Assign a distinct AWS user identity to each individual person

3. Grant permissions to groups rather than individual users, then assign users to those groups

4. Set up and enforce strong password requirements across the account

5. Attach temporary permission policies to IAM service roles to allow AWS services to securely access required resources

6. Require and enforce Multi-Factor Authentication (MFA) across all accounts and users

7. Restrict access key usage exclusively to CLI and SDK programmatic access

8. Maintain strict individual identity boundaries by never sharing user credentials or programmatic access keys across operators

9. Regularly review account permissions using the IAM Credentials Report and IAM Access Advisor
