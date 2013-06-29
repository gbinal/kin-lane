---
layout: post
title: My Only 2 Complaints About Amazon EC2
url: http://kinlane.com/2009/02/28/my-only-2-complaints-about-amazon-ec2/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}

So tonight I was doing some server maintenance and backing up many server instances as AMI. This gives me a image snapshot of that production server to use while scaling and / or restoring in the event of failure.
Any other time the EC2 services are awesome but tonight my 2 complaints are evident:
1) Only 1 IP Address per instance. PLease give me multiple IP Addresses per instance.
2) When I bundle a Windows 2003 Web Server Instance it KILLS ANY SSL CERTIFICATES! It does something to the permissions of the certs in store. I blogged about this before. I have .pfk backup files and I just delete and import. Still it is a pain to do across MANY web server instances.
So I only backup machine instances using AMI once a month.