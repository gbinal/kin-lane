---
layout: post
title: Proofing a Scribd PDF Using Mimeo Connect
url: http://kinlane.com/2011/01/11/proofing-scribd-pdf-using-mimeo-connect/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
<p>
     Now the PDF we pulled from Scribd is proofed. With the Product ID returned from the Mimeo Proof Service we can get the details of the proof. We need to make a second call to the Proof Service and Get the Proof.
</p>
<div class="c1">
     <code>$root_url = "connect.sandbox.mimeo.com/2010/09/"; $user_name = "[user name]"; $password = "[user password]"; $rest = new MimeoRESTclient($root_url,$user_name,$password);$documentId = "702e6c5b-35d8-4ffb-8d3c-cf779d9a13eb"; $url = "ProofService/Proof/" . $Product_ID;</code><code>$rest-&gt;createRequest($url,"GET",""); $rest-&gt;sendRequest(); $output = $rest-&gt;getResponseBody(); $XMLArray = xmlstr_to_array($output);</code><code>for ($Page = 0; $Page &lt; $PageCount; $Page++) { $Small_Image_URL = $XMLArray['ProofPages']['ProofPage'][$Page]['SmallImage']; $Large_Image_URL = $XMLArray['ProofPages']['ProofPage'][$Page]['LargeImage']; }</code>
</div>
<div id="_mcePaste">
     The Proof Service will return a small and large image representation for each page of our PDF. With the small image proofs we can create a preview of the document for displaying to users. The larger image proofs we can use to provide an actual interactive presentation of the document like a HTML5 flip-book or Flash format.
</div>
<div id="_mcePaste">
     In addition to proofing a copy of the PDF, the file is also placed in the My Mimeo account of the application making request or of another new user account created on the fly.
</div>
<div id="_mcePaste">
     Now our PDF content pulled from Scribd and proofed with the Mimeo Cloud Print API we can do several things:
</div>
<div id="_mcePaste">
     <ul class="mainlist">
          <li>Create a new product with PDF content, by merging with existing print document and save to My Mimeo Library.
          </li>
          <li>Create a new product with PDF content, by merging with existing print document and place new print order.
          </li>
          <li>We can leave file in our My Mimeo Library &gt; Proofed PDFs for future use.
          </li>
     </ul>
</div>
<div id="_mcePaste">
     No matter what we do our content stored at Scribd is now ready to start building a document for printing with Mimeo.
</div>