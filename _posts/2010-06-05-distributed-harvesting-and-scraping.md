---
layout: post
title: Distributed Harvesting and Scraping
url: http://kinlane.com/2010/06/05/distributed-harvesting-and-scraping/
image: http://www.3idatascraping.com/images/data_scraping.jpg
---
{% include JB/setup %}

     Data is the center of my world. I enjoy that there are finally great places on the Internet get open large data sets such as <a href="http://www.factual.com/">Factual</a> and <a href="../?p=1205">Google Fusion Tables</a>. However much of the data I want for different purposes is not neatly organized into an easily accessible data set or available on the Internet.<img class="alignnone" title="Harvesting and Scraping" src="http://www.3idatascraping.com/images/data_scraping.jpg"  width="400" height="308" align="right" />
</p>

<p>
     When I see data on the Internet that is controlled and not widely available I get the urge to set it free. Help the data owner organize it and make it available. Other times I need access to the data for business purposes.
</p>

<p>
     This is when data harvesting or data scraping techniques come into play. It is when you programmatically pull a web page and parse the content to get at some or all of the data on the page. Then you setup some sort of script to spider and pull all of the available pages either through GET or POST of data to increment the site and encourage it to cough up all of its information.
</p>

<p>
     There are many ways to pull these pages and crunch this data for whatever purposes. This isn't what this post is about. It is more about ways to position these scrape or harvest scripts to grab the data.
</p>

<p>
     See when I pull data from a known site, sometimes I making thousands, hundreds of thousands, or millions of requests for pages against a site. If the site owner is smart they will limit the number of requests you can make on their site from a single IP Address.
</p>

<p>
     With limitations on the number of requests I can make in a given time period I have to slow my requests down. With large data sets this means I have to wait longer. Which just isn't acceptable to my ADD personality. I can't wait.
</p>

<p>
     So I need a way of making requests from many IP addresses quickly. <strong>Cloud Harvesting and Scraping Systems.</strong>
</p>

<p>
     With the growth of cloud computing there are many places to quickly procure computing power at unique IP addresses. Using services such as <a href="http://aws.amazon.com/ec2/">Amazon EC2</a>, <a href="http://www.rackspacecloud.com/">Rackspace Cloud</a>, and <a href="http://www.gogrid.com/">GoGrid</a> makes it easy to quickly automate and distribute calls pulling remote pages across many IP addresses.
</p>

<p>
     Of course this route costs $$. So to make it worth my time to deploy cloud infrastructure for harvesting and scraping I need a budget and a legitimate business purposes for the harvest.
</p>

<p>
     Cloud Infrastructure as a Service (IaaS) is the quickest way to plan, deploy, maintain and shut down a distributed harvester and get data as fast you want. Of course you have to refrain from crossing to the dark side of cloud and becoming a Denial of Service (DOS) attack as well. How much can the target data source handle? How many requests can they deal with before their systems are overloaded and you start negatively impacting their business. This can be a fine line. With all the cloud computing power at your finger tips....you have to be careful. <strong>Distributed Harvesting and Scraping System</strong>
</p>

<p>
     Another way of creating a distributed approach to your harvesting and scraping program is to use a distributed approach that technically is still in the clouds, but not using major cloud computing providers. A common way is to procure accounts on many of the FREE hosting providers out their that utilize the language of your choice (PHP, Python) etc. You can easily setup a front site such as blog, forum, or other site and in the back ground be running scripts on timers that pull pages from your target host without alerting triggering their red flags. How you process the harvested data is up to you. I often send raw data back to central cloud based host for processing, cleanup and warehousing.
</p>

<p>
     Another way of created a distributed approach is using JavaScript widgets. You can create intelligent widgets that have a distinct or purpose to unknowing users. They they handle the distributed part for you, and grab the widget code put on their site. You can then create a sort of intelligent proxy in which you can harvest remote data. Of course there are Cross Site Scripting hurdles to overcome, but these have workarounds often times.
</p>

<p>
     Both of these distributed solution create a sort of Ambient Computing Power that you have at your fingertips. You can then harvest data in a distributed fashion at whatever scale you have the budget for or time for depending on your business goals.
</p>

<p>
     Harvesting of data can be fun if you are a data geek, but it can also be illegal. So be careful and wise in how you deploy.
</p>