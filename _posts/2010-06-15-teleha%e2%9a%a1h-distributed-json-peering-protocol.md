---
layout: post
title: TeleHa?h - Distributed JSON Peering Protocol
url: http://kinlane.com/2010/06/15/teleha%e2%9a%a1h-distributed-json-peering-protocol/
source: http://kinlane.com/2010/06/15/teleha%e2%9a%a1h-distributed-json-peering-protocol/
domain: kinlane.com
image: http://jeremie.com/i/810c8079d4a77e514296b3a58710c903.png
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <img class="alignnone" style="padding: 15px;" title="TeleHash" src="http://jeremie.com/i/810c8079d4a77e514296b3a58710c903.png" alt="" width="284" height="180" align="right" />TeleHash is a new
    wire protocol for exchanging <a href="http://www.json.org/">JSON</a> in a real-time and fully decentralized manner, enabling applications to connect directly and participate as servers on the
    edge of the network. It is designed to efficiently route and distribute small bits of data in order for applications to discover each other directly or in relation to events around piece of
    shared content. The core benefits of TeleHash over other similar platforms and protocols is that it is both generic (not tied to any specific application or content structures) and is radically
    decentralized with no servers or points of central control. It works by sending and receiving very simple small bits of JSON via <a href=
    "http://en.wikipedia.org/wiki/User_Datagram_Protocol">UDP</a> using an easy routing system based on <a href="http://en.wikipedia.org/wiki/Kademlia">Kademlia</a>, a proven and popular <a href=
    "http://en.wikipedia.org/wiki/Distributed_hash_table">Distributed Hash Table</a>. Everything within TeleHash is routed based on a generic <a href=
    "http://en.wikipedia.org/wiki/Secure_Hash_Algorithm">SHA</a> hash, usually of something specific to an application or something common like a URL. While it is still young, the protocol and early
    implementations are evolving quickly and can already be used. Everyone is welcome to start experimenting and get involved in any form. <strong>URL:</strong> <a href=
    "http://telehash.org/">http://telehash.org/</a>
  </body>
</html></p>
