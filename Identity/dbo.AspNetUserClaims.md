### [back](../index.md)

# dbo.AspNetUserClaims

Stores assigned to the user Claims.

| Column     | IsNull | Type          | FK                                         | Description                 |
|------------|--------|---------------|--------------------------------------------|-----------------------------|
| Id         | no     | int           |                                            | Primary Key, auto generated |
| UserId     | no     | nvarchar(256) | [dbo.AspNetUsers (id)](dbo.AspNetUsers.md) |                             |
| ClaimType  | yes    | nvarchar(max) |                                            | Type of the claim           |
| ClaimValue | yes    | nvarchar(max) |                                            | Claim value                 |

