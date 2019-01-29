**IAM**

AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

IAM is to manage:

* users
* groups
* Access Policies
* Roles
* User Credentials
* User Password Policies
* Multi Factor Authentication
* API keys for programmatic access CLI

By default new user is created without access to any AWS services

IAM users are indivduals who have been granted access to AWS account

Each IAM user has three main componenets:

* user name
* password
* Permission to access various AWS services


***
**Role:**

An IAM role is an IAM entity that defines a set of permissions for making AWS service requests. IAM roles are not associated with a specific user or group.
Collect of access policy.

You can use IAM roles to delegate access to your AWS resources. With IAM roles, you can establish trust relationships between your trusting account and other AWS trusted accounts. 

Use Roles to **Delegate Permissions**
Don't share security credentials between accounts to allow users from another AWS account to access resources in your AWS account. Instead, use IAM roles. You can define a role that specifies what permissions the IAM users in the other account are allowed. You can also designate which AWS accounts have the IAM users that are allowed to assume the role.

*How much do IAM roles cost?-
IAM roles are free of charge. 


***

**Access Policy:**
You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions. AWS evaluates these policies when a principal entity (user or role) makes a request. Permissions in the policies determine whether the request is allowed or denied. Most policies are stored in AWS as JSON documents. AWS supports six types of policies: identity-based policies, resource-based policies, permissions boundaries, Organizations SCPs, ACLs, and session policies.

**Policy Types:**

*  Identity-based policies – Attach managed and inline policies to IAM identities (users, groups to which users belong, or roles). Identity-based policies grant permissions to an identity.

* Resource-based policies – Attach inline policies to resources. The most common examples of resource-based policies are Amazon S3 bucket policies and IAM role trust policies. 

* Permissions boundaries – Use a managed policy as the permissions boundary for an IAM entity (user or role). 

* Organizations SCPs – Use an AWS Organizations **service control policy (SCP)** to define the maximum permissions for account members of an organization or organizational unit (OU). 


* Access control lists (ACLs) – Use ACLs to control which principals in other accounts can access the resource to which the ACL is attached. 

* Session policies – Pass an advanced session policy when you use the AWS CLI or AWS API to assume a role or a federated user. Session policies limit the permissions that the role or user's identity-based policies grant to the session. Session policies limit permissions for a created session, but do not grant permissions. For more information, see Session Policies.


