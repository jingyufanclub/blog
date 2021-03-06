---
layout: post
title: Sando Club MVP
---
[Registration for the Sixth Annual Sandwich Club Summit](http://sandwich-club.org/2017-sandwich-club-summit/) is now open! The Summit is free to attend but registration is required as seating is limited. I'm excited to be a presenter this year debuting an app that will help you find a friend with whom to share a sandwich at lunch.

In a recent conversation about bring products to market, I heard some advice that I shall paraphrase as: "Build for the ten people you can strong-arm into using your app, not the 10,000 users you may one day acquire." I've been thinking about this, and about my "creative process" as it relates to "art" vs. "design", and I've decided to both trim some features from the MVP and head in an aesthetic direction that would not lionize UX yet not sacrifice accessibility standards.

Originally, Ashley and I had considered user privacy a priority; one ought to be able to create a group visible only to known and invited participants. However, anticipating that just a handful of friends will be initial users, privacy logic seems less urgent a feature to implement. Frankly, even with a hundred users I would do away with privacy controls all together.

Does Sando Club need to be a single page app? I'm indifferent! But I'm bored of seeing the ubiquitous slick UI with full-bleed stock images and [parallax effects]({{ site.baseurl }}/astute-readers/) (edit: lol). Insofar as I have an artistic style, it would favor low-concept graphics, camp, and the abject. I want to recreate the world in my image visually and conceptually, not imitate the designs de rigueur. So I've settled against using heavy frameworks and am proceeding with Rails, CSS grid for responsive layout, and a little Vue. And now to draw some sandwiches as avatars.
