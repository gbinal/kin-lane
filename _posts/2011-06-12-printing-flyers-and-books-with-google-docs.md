---
layout: post
title: Printing Flyers and Books with Google Docs
url: http://kinlane.com/2011/06/12/printing-brochures-and-books-with-google-docs/
image: http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-2.png
---
{% include JB/setup %}
<p>
     <a href="http://developer.mimeo.com/"><img src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-2.png" alt="" width="250" align="right" /></a><a title="Google Apps" href="http://www.google.com/apps/intl/en/business/index.html">Google Apps</a> provides a very powerful document management solution, <a title="Google Docs" href="https://docs.google.com">Google Docs</a>. With Google Docs you can upload and create many different types of documents. The Google Apps platform also allows users to collaborate, share, translate, download and print documents in Google Apps. This is pretty powerful stuff, when it comes to business publishing and printing. A couple months ago I built a <a title="prototype of a commercial print application using google Cloud print" href="http://googlecloudprinters.laneworks.net/">prototype of a commercial print application using Google Cloud Print</a>. The platform allows users to sign on and create and / or register cloud printers with Google's Cloud Print (GCP) registry. Google Apps users can then print single sheet, bound document, and binders using Google Cloud Print and Mimeo.com. I wanted to simplify what I built. So I made some time this last week, to strip out three core pieces of functionality. I wanted to enable developers to do three separate types of simple print integrations:
</p>
<ul class="mainlist">
     <li>
          <strong><a title="Printing Single Sheets" href="http://developer.mimeo.com/blog/blog_detail.php?ID=128">Printing Single Sheets</a></strong> - Allow printing of brochures, flyers and other single sheet documents to Mimeo.com with GCP.
     </li>
     <li>
          <strong><a title="Printing Bound Documents" href="http://developer.mimeo.com/blog/blog_detail.php?ID=129">Printing Bound Documents</a></strong> - Allow printing of books, magazines, newsletters, and other bound documents to Mimeo.com with GCP.
     </li>
     <li>
          <strong><a title="Print Driver" href="http://developer.mimeo.com/blog/blog_detail.php?ID=130">Print Driver</a></strong> - Enable sending print files to Mimeo.com using GCP.
     </li>
</ul>
<p>
     These how-tos are meant to be complete, but simple integration examples with <a title="Google Cloud Print" href="http://code.google.com/apis/cloudprint/docs/overview.html">Google Cloud Print</a>. I want to show users how easily it is to print business documents using Google Cloud Print and your <a title="Mime.com" href="http://www.mimeo.com">Mimeo.com</a> account. These samples are written in PHP, and use the Zen framwork for the Google API integration. Each how-to, has the samples, and link to the full repositories for download at Github. I'm hoping this help developers get going with self-publishing and print-on-demand using Google Apps, Google Cloud Print and Mimeo.com.
</p>
<h6 class="zemanta-related-title c1">
     Related articles
</h6>
<ul class="zemanta-article-ul">
     <li class="zemanta-article-ul-li">
          <a href="http://www.kinlane.com/2011/04/mimeo-cloud-printing-building-blocks/">Mimeo Cloud Printing Building Blocks</a> (kinlane.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://www.kinlane.com/2011/04/mimeo-connect-api-ecosystem/">Mimeo Connect API Ecosystem</a> (kinlane.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://www.kinlane.com/2011/04/mimeo-cloud-print-vs-lulu/">Mimeo Cloud Print vs. Lulu</a> (kinlane.com)
     </li>
</ul>