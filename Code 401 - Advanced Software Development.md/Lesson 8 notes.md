# 5 Steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?

* " A method for managing and controlling access to computer systems and resources based on the roles and responsibiities of users within an organization."
* " A security model that provides a structured way to assign permissions and access rights to users or systsem entities based on their roles, rather than specifying access control for individual users."

2. Describe a Role/Permission heirarchy that you might implement using RBAC.

* Roles - functions or responsibilities
* Permissions - specific actions or operations taht a user with a particular role is allowed to perform
* Users - individuals or entities who interact with the system
* Role Assignment - the process of associating users with specific roles.
* Access Control Policies - specify which roles have access to specific resources and what actions they are allowed to perform

3. What approach might you take to implement RBAC?

* Identify Roles
* Assign Permissions
* Role-Permission Mapping
* User-Role Assignment
* Access Control Policies
* Regular Review and Auditing

### wiwki - RBAC

1. IF authentication is "you are who you say you are", what is Authorization?

* "If YOU are who you say you are" = Authentication
* "*What* are you allowed to do?" = Authorization

2. Name three primary rules defined for RBAC.

* Role Assignment - Exercise a permission only if the subject has selected or been given a role
* Role Authorization - Active role must be authorized for the subject. Users can only take on roles for which they are authorized.
* Permission Authorization - A subject can exercise a permission only if the permission is authorized for the subject's active role.

3. Describe RBAC to a non-technical friend.

* You show up to a laboratory to go to work. In order to get into the building, you have to show security your badge and your badge determines what you can do and where you can go within the laboratory. So if you have a "lead scientist" badge, you can go wherever and do whatever in the lab. If your badge says "chemicals", you can only go to the "chemical" lab and work exclusively with the chemicals.

### RBAC Tutorial Video

1. What are access rights Associated with? The user? or the Role? Explain.

* The role.  With RBAC every user is given a role based on what they are there to do. So then the role gets associcated with a set of rights or permissions that stipulate what they can/can't do.

2. Access Rights, or Authorization, is activated after a user successfully does what?

* Access Rights/Authorization is activated after a user successfully completes the authentication process.

3. Explain how RBAC might benefit a business?

* It allows everyone within the business to have a specific role with authentication. Managers can manage, employees can employee, without trying to manage because they need authorization.

#### References

* ChatGPT (5 steps to RBAC)
