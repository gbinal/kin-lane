---
layout: post
title: The API Pipes From Resource to Last Mile
url: http://kinlane.com/2013/03/17/apis-from-resource-to-last-mile/
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/apis-resource-to-last-mile.png
---
{% include JB/setup %}
<p>
     This post is more rant, and about me working through my thoughts on this subject, which is why its on <a href="/admin/blog/kinlane.com">kinlane.com</a> and not <a href="http://apievangelist.com">apievangelist.com</a> or <a href="http://apivoice.com">apivoice.com</a>.  This post is an aggregation of ongoing thoughts I'm having around my role in the API space, a diagram I drew the other day while enjoying an IPA, and inescapable thoughts fueled up by a post by Patrick Meir over at iRevolution, called <a href="http://irevolution.net/2013/03/17/neogeography-and-democratization/">Crisis Mapping, Neogeography and the Delusion of Democratization</a>.  
</p>
<p>
     Meir kicks up a bunch of thoughts related to how I perceive my role in the API space, which I believe is to help keep a certain amount of oxygen (aka open) present in the space, which I believe is the key ingredient in why the expirement we know as APIs is working.  At first glance, API Evangelist looks like just a blog, but in reality it is a pretty complex system of data stores, API connectors, jobs and curation that I'm using to help draw a map of the API space that I can follow. Currently it looks something like this:
</p>
<p>
     <a href="https://s3.amazonaws.com/kinlane-productions/api-evangelist/apis-resource-to-last-mile.png" target="_blank"><img src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/apis-resource-to-last-mile.png"  width="600" /></a>
</p>
<p>
     The way I see the space, is there are a shitload of resources, awaiting to be exposed via APIs that are both public and private resources. The stewards of these resources have the ability to select from tools and resources to deploy their API resources, using various building blocks for accomplishing this.
</p>
<p>
     <strong>API as a Service</strong><br />
     Additional to standing up your own API, there is the phenonmenon known as BaaS, PaaS and SaaS.  Many of these platforms can actually help you deploy API resources, while also consuming and deploying resources of their own.  For example, Kinvey allows you to deploy generic APIs from data stores you setup on their BaaS platform, bt they also consume API resources and makes available to you from eBay, and other places, while also providing you with their own API resources that you can use to rapidly deploy mobile apps. This layer is complex, lots to think aobut here.
</p>
<p>
     <strong>Top APIs</strong><br />
     There is a breed of API resources that are changing the landscape, both in whats available and how you do it.  Leaders like Twilio, SendGrid, Amazon Web Services, Google and others are providing API resources and approaches to delivering API resources in ways that are influencing the API economy in big ways.  These players stand out, and are worthy of identifying as separate group.
</p>
<p>
     <strong>Discovery</strong><br />
     API consumers have to be able to find API resources.  Historically we've only had ProgrammableWeb for this, but we are seeing growth in number of directories, IDE integrations and other evolutions in how we describe, share and discover APIs.  
</p>
<p>
     <strong>Enablers</strong><br />
     There are several evolving approaches to using APIs that deliver entirely new use cases for APIs, enabling new value that API providers and consumers can tap into.  API aggregation from providers like Singly are bringing together existing API resources into easier to use, aggregated interfaces.  Reciprocity providers like Zapier and IFTTT allow resources and value to transfer between API platforms in the clouds and behind the firewall.  Application frameworks like <a href="http://ql.io/">ql.io</a>, are changing how we bridge APIs and rapidly build API driven web and mobile applications.  Real-time providers like Firebase and Pusher are connecting and providing APIs that make the exchange of API driven resources real-time.  These are just a of the few of the new areas of API enablement I'm seeing emerge.
</p>
<p>
     <strong>Reseller</strong><br />
     Platform providers like BaaS, PaaS and Saas, plus the enablers, discovery services and top APIs all represent reseller and partnership opportunities for individual companies deploying API resources.  This is the wholesale world of getting your API found as well as being baked into an existing consumer base.  Without a reseller or partner layer to your API, you are just a single API in a ever growing flood of API resources.
</p>
<p>
     <strong>Last Mile</strong><br />
     However, this is all just the piping or tubes of this fascinating new API driven economy.  The entire purpose of having these API pipes is to deliver the "last mile".  APIs began by delivering resources to distributed web sites, and enabling sharing and embeddable widgets and buttons.  With the birth of the cloud, APIs began delivering wholesale infrastructure resources for use indistributed cloud environments. Then with mobile we saw the demand for APIs skyrocket--what will it do with big data, sensors, devices, cars, home and building and beyond? 
</p>
<p>
     Which brings me back to my role as API Evangelist.  I feel compelled to keep the discussion of the pipes occuring within all the "last mile" conversations.  I understand the VC's and companies under their control want to monetize the last mile.  This is fine.  But I want to prevent the API pipes from getting paved over in the process.  
</p>
<p>
     I want ANYONE to be able to get at the pipes behind the tablet applications their children use.  I want ANYONE to be able to get at the data that went into any infographic, visualzation or report.  I want ANYONE to understand the pipes that connect our physical worlds via sensors, devices to our online worlds.  
</p>
<p>
     I want the pipes to stay open, accessible, transparent and part of ALL "last mile" conversations.  Which brings me back to Patrick Meir article.  There were several key quotes I'm processing in regards to how I view API resources, API pipes and the last mile API Products that are derived from them:
</p>
<p>
     <em>Feenberg’s own view is constructivist, “emphasizing that technology development is humanly controlled and encapsulates values and politics; it should thus be open to democratic control and intervention.” In other words, “technology can and should be seen as a result of political negotiations that lead to its production and use. In too many cases, the complexities of technological systems are used to concentrate power within small groups of technological, financial, and political elites and to prevent the wider body of citizens from meaningful participation in shaping it and deciding what role it should have in the everyday.”</em>
</p>
<p>
     <em>“Meaning Hacking" is often hijacked by "Deep Technical Hackers"</em>
</p>
<p>
     <em>Democratizing information flows and access; promoting Open Data and Do it Yourself (DIY)</em>
</p>
<p>
     <em>Innovation with free, highly hackable (i.e., open source) technology; letting go of control.</em>
</p>
<p>
     <em>"the artful alteration of technology beyond the goals of its original design or intent,” enables “Deep Democratization"</em>
</p>
<p>
     <em>"Freely pro-viding the hackable building blocks for DIY Innovation is one way to let go of control and democratize"</em>
</p>
<p>
     <em>"The control over the information is kept, by and large, by major corporations and the participant’s labor is enrolled in the service of these corporations, leaving the issue of payback for this effort a moot point. Significantly, the primary intention of the providers of the tools is not to empower communities or to include marginalized groups, as they do not re-present a major source of revenue."</em>
</p>
<p>
     There are so many lessons to be absorbed from CrisisMapping and Neogeography, when it comes to the API economy.  Sorry for just posting these quotes as just a list, but I'm still absorbing and just needed them published in single place, so I can reference and re-read while thinking on this subject.  (Thats right, I read my own blog!)
</p>
<p>
     I don't think there are any easy answers here.  I just want to make sure we keep the conversation including the pipes and not just about the resources and last mile products delivered on top of the pipes.  So we don't cutoff the oxygen needed for the API economy to work for EVERYONE!
</p>