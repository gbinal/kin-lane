---
layout: post
title: Email in the Amazon Cloud Part 3 - Maintaining IP Addresses and DNS Quality
url: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/
source: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>Sending large amounts of email and ensuring they get received requires a lot of work and you need to make sure your mail framework is setup correctly and is healthy.This takes a lot of work and maintenance.First off I reserve 11 IP addresses with Amazon Web Services.I reserve these 11 IP addresses and never let them back into the general pool.I setup DNS for my domain to reflect using 10 of the IP addresses as smtp1.</p>
<center><p><a href="http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
