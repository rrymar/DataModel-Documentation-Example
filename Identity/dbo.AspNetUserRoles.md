### [back](../index.md)

# dbo.AspNetRoles

Stores Roles which is assigned to user. Many to many relation.

| Column | IsNull | Type          | FK                                         | Description           |
|--------|--------|---------------|--------------------------------------------|-----------------------|
| UserId | no     | nvarchar(450) | [dbo.AspNetUsers (id)](dbo.AspNetUsers.md) | Composite Primary Key |
| RoleId | no     | nvarchar(450) | [dbo.AspNetRoles (id)](dbo.AspNetRoles.md) | Composite Primary Key |

