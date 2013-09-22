---
layout: post
title: "Abstract Away the Complexities of Print with an API"
url: 'http://kinlane.com/2011/07/24/abstract-away-the-complexities-of-print-with-an-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][1]When I was being interviewed at Mimeo.com as the API evangelist, one big gap in my resume, that I was concerned about, was no print industry experience. Mimeo is a print company and naturally I should bring something to the table?

My boss simply replied, We want someone with the tech, not the print. Someone who can think out of the box. For the first time I feel like I'm putting that lack of skill to use.

It took me about 48 hours to get up and running hacking on the [Mimeo Connect Cloud Print API][2] when I first got hired. I was able to start using the API without any real documentation or help, just hacking.

Even though I enjoy this type of hacking, it is about 47.5 hours too long for regular developers. I probably have shortened this time-frame with documentation, FAQ, code samples and how-tos. But there still are some considerable learning curves when it comes to connecting with the Mimeo.com print API.

I see developers struggle with two hurdles:

  * **Mimeo User Account(s)** \- To use Mimeo start to finish you will need 3 separate accounts. developer area, sandbox API, and live API.
  * **Document Building** \- All final product products are designed as documents. You can assemble one or many print files into a final Mimeo document. The document contains all the final print qualities, such as binding, paper, color, etc.
Both these areas provide a lot of flexibility in the Mimeo system, such as a testing environment, and ability to define a wide range of print documents. But they also introduce a substantial learning curve regarding how Mimeo.com operates, before you even can get started using the API.

For some developers this is proving to be too much. Currently a developer comes to me and says, I want to print a poster. Simple request. I respond with:

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png" alt="" align="right" />

_Start by signing up as a Mimeo.com developer, then setup your sandbox environment. Then login and build the poster you wish to see using Mimeo.com poster builder. When done you right click on the document and grab the product id for your poster. Then you can start making calls against the API to build new posters using that document and any new PDF file._ Too much! I should be saying:

_Sign up for developer key, make call against this web service with the size of poster and the URL of PDF you wish to print. You can get proof quote, shipping options, and when ready add address and credit card info to actually order a poster._ My first response is already too long, and you actually haven't even reached the actual goal of printing a poster with an API? My second response is short and achieves the desired goal.

Last week I set out to fix this. I was losing too many simple requests to print posters. So I set out to add a layer to the Mimeo Connect API (with the resources I have), that abstracts away the complexities of print. I don't want a user to have to think about Mimeo accounts or building documents. I want them to only think about achieving integration with their application.

So using [Mashape][3], I'm building simple poster printing API that delivers the desired results. I will be posting more information this week, as it is ready.

   [1]: http://www.mimeo.com/
   [2]: http://developer.mimeo.com/
   [3]: http://www.mashape.com (Mashape)
