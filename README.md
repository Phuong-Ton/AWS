■ Create new AWS account needs (For 1year Free-Tier):
1. Email: verify your email code
2. Phone: SMS code
3. Credit/Debit: for verify pay method
4. Consider the day of month to start. if you start on August 29, they count 1 month to using Free-Tier (August 1 - August 31)

■ To do list when starting a new Account(Using Root Account):
1. Add MFA for root account through "Authy" at IAM Dashboard
2. Never use root account
3. Create new account at IAM - Users, Check "provide user access to AWS Console", Create Admin Group and Assign AdministratorAccess Policy, Setup MFA through "Authy"
4. Add permission for user Billing - root>Account>IAM User and Role Access to Billing > Activate
5. Alert preference for AWS Free Tier - root>Account>Building Preference

