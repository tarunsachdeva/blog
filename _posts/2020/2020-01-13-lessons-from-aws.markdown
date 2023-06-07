---
layout: post
title:  "Lessons from the Early Days of AWS"
comments: true
date:   2020-01-13 12:00:00 -0500
categories: general
draft: false
favorite: true
---

In 2002-2003 as a young developer I spent a few internships at Amazon.com. I was strangely interested in the world of mobile apps, which at that time meant writing software for [Nokia Series 60 devices](https://en.wikipedia.org/wiki/S60_(software_platform)). Amazon had a small team called Amazon Anywhere, which reportedly was responsible for bringing Amazon "anywhere except the PC". This team was responsible for building an API layer around the core Amazon data (at that time it was product information). This API was then abstracted for external consumption and became the very first version of Amazon Web Services.

Amazon Anywhere [didn't work out](https://www.cnet.com/news/amazon-anywhere-not-quite-everywhere/) as planned, but the technology and team stayed, and I was lucky to be a fly on the wall in those early discussions. Some lessons from that early experience:

1. **The best companies fail differently.** When an initiative or experiment fails, most companies look at that failure in one dimension. They might chalk it up to wrong market timing, or a bad product. The best companies try to understand every part of what didn't work, and whether there was any other learning along the way that could lead to more opportunity. In Amazon's case, the API they built was found to be a useful thing for internal developers and became a foundational learning for AWS. 

2. **The best companies understand all the ways they create value**. Amazon's API before web services was an internal 'tool' to make development more efficient. Most companies look at their internal tools as a way of getting their core work done, and not as a unit of value themselves. Once they realized it _was_ valuable to others, it was abstracted to be externally friendly. That same logic went down the computing stack - and they soon made available their payments platform, storage, compute, and the rest is history. Key lesson - understand that value signals come from everywhere.

3. **The best companies make long term investments.** AWS in the early days was not a revenue generator. People created websites with AWS powered widgets for things like custom stores, but it wasn't clear the overall value for Amazon. It was only in the later days when more parts of the compute stack were exposed that the value became clear. Now AWS is the highest margin business and fastest growing business in Amazon, almost two decades later. Very few companies carry a multi-decade timescale in their minds. 

Many of these lessons are still valid today, and there are of course decades of lessons that could be extracted from later stages of AWS.
