# Azure Role-Based Access Control (RBAC)

## Objective

Implement Azure Role-Based Access Control (RBAC) by assigning permissions to a Microsoft Entra ID security group using the principle of least privilege.

---

## Resources Used

- Azure Resource Group
- Microsoft Entra ID
- Azure IAM (Access Control)
- Security Group: IT Department
- Built-in Role: Contributor

---

## Steps Completed

1. Navigated to the Resource Group.
2. Opened **Access Control (IAM)**.
3. Selected **Add Role Assignment**.
4. Chose the built-in **Contributor** role.
5. Selected the **IT Department** security group.
6. Reviewed the assignment scope.
7. Assigned the role.

---

## Result

The IT Department security group now has Contributor permissions on the Resource Group. Any future users added to this group automatically inherit these permissions.

---

## Key Concepts Learned

### Role-Based Access Control (RBAC)

RBAC controls access to Azure resources by assigning permissions to users, groups, or service principals.

### Scope

Permissions can be assigned at different levels:

- Management Group
- Subscription
- Resource Group
- Individual Resource

Permissions assigned at higher levels inherit down to lower levels.

### Built-in Contributor Role

The Contributor role allows users to:

- Create resources
- Modify resources
- Delete resources

The Contributor role **cannot**:

- Assign roles
- Manage IAM permissions

---

## Security Best Practice

Instead of assigning permissions directly to users, assign permissions to security groups. This simplifies administration and reduces configuration errors.

---

## Principle of Least Privilege

Users should receive only the permissions necessary to perform their job duties.

---

## Challenges

Initially selected the wrong scope for the role assignment. Corrected the assignment by assigning the Contributor role at the Resource Group level instead of an individual resource.

---

## Skills Demonstrated

- Azure IAM
- RBAC
- Microsoft Entra ID
- Security Groups
- Azure Resource Groups
- Principle of Least Privilege
