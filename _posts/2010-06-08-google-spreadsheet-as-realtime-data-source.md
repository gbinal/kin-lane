---
layout: post
title: Google Spreadsheet as Real-Time Data Source
url: http://apievangelist.com/2010/06/08/google-spreadsheet-as-real-time-data-source/
source: http://apievangelist.com/2010/06/08/google-spreadsheet-as-real-time-data-source/
domain: apievangelist.com
image: http://d35fa85q7j6dnm.cloudfront.net/google-fusion-tables.PNG
---
{% include JB/setup %}I was just talking with Google I/O events team about keeping events sessions up to date on the conference and event sessions page. Sessions change rapidly and updates are needed by multiple teams in real-time.
Web-site(s), support personnel, marketing, etc all need updated information. There are multiple digital and human sources that need the updates.
There are also multiple people potentially making updates to the data. In the business world people default to using a spreadsheet to store information, with the introduction of Google Docs you can easily share this information from a central location.
It is easy to turn on Notification Rules that send email alerts to users when updates are made. Once you follow the link, you can easily see which cell(s) were updated.
This can also be an easy way to update other web sites or other non-human sources. You can send email updates to a system email account, when received it can then pull the spreadsheet through the Google Docs API.
Thus creating a real-time update system.

	The spreadsheet is updated
	Notification is sent to system email address.
	System responds to email notification
	Pull spreadsheets
	Updates local data source from spreadsheet content.

Now this is pretty complex, it would be easier to make these sites use the spreadsheet as a direct data source. If your in the business you know this isn't always possible. People use their own data sources and protocols, they just need an update from time to time.
This process uses an existing set of tools (Google Docs), speaking in an existing language people are used to (spreadsheets) to quickly create a central data source that can updated and notify all human and system users in real-time when updates occur.
As Google continues their move in the Cloud Storage market with Google Docs, Fusion Tables, Google Secure Data Connector and Google Storage for Developers there are an amazing number of ways to use them as a collaborated, centralized data store.