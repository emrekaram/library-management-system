# library-management-system

Library management system, a project for **BilgeAdam Academy**. A Windows desktop app for managing books, members and loans, built with C# WinForms and Entity Framework (database-first).

**Status:** Archived · **Stack:** C#, .NET Framework 4.7.2, WinForms, Entity Framework 6, SQL Server, MetroModernUI

## Features

- Login and sign-up with role-based screens (admin, library owner, user)
- Book management
- Member management
- Borrowing and returns
- Owner dashboard

## Project structure

```
LibaryManagmentSystemEf/
├── Model1.edmx            EF database-first model
├── Tbl*.cs                Entities: Book, Member, Borrow, User
├── LoginForm, SignForm    Authentication
├── AdminForm, OwnerDashboardForm, UserForm
└── BookForm, MemberForm, BorrowForm
```

## Getting started

1. Open `LibaryManagmentSystemEf.sln` in Visual Studio.
2. Restore NuGet packages.
3. Update the `connectionStrings` entry in `App.config` to your SQL Server and create the database from `Model1.edmx`.
4. Run the project.

## Related

- [inventory-tracking-system](https://github.com/EmreKaram/inventory-tracking-system): BilgeAdam final project
