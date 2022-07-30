---
layout: post
title: "Dewdrop - A Java based Event Sourcing platform released"
date: 2022-07-19 20:37:13 -0600
tags: event-sourcing dewdrop java
categories: [dewdrop]
author: "matt_macchia"
post_image: "/assets/img/blog/01.jpg"
---

<h4>If you build it they will come! </h4> 
<h5>The power of event sourcing, DDD and CQRS</h5>
<p>Over the last year I've had the opportunity to dive deep into the world of event sourcing. This has been a wild ride and a fundamental change in how I view software development. </p>
<p>When I was assigned the idea of exploring event sourcing I thought to myself, that this shouldn't be too difficult. And I went to build an event sourcing strategy with the old ideas that haunt me from the world of service oriented architectures. I won't dive too deep on my many mistakes, but I completely misunderstood the ideas in event sourcing and how to go about them. Which unfortunately led me down the path of having to do a rewrite of what I had done. </p>
<p>If I'd had an easy to use, off the shelf, java based event sourcing framework I would have saved a lot of time getting up to speed and been able to focus on the business logic rather than the low level data management needed to handle event sourcing. Which led to <a href="https://dewdrop.events">Dewdrop</a>...</p> 
<h4>Let me intoruduce Dewdrop!</h4> 
<p>Excuse as I cut and paste from the docs, but here's the elevator pitch for Dewdrop. </p>
<blockquote class="blockquote single-quote">
  <p>Dewdrop is an opinionated, simple and powerful framework for implementing event sourcing in Java. The idea of Dewdrop is to make it easy to build an event driven system easily and quickly by pushing all the complex reading, writing and marshalling of events down deep into the framework allowing your team to focus on building out the business logic in terms of AggregateRoot behavior, Query logic, and ReadModel composition. </p>
</blockquote>
<h4>Why use Dewdrop?</h4>
<p>Building an event sourcing framework is hard. But an absolute necessity if you're going to venture into the world of event sourcing. If you want to use an open source tool like EventStoreDB, you're unable to use any existing frameworks and you'll need to write your own. However, this is a complicated, time consuming task that is fraught with danger. Being able to use a tool off the shelf has huge advantages in terms of cost and time to market.</p>

<h4>Did I mention it's open source?</h4>
<p>Dewdrop is released under the Apache 2.0 license. I decided to release Dewdrop as an open source framework for the following reasons:
  <ul>
    <li>Give back to open source community at large - I've used a lot of open source projects over the years... Time to do my own</li>
    <li>Allow others to expand upon what I've done - I'm curious what others can take and build from these basic ideas</li>
    <li>Open up for others to help me develop it - I'd love the opportunity to work with other people and open up Dewdrop to outside ideas and influence</li>
  </ul>
</p>

<p>I'm not going to dive into the technical benefits here, since I'll be doing a lot more blog posts about event sourcing moving forward, but I can say that this is a stake in the ground for the java community at large to learn and expand in the world of event sourcing. </p>

<h4>What's next?</h4>
<p>My goal over the next few weeks is to increase visibility for Dewdrop and to resolve any bugs that are found. If you see any problems, please let us know at <a href="mailto:dewdrop@betterthanbrian.com">dewdrop@betterthanbrian.com</a>.</p>
<p>In terms of features, the next step is a fundamental question and concern for event sourcing, how to handle versioning of events? We will be looking at some strategies on how to handle this at scale and execute a version management system within Dewdrop.</p>