# dbo.AspNetUsers

Stores Users Information like login name, password etc.

	[Id] [nvarchar](450) NOT NULL Pimary Key

	[UserName] [nvarchar](256) NULL

	[Email] [nvarchar](256) NULL

	[EmailConfirmed] [bit] NOT NULL

	[PasswordHash] [nvarchar](max) NULL

	[PhoneNumber] [nvarchar](max) NULL

	[PhoneNumberConfirmed] [bit] NOT NULL

	[TwoFactorEnabled] [bit] NOT NULL
