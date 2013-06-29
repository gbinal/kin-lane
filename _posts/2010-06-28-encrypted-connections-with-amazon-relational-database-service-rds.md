---
layout: post
title: Encrypted Connections with Amazon Relational Database Service RDS
url: http://kinlane.com/2010/06/28/1753/
image: http://kinlane-productions.s3.amazonaws.com/relational-database.jpg
---
{% include JB/setup %}

     <img class="alignnone c1" title="Amazon RDS" src="http://kinlane-productions.s3.amazonaws.com/relational-database.jpg"  width="140" align="right" />Amazon published today that <a href="http://aws.typepad.com/aws/2010/06/amazon-rds-support-for-ssl-connections.html" target="_blank">Relational Database Service (RDS) now supports SSL encrypted connections</a>. You can now generate an SSL certificate for each database instance.
</p>

<p>
     Here are a few of the details about Relational Database Service (RDS) SSL connections:
</p>
<ul class="mainlist">
     <li>SSL encrypts the data transferred "over the wire" between your DB Instance and your application. It does not protect data "at rest." If you want to do this, you'll need to encrypt and decrypt the data on your own.
     </li>
     <li>SSL encryption and decryption is a compute-intensive task and as such it will increase the load on your DB Instance. You should monitor your database performance using the CloudWatch metrics in the AWS Management Console (pictured at right), and scale up to a more powerful instance type if necessary.
     </li>
     <li>The SSL support is provided for encryption purposes and should not be relied upon to authenticate the DB Instance itself.
     </li>
     <li>
          <img class="alignnone c1" title="Amazon RDS" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg"  width="250" align="right" />
     </li>
     <li>You can configure your database to accept only SSL connections by using the GRANT command with the REQUIRE SSL option. You can do this on a per-user basis so you could, for example, require SSL requests only from users connecting from a non-EC2 host.
     </li>
</ul>
<p>
     I have just started using <a href="http://www.kinlane.com/category/amazon/amazon-relational-database/">Amazon Relational Database Service (RDS)</a> for a couple of blogs and a real-time data harvesting tools I am working on for fun, so probably won't get a chance to try out the SSL encrypted connections for a while. I'm sure it will help make people concerned about cloud security feel a little better.
</p>