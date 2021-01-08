---
id: 3579
title: Google Brings Over Secure DNS to Android
date: 2020-09-02T20:31:35+00:00
author: Newb
layout: post
guid: https://new.blicio.us/?p=3579
permalink: /google-brings-over-secure-dns-to-android/
classic-editor-remember:
  - classic-editor
slide_template:
  - default
ilj_linkdefinition:
  - 'a:0:{}'
fifu_image_url:
  - https://i.imgur.com/GFF2UKG.jpg
fifu_image_alt:
  - Auto Draft
image: https://i.imgur.com/GFF2UKG.jpg
---
[Google has just announced the arrival of Secure DNS in Chrome 85 for Android devices](https://blog.chromium.org/2020/09/a-safer-and-more-private-browsing.html), a feature already present in the desktop versions of Chrome from version 83 onwards, with which it aims to improve the security and privacy of users within their browsing sessions.

This should be a relief to privacy-concerned users that have trouble encrypting, let alone changing DNS servers, in Android. This was otherwise accomplished with jailbreaking and third-party hacks.

According to the company, this feature shares the same design principles as the one available in Chrome for desktop devices. However, it points out that its launch will be progressive in order to guarantee the stability and performance of the function, and also to help DNS providers over HTTPS (DoH) to scale their services according to demand.

Those who want to expand their knowledge about this function, based on the secure DNS protocol called DNS over HTTPS, the company invites to read this blog entry, where it offers more information about it.

In addition, at the user level, Chrome will switch to DNS over HTTPS automatically if the current DNS provider offers this service, and will even do the same with the current private DNS (DNS over TLS) if it were already configured, allowing you to keep the additional services you already have from your current DNS provider. In case the behavior of this function is inadequate to the needs of the users, they have the possibility to make use of other providers, or directly disable this function.