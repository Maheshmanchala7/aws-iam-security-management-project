# AWS IAM Security Management Project

## Project Overview

This project demonstrates AWS Identity and Access Management (IAM) security concepts including IAM users, groups, policies, Multi-Factor Authentication (MFA), and least privilege access control.

The project was designed to simulate secure access management in a cloud environment.

---

## Services Used

* AWS IAM
* IAM Users
* IAM Groups
* IAM Policies
* MFA
* AWS EC2
* AWS S3

---

## Security Concepts Implemented

* Least Privilege Access
* Role-Based Access Control
* Multi-Factor Authentication
* Read-Only Permissions
* Custom IAM Policies

---

## Steps Performed

### 1. Created IAM Group

Created IAM group:

```text id="jlwmo0"
Developers
```

Attached policy:

```text id="jlwmr2"
AmazonEC2ReadOnlyAccess
```

---

### 2. Created IAM User

Created IAM user:

```text id="jlwmu5"
mahesh-dev-user
```

Added user to Developers group.

---

### 3. Tested EC2 ReadOnly Access

* Successfully viewed EC2 resources
* Access denied while creating EC2 instances

Implemented least privilege security concept.

---

### 4. Created Custom IAM Policy

Created custom S3 read-only policy using JSON.

---

### 5. Attached Custom Policy to User

Attached custom S3 policy to IAM user.

---

### 6. Enabled Multi-Factor Authentication (MFA)

Configured MFA for secure authentication.

---

### 7. Verified Secure IAM Access

Successfully logged in using password and MFA verification.

---

## Screenshots

* IAM Dashboard
* IAM User Group
* IAM User
* Attached Policies
* EC2 ReadOnly Access
* Custom Policy
* MFA Enabled
* Permissions Review

---

## Challenges Faced

* Understanding IAM permissions
* Policy attachment troubleshooting
* MFA configuration
* Least privilege access implementation

---

## Outcome

Successfully implemented AWS IAM security best practices including secure user management, policy-based access control, and MFA authentication.
