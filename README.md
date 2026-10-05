# AWS-IAM-BEST-PRACTICES
Collection of guidelines and best practices for managing AWS Identity and Access Management

Restrict the use of the AWS root user strictly to initial account configuration

Assign a distinct AWS user identity to each individual person

Grant permissions to groups rather than individual users, then assign users to those groups

Set up and enforce strong password requirements across the account

Attach temporary permission policies to IAM service roles to allow AWS services to securely access required resources

Require and enforce Multi-Factor Authentication (MFA) across all accounts and users

Restrict access key usage exclusively to CLI and SDK programmatic access

Maintain strict individual identity boundaries by never sharing user credentials or programmatic access keys across operators

Regularly review account permissions using the IAM Credentials Report and IAM Access Advisor
