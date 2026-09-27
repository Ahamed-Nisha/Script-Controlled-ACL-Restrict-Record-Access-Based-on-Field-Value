SCRIPT-CONTROLLED ACL – RESTRICT RECORD ACCESS BASED ON FIELD VALUE

PROJECT OVERVIEW

Script-Controlled ACL – Restrict Record Access Based on Field Value is a ServiceNow security project developed to control record access based on specific field values and user roles.
The project demonstrates how Access Control Lists (ACLs) and scripting can be used to provide controlled access to records. In this project, the Branch field is used as the main condition for restricting record access.
The system ensures that users can access only the records they are authorized to view or modify according to the configured ACL rules.

OBJECTIVES

• To understand Access Control Lists (ACLs) in ServiceNow.
• To implement a Script-Controlled ACL.
• To restrict record access based on a field value.
• To control access according to user roles.
• To implement Create, Read, Write, and Delete access controls.
• To test authorized and unauthorized record access.
• To demonstrate ACL behavior using user impersonation.

TOOLS AND TECHNOLOGIES

• Platform: ServiceNow
• Security Feature: Access Control List (ACL)
• Scripting: JavaScript
• Testing: ServiceNow User Impersonation
• Version Control: GitHub

KEY FEATURE

Branch-Based Record Access
The project uses the Branch field to control access to records.
Example Branch values:
• ECE
• EEE
• CSE
The Script-Controlled ACL checks the relevant field value and determines whether the current user should be allowed to perform the requested operation.

USER AND ROLE CONFIGURATION

Test users and roles are created in ServiceNow to verify the ACL behavior.

The project demonstrates:

• Authorized record access
• Restricted record access
• Record modification permissions
• Record deletion permissions
• Role-based access

ACL OPERATIONS

Create – Controls who can create records.

Read – Controls who can view records.

Write – Controls who can modify records.

Delete – Controls who can delete records.

PROJECT WORKFLOW

User Login
↓
User Role Verification
↓
Access Record
↓
Check Branch Field
↓
Script-Controlled ACL
↓
Evaluate Access Condition
↓
Allow or Deny Access

TESTING

The project is tested using different users and Branch values.

1. AUTHORIZED READ

User tries to access a permitted Branch record. Access is granted according to the ACL rule.

2. UNAUTHORIZED READ

User tries to access a restricted Branch record. Access is restricted according to the ACL rule.

3. AUTHORIZED WRITE

Authorized user attempts to modify a permitted record. Update is allowed according to the ACL configuration.

4. UNAUTHORIZED WRITE

User attempts to modify a restricted record. Update access is denied.

5. CREATE ACCESS

User attempts to create a record. Access is determined by the configured ACL rule.

6. DELETE ACCESS

User attempts to delete a record. Delete access is controlled by the ACL.

7. IMPERSONATION TESTING

Different users are impersonated in ServiceNow to verify their actual record-access behavior.

PROJECT SCREENSHOTS
The repository contains screenshots of:
• Table creation
• Branch field configuration
• Branch choice values
• User creation
• Role creation
• Role assignment
• ACL configuration
• ACL script
• Sample records
• User impersonation
• Authorized access
• Restricted access
• Admin verification

PROJECT DOCUMENTATION
The project documentation contains eight phases:
1. Brainstorming & Ideation
2. Requirement Analysis
3. Project Design
4. Project Planning
5. Project Development
6. Project Testing
7. Project Documentation
8. Project Demonstration

PROJECT DEMONSTRATION

A demonstration video is provided to show the implementation and testing of the Script-Controlled ACL.

Demo Video:
https://drive.google.com/file/d/1JRloiU28K1eZEUEkvvR8EK0NNp0WIvyp/view?usp=drive_link

LEARNING OUTCOMES
Through this project, we learned:
• ServiceNow ACL concepts
• Role-based access control
• Field-based record restriction
• ACL scripting using JavaScript
• Create, Read, Write, and Delete permissions
• User impersonation for security testing
• ServiceNow security configuration

PROJECT INFORMATION

Project Title:
Script-Controlled ACL – Restrict Record Access Based on Field Value
Platform:
ServiceNow
Project Type:
Security / Access Control Project
Repository:
GitHub

CONCLUSION

This project demonstrates how ServiceNow Script-Controlled ACLs can be used to implement field-based record access restrictions. By combining user roles with Branch-based conditions, the project provides a practical example of controlling access to records in a ServiceNow environment.
