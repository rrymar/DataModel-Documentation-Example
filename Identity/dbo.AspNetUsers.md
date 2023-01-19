### [back](../index.md)

# dbo.AspNetUsers

Stores Users Information like login name, password etc.

| Column               | IsNull | Type          | Description                                                                     |
|----------------------|--------|---------------|---------------------------------------------------------------------------------|
| Id                   | no     | nvarchar(450) | Primary Key                                                                     |
| UserName             | yes    | nvarchar(256) | Human readable user identifier                                                  |
| Email                | yes    | nvarchar(256) | Email linked to user                                                            |
| EmailConfirmed       | no     | bit           | Is user confirmed his email via verification link                               |
| PasswordHash         | yes    | nvarchar(max) | Encoded password with specific hash function, real password is not stored in DB |
| PhoneNumber          | yes    | nvarchar(max) | Phone number linked to user                                                     |
| PhoneNumberConfirmed | no     | bit           | Is user confirmed phone number via sms                                          |
| TwoFactorEnabled     | no     | bit           | Is two factor authentication enabled for this user                              |
