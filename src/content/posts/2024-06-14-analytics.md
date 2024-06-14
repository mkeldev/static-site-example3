---
title: Analytics
description: Setup page analytics
date: 2024-06-14T15:59:07
image: /images/image-2.jpg
authors:
  - Dennis
tags:
  - analytics dev
categories:
  - tech
---
I want to track page views and visits, but I don't want to expose the website visitor's data to ad providers. I also don't want the page to include a cookie banner, because the user should not need to worry about such things.

It is not easy to implement this requirement serverless and with no fees, because the visitor statistics need to be stored somewhere, and hardly any hosted analytic service is free. However, I found [GoatCounter](https://www.goatcounter.com/) that can be used for free  “for reasonable public usage”.

So I set it up to track the page view.

I chose not to use Google Analytics, that would be the easiest solution, but would require a cookie banner and give Google access to all the data.

Netlify would also have a nice analytics solution, but it would cost a monthly fee. That would probably be worth it for a commercial website.
