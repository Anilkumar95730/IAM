# IAM
IAM (Identity and Access Management):
IAM (Identity and Access Management) in AWS (Amazon Web Services) is a service that helps you manage who can access your AWS resources and what actions they can perform. It allows you to create and manage users, groups, and roles, and set permissions to control access to AWS services and resources securely. Essentially, IAM is a way to manage access and ensure that only authorized users can access or perform specific actions on AWS resources.
![Screenshot 2024-09-09 145228](https://github.com/user-attachments/assets/ed4e6013-bf8e-41e7-bcd0-0db45466f9c8)
# Authentication :
Authentication in AWS is the process of verifying the identity of a user or service trying to access AWS resources. It ensures that the person or application requesting access is who they claim to be, typically using a username and password, access keys, or other security credentials. This step is crucial before allowing any user or service to interact with AWS resources.

# Authorization :
Authorization in AWS is the process of determining what actions a user or service is allowed to perform on AWS resources after they have been authenticated. It defines what permissions they have, such as which services they can access or what specific operations they can perform within those services. In simple terms, after AWS confirms who you are (authentication), it checks what you're allowed to do (authorization).

# group Users :
In AWS, a group is a collection of users that share the same set of permissions. Instead of assigning permissions to each individual user, you can assign them to a group, and all users in that group will automatically have those permissions. This simplifies management by allowing you to control access for multiple users at once.
![Screenshot 2024-09-09 145600](https://github.com/user-attachments/assets/24d0e03b-1697-4d20-9198-cbdbf5a021a4)
# policies are directly attached through the user Groups :
![image](https://github.com/user-attachments/assets/81572622-4a76-48cb-8144-87de45aa68b3)
# Users :
In AWS, a user is an individual account created for a person or application that needs to interact with AWS resources. Each user has its own credentials (like a username and password or access keys) and can be assigned specific permissions that define what actions they are allowed to perform in AWS. Users are typically created and managed through AWS Identity and Access Management (IAM).
![image](https://github.com/user-attachments/assets/23e81f04-dc64-4954-8f5f-ea35e3835c11)
# Policies :
In AWS, a policy is a document that defines permissions. It specifies what actions are allowed or denied on which resources and under what conditions. Policies are used to control user and service access to AWS resources by attaching them to users, groups, or roles. Policies are written in JSON format and help enforce security by defining who can do what within your AWS environment.
![Screenshot 2024-09-09 150010](https://github.com/user-attachments/assets/0f8485a4-5953-433d-9d11-2aa3b95b2c72)
# Roles :
In AWS, a role is a set of permissions that define what actions an entity (such as an AWS service, user, or application) can perform on AWS resources. Roles are used to grant temporary access to AWS resources without needing to share long-term credentials. For example, you can create a role for an EC2 instance to access an S3 bucket, or for a user to assume temporarily for specific tasks. Roles are particularly useful for granting access between different AWS accounts or services securely.

# we can create the policies throught the json format
we can allows access or deny access with help of using the json formate first of all we need to create the in line policies then we need to change json formate through that we can do any thing like allow or deny

# Allow the polcy through json formate :
![Screenshot 2024-09-09 150235](https://github.com/user-attachments/assets/32b703ea-7c63-4323-bf64-4be511cbd1c5)
We can see that the policy added throught the json formate with the help of create in line policy
![Screenshot 2024-09-09 150259](https://github.com/user-attachments/assets/55433be9-de63-42e9-bd1a-4f31c1eaa03e)
# Deny the polcy throught json formate :
Now,we can see that the policy deny throught the json formate with the help of create in line policy
![Screenshot 2024-09-09 150537](https://github.com/user-attachments/assets/002230b8-93ab-4ae9-bdee-40962f26826b)
![Screenshot 2024-09-09 150556](https://github.com/user-attachments/assets/a93627d9-d47d-4710-a2d3-01cb55ea3cb9)
# The result is Here :
We cannot do any thing on this page after denning the policy.Without any permissions we cannot do anything on that page 
![Screenshot 2024-09-09 150610](https://github.com/user-attachments/assets/3f8f8478-a0bb-4e6a-8d86-dfd5376fe0db)
