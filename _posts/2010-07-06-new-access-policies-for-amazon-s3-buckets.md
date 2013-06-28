---
layout: post
title: New Access Policies for Amazon S3 Buckets
url: http://apievangelist.com/2010/07/06/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/
source: http://apievangelist.com/2010/07/06/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}<p>Amazon Web Services released support for Bucket Policies within Amazon S3 Cloud Storage today. Bucket policies provide access control management for Amazon S3 buckets and for the objects in them using a single unified mechanism. The policies are expressed using whats called Access Policy Language, that enables centralized management of permissions.
Access Control Lists (ACLs) can only be used to grant permissions on individual objects, policies can either add or deny permissions across all of the objects within a single bucket. You can use regular expression operators, so that you can control access to groups that begin with a common prefix or end with a specific file extension such as ".pdf, word, or .html documents
Policies can include references to:

	 IP addresses
	IP address ranges in CIDR notation
	Dates
	User Agents
	 HTTP referrer
	http and https

This really gives me much more granular level control over Amazon S3 buckets. I was just having problems with storing all my server files centrally at Amazon S3 because I couldn't establish settings for entire buckets. I have been distracted by other work lately and with the Fourth of July holiday. Now I can set up a bucket policy to:

	Allow Comprehensive Write Access
	Access from Specific Networks
	 Allow Access from Specific Application using User Agent

I am reviewing my file management policies for Amazon S3 right now to see how I can create different levels of access. This will definitely make it easier for me to require all workstations, servers and web applications to store ALL files in Amazon S3 Buckets.</p>
<center><p><a href="http://apievangelist.com/2010/07/06/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
