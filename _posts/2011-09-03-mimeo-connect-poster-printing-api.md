---
layout: post
title: Mimeo Connect Poster Printing API
url: http://kinlane.com/2011/09/03/mimeo-connect-poster-printing-api/
image: http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png
---
{% include JB/setup %}
<img src="http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png"  align="right" />We've added a new<a title="API that provides poster printing services" href="http://mimeoconnect.3scale.net/wiki/poster-printing-api">API that provides poster printing services</a>for developers. It enables you to price and order commercially printed posters in different sizes, paper, lamination and mounting from within your web and mobile applications.
These are the different settings currently available for posters:
<ul>
     <li>
          <strong>size</strong>- 8.5�11, 11�17, 12�18, 18�24, 24�36 or 36�48
     </li>
     <li>
          <strong>paper</strong>- Premium Photo, Heavy Matte or Standard Matte
     </li>
     <li>
          <strong>lamination</strong>- None or Laminated
     </li>
     <li>
          <strong>mounting</strong>- None or Foam Core Mount
     </li>
</ul>We provide five methods currently:
<ul>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiProof-Post" target="_blank">Proof (POST)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiProof-GET" target="_blank">Proof (GET)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiQuote-GET" target="_blank">Quote (GET)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiShippingOptions-GET" target="_blank">Shipping Options (GET)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiOrderQuote-GET" target="_blank">Order Quote (GET)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiPlaceOrder-POST" target="_blank">Place Order (POST)</a>
     </li>
     <li>
          <a href="http://mimeoconnect.3scale.net/wiki/poster-printing-apiOrderStatus-GET" target="_blank">Order Status (GET)</a>
     </li>
</ul>You will also find common error codes, PHP code samples. I will be adding more code samples as they become available.