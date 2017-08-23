---
layout: post
title: Sandwich MVP
---
[Registration for the Sixth Annual Sandwich Club Summit](http://sandwich-club.org/2017-sandwich-club-summit/) is now open! The Summit is free to attend but registration is required as seating is limited.

I'm excited to present an app I've been working on that will help you find a friend with whom to share a sandwich at lunch. In a recent conversation about bring products to market, I heard some advice that I shall paraphrase as, "Build for the ten people you can strong-arm into using your app, not the 10,000 users you think you may one day acquire." I've been thinking about this lately and about my "creative process" as it relates to "art" vs. "design", and I've decided to both trim some features from the MVP and go in an aesthetic direction that would not lionize UX yet not sacrifice accessibility standards.

Originally, Ashley and I had considered user privacy a priority; one ought to be able to create a group only visible to known and invited participants. However, anticipating that only a handful of friends will be initial users, privacy logic seems less an urgent feature to implement. Even with a hundred users, I would do away with privacy controls all together.

Does Sando Club need to be a single page app? I'm indifferent! And I kind of loathe slick UI with parallax effects. Insofar as I have an artistic style, it favors low-concept graphics and camp. I want to recreate the world in my own image, not  So I've settled against using a javascript framework and am proceeding with Rails and CSS grid for a responsive layout. 