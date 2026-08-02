# Cloud Security with AWS IAM

## Project Overview

In this project, I learned how to secure AWS resources using AWS Identity and Access Management (IAM). I created IAM users, user groups, and custom IAM policies to control access to Amazon EC2 instances. I also tested permissions by logging in as another IAM user and verified policy behavior using the IAM Policy Simulator.

---

## Project Objectives

- Understand the fundamentals of AWS Identity and Access Management (IAM)
- Launch EC2 instances for different environments
- Apply resource tags
- Create custom IAM policies using JSON
- Create IAM users and user groups
- Restrict access based on EC2 tags
- Test user permissions
- Verify permissions using IAM Policy Simulator

---

## AWS Services Used

- AWS Identity and Access Management (IAM)
- Amazon EC2

---

## Key AWS Concepts

- IAM Users
- IAM User Groups
- IAM Policies
- JSON Policies
- Account Alias
- Resource Tags
- Principle of Least Privilege
- IAM Policy Simulator

---

## Project Workflow

1. Launched two EC2 instances.
2. Tagged one instance as Development.
3. Tagged another instance as Production.
4. Created a custom IAM policy using JSON.
5. Created an IAM User Group.
6. Attached the custom policy to the group.
7. Created an IAM user.
8. Added the user to the group.
9. Logged in as the IAM user.
10. Tested access to both EC2 instances.
11. Verified permissions using the IAM Policy Simulator.

---

## What I Learned

- How IAM controls access to AWS resources.
- How custom JSON policies work.
- How tags can control permissions.
- Why user groups simplify permission management.
- How to safely test permissions using the IAM Policy Simulator.

---

## Challenges Faced

The most challenging part of this project was understanding how custom IAM policies work and how resource tags affect permissions. After testing different scenarios and using the IAM Policy Simulator, I gained a much better understanding of AWS access control.

---

## Project Outcome

The restricted IAM user was able to manage the Development EC2 instance but could not perform actions on the Production instance because of the permissions defined in the custom IAM policy.

---

## Architecture Diagram

*(Architecture diagram will be added here.)*

---

## Screenshots

The screenshots for each project step are available in the `screenshots` folder.

---

## Project Documentation

The complete NextWork project documentation is included in this repository.

---

## Skills Gained

- AWS IAM
- AWS Security
- EC2 Management
- Access Control
- JSON Policy Creation
- Cloud Security Best Practices

---

## Date Completed

August 2026
