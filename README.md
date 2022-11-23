# github-oidc-aws-connector

# GitHub Actions Workflow
  - To create a openID role with identity provider github token (OIDC):
  
  https://us-east-1.console.aws.amazon.com/cloudformation/home?region=<Region>#/stacks/quickcreate?templateURL=https%3A%2F%2Fstorm-fsi-solutions.s3.amazonaws.com%2Fmarketplace-portal-iam-access%2Frole-open-id-identity-provider-FSI-template.json&stackName=role-openid-oidc-stack&param_AWSManagedPolicy=<AWS_Managed_Policy>s&param_AWSAccountId=<AWSAccount_ID>&param_GitHubOrg=<GitHub_Org>&param_RepositoryName=<Repository_Name>
  
  ![Untitled Diagram drawio](https://user-images.githubusercontent.com/47794950/203549987-7f75769d-bfe4-4e91-9840-2439c983abdb.png)
