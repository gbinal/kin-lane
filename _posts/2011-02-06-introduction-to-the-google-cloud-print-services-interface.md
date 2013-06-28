---
layout: post
title: Introduction to the Google Cloud Print Services Interface
url: http://apievangelist.com/2011/02/06/introduction-to-the-google-cloud-print-services-interface/
source: http://apievangelist.com/2011/02/06/introduction-to-the-google-cloud-print-services-interface/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png
---
{% include JB/setup %}<p>The Google Cloud Print services interface or Google Cloud Print API is where the whole cloud print thing starts getting cool.
The Google Cloud Print service interfaces allow you to create a cloud print proxy that gives you a virtual cloud printer you can send jobs to.

I'm developing a PHP / MySQL proxy that enables me to register a virtual cloud printer with Google Cloud Print (GCP) registry. Once the printer is registered with the service, it can then receive jobs from and communicate status with Google Cloud Print.
Google defines a Cloud Print Proxy as: A cloud print proxy can be a piece of software that runs on a computer connected to a non-cloud-aware printer, a small add-on hardware device that contains the proxy interface and connects to the printer, or firmware that is built in to printers of the future.
I want to evolve the proxy definition beyond just hardware, I want to proxy Google Cloud Print jobs and translate them into anything, but first what is the GCP services interface?
The URL for the GCP services interface is:

	http://www.google.com/cloudprint/interface/

Currently GCP services interface uses Google client login for installed apps, although I don't see any reason it can't use oAuth for Web Apps.  Both types of authentication give you access to a users Google Account services, the oAuth for Web Apps is cleaner, and doesn't require you ask for a login.
The Auth token retrieved from authentication will need to be included in all requests using the HTTP header Authorization: GoogleLogin auth={auth_token}.
In addition, all requests to the Google Cloud Print server will need to incldue the HTTP header: X-CloudPrint-Proxy: {OEM_ID}
Once you are authenticated with a users account you can begin to make calls against the GCP services interface.  Google provides the following cloud print endpoints:

	/control - Allows proxy control over the status of a cloud print job.
	/delete - Allows proxy to delete a printer from Google Cloud Print (GCP) registry.
	/fetch - Allows proxy to fetch the next available job for the specified cloud printer.
	/list - Provides proxy a listing of all the printers for the given users Google Account.
	/register - Allows proxy to register printers.
	/update - Allows proxy to update various attributes and parameters of the printer registered with Google Cloud Print.

The GCP services interface gives you access to everything you for managing Google Cloud printers and jobs.  Google Cloud Print can also provide print job availability notification through Google Talk, using a persistent XMPP connection.

I have a working XMPP script, because my focus goes beyond instant gratification from a local printer, into more a commercial cloud print format, I'm not implementing the XMPP jobs management and just relying on the /fetch and /control endpoints to manage jobs.
That concludes a quick overview of the GCP services interface, I will be publishing specific Google Cloud Print code samples for each step shortly.  You can also find a Google Cloud Print Developers Guide and Google Cloud Print Services Interface Guide over at Google Code.
Related articles

	Cloud Print "Coming Soon" to Google Docs (readwriteweb.com)
	Wireless Printing From Gmail Coming Soon to Android and iOS (mashable.com)
	Google Cloud Print lets you print GMail content from your mobile device (macworld.com)

</p>
<center><p><a href="http://apievangelist.com/2011/02/06/introduction-to-the-google-cloud-print-services-interface/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
