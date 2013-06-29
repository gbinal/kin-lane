---
layout: post
title: Pulling a PDF Using Scribd API and PHP
url: http://kinlane.com/2011/01/10/pulling-a-pdf-using-scribd-api/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}

This call returns an XML response containing relevant file information:
&lt;rsp stat="ok"&gt;
&lt;download_link&gt;http://documents.scribd.com.s3.amazonaws.com/docs/2kjfqelznknvkv5.pdf?t=1284562355
&lt;/download_link&gt;
&lt;title&gt;
The Future of Reading and Publishing is Social
&lt;/title&gt;
&lt;page_count&gt;4&lt;/page_count&gt;
&lt;height&gt;792&lt;/height&gt;
&lt;width&gt;612&lt;/width&gt;
&lt;dpi&gt;72&lt;/dpi&gt;
&lt;/rsp&gt;
Now I can pull the PDF file and begin using for my cloud print ordering process. Next I will need to proof the document before I can display for the user.