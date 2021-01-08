---
id: 944
title: 5 Fundamental Social Design Patterns
date: 2006-10-24T03:02:14+00:00
author: David
layout: post
guid: http://new.blicio.us/?p=944
permalink: /5-fundamental-social-design-patterns/
fifu_image_url:
  - https://i.imgur.com/xobTOd7.gif
fifu_image_alt:
  - 5 Fundamental Social Design Patterns
ultra_companion_post_views_count:
  - "1"
image: https://i.imgur.com/xobTOd7.gif
---
A few different sites have implemented some very successful social designs. I’ll lay out 5 social design patterns here and then follow up with case studies in subsequent posts. These apply to sites with user-generated content where the content is the primary object.  
Public Timeline

I’m starting with the public timeline because, while it’s not the sexiest thing on this list, it’s critical for new users as a solution to the cold start problem. The public timeline is the first place new users will look for new content. It’s also how they will determine if they wish to join your community – the size, the tone, the cultural-norms, and the freshness of your community is easily communicated via the public timeline. And, of course, it’s also where new users can find other interesting users, which leads me to my next pattern.  
Asymmetrical Follow

This has been written about before, so I won’t say much. Asymmetrical follow means I can follow the updates of a user without their permission. They, in turn, could follow me back but it’s not required. This allows for the kind of preferential attachment characteristic of scale-free networks, and it’s scale-free networks that are primed for viral propagation. When the goal is content distribution powered by network effects, it just doesn’t matter if you actually know the person or not. All that matters is if the person if a reliable source for interesting content. This is why social networks have failed to become anything more than social networks. Remember this graph from Brad Horowitz?

## Only 1% of a community are content creators

Most people’s social networks aren’t large enough to contain more than a handful of super-star content creators. I believe the average Facebook account has 300 users. 1% of that is 3 – not enough to be a valuable source of content. If you think Dunbar’s number is a more accurate group size – which I do not with regard to online communities – then you’re only left with 1 or 2 people (1% of 150 = 1.5). Yes, you can argue that Facebook has done very well for itself living off of soap-opera like content – who is dating whom, who got drunk at what party, what was she wearing?!?) but there are natural limits to that growth. Their commenting feature will help drive page views, but there isn’t a whole lot of new value being created there.

## Newsfeed

Nothing shocking about this. Now that your users have gone out and followed their friends and other interesting users, their homepage should now be the newsfeed that aggregates all of that content into one place. But it’s not sufficient just to include the stream of content. You need to also show who contributed that content (and, in the case of re-blogging, the other hands it passed through). Why? Because that’s how you can evaluate the people you are following (and, with re-blogging, discover new people to follow).  
Re-blogging

I’m a huge re-blogging fan. It’s the engine that drives the content diffusion through the network. The concept is simple: if someone I’m following shares something interesting, I can easily push that same interesting piece of content out to everyone who is following me while providing proper attribution. Someone who follows me can do the same, and again, and again. This is really powerful, as the people who follow me are most likely not the same as the people I follow. Re-blogging provides a transport device for great interesting content to travel through connected components of the network (which are generally much larger than your immediate social network).

## Social Proof

While judging the content someone shares is a decent proxy for evaluating whether or not to follow that person, social proof can help. Show how many followers the person has. Better yet, calculate their influence (like PageRank does for websites). Or, show how many favorites their posts have accrued or re-blogs their posts have had. It’s a quick and easy way for users to ascertain the reputation of a user in the context of your site.  
Bonus: APIs and RSS

I promised five, but here’s an extra. Use APIs and RSS to amplify your power. Provide APIs so that others can build tools that extend your reach. Publish RSS feeds so that users can incorporate your interesting content into their existing routines. Make use of other companies’ APIs to publish your content out to them (like publishing to [Twitter](https://new.blicio.us/how-to-promote-your-startup-using-twitter/)). It’s very difficult to create new habits, but it’s much easier to go where your users already are (Facebook, Twitter, Google Reader in my case).

Like I said at the start, I’ll be back soon with some commentary on how well (or not) various sites are implementing these ideas. Off the top of my head, I’m thinking about Blip.fm, bit.ly, and Soup.io. I’d love to talk about Etsy, but I feel like it wouldn’t be appropriate.