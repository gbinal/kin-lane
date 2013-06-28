---
layout: post
title: Amazon Launches New Web Service for Fulfillment
url: http://apievangelist.com/2008/03/20/amazon-launches-new-web-service-for-fulfillment/
source: http://apievangelist.com/2008/03/20/amazon-launches-new-web-service-for-fulfillment/
domain: apievangelist.com
image: 
---
{% include JB/setup %}Amazon added another layer to their stack of web services to.  They added the Amazon Fulfillment Web Service (Amazon FWS) which allows merchants to tap in to Amazon's network of fulfillment centers and logistics. Merchants can store their own products to our fulfillment centers and then, using a web service interface, fulfill orders for the products and ship a product to a customer.There are two sets of APIS - Inbound and Outbound.The Inbound service gives merchants the ability to create and send shipments to an Amazon fulfillment center from your vendors.The Outbound service gives merchants the ability to ship products from Amazon FCs to their customers. This service revolves around the concept of a fulfillment order. The order contains a destination address, a shipping speed, and a list of item/quantity pairs to be shipped. The createFulfillmentOrder function is used to initiate the shipping process. They are moving forward in basically offering a wholesale version of everything the do in-house.