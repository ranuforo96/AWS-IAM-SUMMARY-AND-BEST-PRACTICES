# AWS-IAM-SUMMARY-AND-BEST-PRACTICES
Summary of IAM and a collection of guidelines and best practices for managing AWS Identity and Access Management:

1. Restrict the use of the AWS root user strictly to initial account configuration

2. Assign a distinct AWS user identity to each individual person

3. Grant permissions to groups rather than individual users, then assign users to those groups

4. Set up and enforce strong password requirements across the account

5. Attach temporary permission policies to IAM service roles to allow AWS services to securely access required resources

6. Require and enforce Multi-Factor Authentication (MFA) across all accounts and users

7. Restrict access key usage exclusively to CLI and SDK programmatic access

8. Maintain strict individual identity boundaries by never sharing user credentials or programmatic access keys across operators

9. Regularly review account permissions using the IAM Credentials Report and IAM Access Advisor
