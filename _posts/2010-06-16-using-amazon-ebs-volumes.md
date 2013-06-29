---
layout: post
title: Using Amazon EBS Volumes
url: http://kinlane.com/2010/06/16/learning-more-about-amazon-ebs-volumes/
image: http://d1nqddva888cns.cloudfront.net/EBS_Free_Monitoring_Console.png
---
{% include JB/setup %}

     <img title="Amazon EBS Volume Metrics" src="http://d1nqddva888cns.cloudfront.net/EBS_Free_Monitoring_Console.png"  width="300" align="right" />I'm increasing my usage of Amazon EBS volumes. I tend to use objects I've written in PHP or ColdFusion for writing data to Amazon S3. I haven't historically used EBS volumes much, because data tends to be needed across multiple instances.
</p>

<p>
     I'm taking another look at them. I'm going to use in a couple different scenarios:
</p>
<ul class="mainlist">
     <li>
          <strong>AMI Root Device Type</strong> - I'm switching all of my Amazon Machine Images to be EBS Root Device Type. This will help with faster launching and persistence of the AMI.
     </li>
     <li>
          <strong>Second Instance Drive</strong> - Many of the instances I deploy use the C: drive as the system, and D:, E: and other drives as secondary data storage. I will start using EBS Volumes for all secondary drives.
     </li>
</ul>
<p>
     I will still be using key <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> buckets for global storage of images, video, audio and other files that I use across servers and deliver to different availability zones worldwide.
</p>

<p>
     Amazon just released <a href="http://aws.typepad.com/aws/2010/06/new-cloudwatch-metrics-for-amazon-ebs-volumes.html">CloudWatch Metrics for Amazon EBS Volumes,</a> which should make my EBS deployments much easier to manage.
</p>

<p>
     More to come as I further integrate <a href="http://aws.amazon.com/ebs/">Amazon EBS Volumes</a> into my <a href="http://www.kinlane.com">cloud IT infrastructure strategy</a>.
</p>