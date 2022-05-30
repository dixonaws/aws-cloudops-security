---
title: "At Rest and In Transit"
chapter: false
weight: 21
pre: 
---

<img src='/images/rest_transit.png' width='600px'>

<b>Encryption In-Transit</b>

<p> To protect data in transit, AWS encourages customers to leverage a multi-level approach. All network traffic between AWS data centers is transparently encrypted at the physical layer. All traffic within a VPC and between peered VPCs across regions is transparently encrypted at the network layer when using supported Amazon EC2 instance types. At the application layer, customers have a choice about whether and how to use encryption using a protocol like Transport Layer Security (TLS). All AWS service endpoints support TLS to create a secure HTTPS connection to make API requests. </p>

<b>Encryption At-Rest</b>

<p> AWS provides tools and services to encrypt data and metadata at-rest using industry standard AES-256 encryption algorithms. An encrypted file system, volume, object, or database is designed to handle encryption and decryption automatically and transparently. Below are shown some of the tools used to encrypt data at-rest at different levels. </p>

<img src='/images/encryption_atrest.png' width='600px'>