---
title: "3 - AWS Authorization and Privileges"
chapter: false
weight: 22
pre: 
---

{{% notice info%}}
<b> Authorization </b> -  What are you allowed to do?
{{% /notice%}}

You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions. AWS evaluates these policies when an IAM principal (user or role) makes a request, giving them different privileges.

For example, an account owner (root) is privileged for all actions. IAM Policies will enable privileges defined at the User and Resource levels.

In AWS, the concept of <b>least privilege</b> means that you give users the least amount of access and responsibility necessary to complete their duties. Least privilege is also referred to as role-based access or need-to-know access and falls under AWS Identity and Access Management policies.

There is a Hierarchy of Privileges in IAM, as shown in the following chart: 

<img src='/images/hierarchy.png' width='400px'>