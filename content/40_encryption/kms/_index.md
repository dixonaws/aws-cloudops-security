---
title: "AWS Key Management Service"
chapter: false
weight: 22
pre: 
---

<img src='/images/kmslogo.png' width='50px'>


AWS Key Management Service (AWS KMS) is a managed service that makes it easy to create and control the cryptographic keys that are used to protect data. AWS KMS uses hardware security modules (HSM) to protect and validate AWS KMS keys under the [FIPS 140-2 Cryptographic Module Validation Program](https://csrc.nist.gov/projects/cryptographic-module-validation-program/Certificate/3139), except in the China (Beijing) and China (Ningxia) Regions.

The KMS keys that you create are customer managed keys. AWS services that use KMS keys to encrypt your service resources often create keys for you. KMS keys that AWS services create in your AWS account are AWS managed keys.

AWS KMS integrates with most other AWS services that encrypt data. AWS KMS also integrates with AWS CloudTrail to log use of KMS keys for auditing, regulatory, and compliance needs.

<img src='/images/kms_downstream.png' width='400px'>
