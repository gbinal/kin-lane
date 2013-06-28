---
layout: post
title: Amazon Security Groups for EC2
url: http://apievangelist.com/2010/06/16/amazon-security-groups-for-ec2/
source: http://apievangelist.com/2010/06/16/amazon-security-groups-for-ec2/
domain: apievangelist.com
image: http://aws.typepad.com/.a/6a00d8341c534853ef0133f0fc1980970b-500wi
---
{% include JB/setup %}I was working on the review of my small business IT infrastructure today, which includes our servers at Amazon EC2. As I was looking at my "server role" definitions and the corresponding Amazon EC2 Security Groups I saw a new blog post come in from Amazon Web Services.
They put together an overview of building three-tier architectures with security groups. I learned a few things while reading which will hopefully help be better setup my infrastructure:

	You can reference other security groups instead of IP addresses when adding entries
	Creating security for external users such as vendors or development groups
	Security groups filters traffic internally and externally.

So this was an eye opener about truly securing your three-tier architecture. I have the web and database server roles, but the application role is a new layer I hadn't considered.
I also have other role based layers for development (subversion), and content (FTP). Also have mail specific SMTP and POP security layers.
I will be upgrading my Amazon EC2 security structures based upon what I've learned today, and include in my cloud IT infrastructure review strategy.