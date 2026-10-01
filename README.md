# servicenow-script-controlled-acl
ServiceNow project implementing Script-Controlled ACLs to restrict record access based on field values, including user/role creation, table configuration, and READ, CREATE, WRITE, and DELETE access controls.
# Script-Controlled ACL – Restrict Record Access Based on Field Value

## 📌 Project Overview

This project is a ServiceNow System Administrator project focused on creating users, roles, tables, and Access Control Lists (ACLs).

The main objective is to control record access based on field values using **script-controlled ACLs** in ServiceNow.

## 🎯 Project Objective

The objective of this project is to:

* Create users and roles
* Create and configure tables
* Configure READ access controls
* Configure CREATE access controls
* Configure WRITE access controls
* Configure DELETE access controls
* Restrict record access based on field values
* Test and verify ACL functionality

## 🛠️ Technologies Used

* ServiceNow
* ServiceNow ACL
* JavaScript
* GitHub

## 📋 Project Milestones

### Milestone 1 – Creation of Users and Roles

* Created required users
* Created required roles
* Assigned roles to users

### Milestone 2 – Tables Creation

* Created the required table
* Added and configured the required fields

### Milestone 3 – ACL READ

* Created READ Access Control List
* Added the required script condition
* Tested record visibility and access

### Milestone 4 – ACL CREATE

* Created CREATE Access Control List
* Configured script-based access
* Tested record creation permissions

### Milestone 5 – ACL WRITE

* Created WRITE Access Control List
* Configured field/record-based access
* Tested record modification permissions

### Milestone 6 – ACL DELETE

* Created DELETE Access Control List
* Configured access restrictions
* Tested record deletion permissions

### Milestone 7 – Conclusion

* Tested all ACL configurations
* Verified user access
* Documented the project results

## 🔐 Access Control

The project uses scripted ACLs to determine whether a user can access or modify records based on specific field values.

The ACLs control:

| Operation | Purpose                         |
| --------- | ------------------------------- |
| READ      | Controls who can view records   |
| CREATE    | Controls who can create records |
| WRITE     | Controls who can modify records |
| DELETE    | Controls who can delete records |

## 📸 Screenshots

Screenshots of the ServiceNow configuration and testing results are stored in the `screenshots` folder.

## 📁 Project Structure

```text
servicenow-script-controlled-acl/
│
├── README.md
├── screenshots/
├── scripts/
└── documentation/
```

## ✅ Project Status

* [ ] Users and Roles
* [ ] Tables Creation
* [ ] READ ACL
* [ ] CREATE ACL
* [ ] WRITE ACL
* [ ] DELETE ACL
* [ ] Conclusion

## 👨‍💻 Project

**Project:** Script-Controlled ACL – Restrict Record Access Based on Field Value

**Platform:** ServiceNow

**Repository:** GitHub
