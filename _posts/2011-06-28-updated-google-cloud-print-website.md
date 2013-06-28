---
layout: post
title: Updated Google Cloud Print Website
url: http://apievangelist.com/2011/06/28/updated-google-cloud-print-website/
source: http://apievangelist.com/2011/06/28/updated-google-cloud-print-website/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo/mimeo_connect_logo.jpg
---
{% include JB/setup %}<p>Google updated the Google Cloud Print website today with all new documentation, code samples and other goodies to help get up and running using Google Cloud Print.
The restructured site pulls together months of learning from behind the scenes by Google, partners and developers on the GCP platform.
The new site starts with a introduction to Google Cloud Print and walks you through each of the components of the Google Cloud Print architecture:

	Applications - Any type of application that enable users to print via Google Cloud Print such as web apps, desktop or mobile applications.
	Google Cloud Print Services - Google's API allowing registering of printers, sharing of printers and sending of print jobs to these printers via applications.
	User Interface - A set of common web interfaces developed by Google that allow users to manage their Google Cloud Print services.
	Printers - Currently defined by cloud ready and non-cloud printing devices.

	Cloud Ready Printers - A new generation of printers with native support for connecting to cloud print services.
	Non-Cloud Printers - All other legacy printers that still connect to devices via PCs and network connections.


	Google Chrome OS Printing - Google's new web operating system where cloud printing is the default print interface, and there is no option for local printing.


The new Google Cloud Print site provides two main areas for integration with the Google Cloud Print Services:

	Submitting Print Jobs

	GCP Web Elements - A JavaScript widget enable simple printing of a PDF file using Google Cloud Print
	Android Integration - Tools for submitting print jobs via Android mobile and tablet platforms
	Services Interface - API documentation for the /submit, /jobs, /deletejob, /printer, /search interfaces, allowing seamless print integration


	Receiving Print Jobs

	Developer Guide - A guide that covers registering printers, handling printers and print jobs on the Google Cloud Print platform.
	XMPP Handshake Flow - Details on the XMPP print job notification system used for notifying "printers" of of new print jobs in real time.
	Services Interface - API documentation for the /control, /delete, /fetch, /list, /register, and /update interfaces, allowing seamless print integration



The new Google Cloud Print update provides much more complete documentation on submitting print jobs and the XMPP integration for print job notification.
They also provide python code samples for integrating with GCP.  You can also use the Mimeo PHP Google Cloud Print samples that I wrote earlier this year, and I will be working on a set of C# samples also, and publish when ready.
</p>
<center><p><a href="http://apievangelist.com/2011/06/28/updated-google-cloud-print-website/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
