---
title: "4 - IAM Best Practices"
chapter: false
weight: 22
pre: 
---


Best practice for least privileges is to ensure that your policies allow the fewest actions and access to resources as possible.

It is even AWS’ recommendation that when you create IAM policies, you begin with least privileges and then grant elevated privileges when necessary. IAM policies should also be tested by someone with knowledge of your AWS environment and IAM policies for assurance that they are functioning as intended.

AWS recommends creating IAM policies surrounding these subject areas:

    Lock Away AWS Account Root User Access Keys
    Create Individual IAM Users
    Use Groups to Assign Permissions to IAM Users
    Grant Least Privilege
    Get Started Using Permissions with AWS Managed Policies
    Use Customer Managed Policies Instead of Inline Policies
    Use Access Levels to Review IAM Permissions
    Configure a Strong Password Policy for Users
    Enable MFA
    Use Roles for Applications that Run on Amazon EC2 Instances
    Use Roles to Delegate Permissions
    Do Not Share Access Keys
    Rotate Credentials Regularly
    Remove Unnecessary Credentials
    Use Policy Conditions for Extra Security
    Monitor Activity in Your AWS Account
