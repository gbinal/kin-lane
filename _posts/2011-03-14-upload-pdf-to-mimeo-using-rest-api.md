---
layout: post
title: Upload PDF to Mimeo Using REST API
url: http://kinlane.com/2011/03/14/upload-pdf-to-mimeo-using-rest-api/
source: http://kinlane.com/2011/03/14/upload-pdf-to-mimeo-using-rest-api/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>I've been <a title=
    "Proofing Documents" href="http://www.kinlane.com/2011/01/proofing-scribd-pdf-using-mimeo-connect/">proofing documents</a> with the Mimeo Connect Cloud Print API. Now I want to start just
    uploading print files into my Mimeo account. I added support for posting files to the Mimeo REST client. Here is a sample POST to the Mimeo Connect Cloud Print API Storage Service. <script src=
    "https://gist.github.com/870303.js?file=MCP%20-%20Storage%20Service%20-%20POST" type="text/javascript">
</script>Storage Service will create any folder structure you specify when posting file. All files and folders are created in the root /printfileroot folder in the specified My Mimeo account.
  </body>
</html></p>
