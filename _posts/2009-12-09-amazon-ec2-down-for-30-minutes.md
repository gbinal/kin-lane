---
layout: post
title: Amazon EC2 Down for 30 Minutes
url: http://apievangelist.com/2009/12/09/amazon-ec2-down-for-30-minutes/
source: http://apievangelist.com/2009/12/09/amazon-ec2-down-for-30-minutes/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>We were trying to finish up a major email blast tonight and all of a sudden our main blast server stopped working.
Then I immediately got a flood of email alerts saying all of our live servers were down.
I submitted a trouble ticket to Amazon EC2. I have Gold Support package lately with all the email issues we have been having.
I looked at their AWS Status Page and it reported nothing. Then shortly after I submitted my ticket I see they refreshed the status:
Power issues in a single availability zone


Just the East region was having issues. Our instances in the West zone were fine. This was at the same time they were providing PTR records for our Amazon EC2 email server IP addresses.
</p>
<center><p><a href="http://apievangelist.com/2009/12/09/amazon-ec2-down-for-30-minutes/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
