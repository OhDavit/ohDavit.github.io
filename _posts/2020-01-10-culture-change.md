---
layout: post
title: Integrating automated testing into the company's culture
author: Davit Ohanyan
tags: [Culture, Team Culture]
---

I was driving to the supermarket and while waiting under a traffic light noticed that someone threw a cigarette from the van. By approaching a bit closer I noticed that the van belonged to the company which was responsible for keeping the city clean!
I was really shocked: how one can do actions which are completely opposite to the company's mission she is the part of'; in this case keeping the city clean.
This is a clear sign that laws only are not always sufficient, rather actions and behaviors should be part of the social habit, i.e. culture. Similarly, in the world of software development there are problems which can be solved way more efficiently in a cultural way.
Below I am going to present a framework how to make automated testing as part of the team culture. Please note that automated testing topic is just an example here and the framework can be used for other topics/ideas as well.

  **Step 1.** The first step is to deconstruct existing approach/culture.
Particularly, when engineers don't write tests usually they say we don't have time to write tests and we have QA team which will do testing for us! Indeed, at the beginning writing tests for the features can slow us down. And nowadays there are various opinionated frameworks which enable us to quickly create apps, features and present to users without automated testing. In the same time product managers usually are happy with this as they can deliver features to the end users in a very fast manner in initial phases.

  **Step 2.** Cultural disruption: identifying the Achilles' heel.
As soon as the application grows bugs are constantly reported, changing one feature implementation has side effects on another feature, i.e. components are coupled in the code. Suddenly a backlog is called buglog, because there are more existing features to fix rather than to develop. At some point due to lacking of automated testing application's code is called [`legacy`]([https://softwareengineering.stackexchange.com/questions/94007/when-is-code-legacy/94011#94011]).

  **Step 3.** Mine the cultural vanguard.
It's already possible that one of the engineers is writing tests before actually implementing code of the feature. At this point it's very important to support these types of engineers by providing them enough time and reasonable freedom by turning them into cultural vanguards. [`Culture of experimentation`](https://hbr.org/2020/03/productive-innovation?ab=hero-main-text#building-a-culture-of-experimentation) can be one of the ways to find vanguard of changes.

  **Step 4.** Create an ideology that challenges the Achilles's heel.
Cultural vanguards are a great source of ideology. Their experience and input can be used to set up new practices and standards. For instance, they can organize demos, knowledge sharing sessions, etc to explain how TDD approach enforces to have decoupled code design which will make application extensible and scalable. I am not going to dive into the manual vs automation testing topic, but one of the well known limitations of manual testing are human errors and testing time. Therefore, decoupled code which enables high standard code, automated testing which makes testing very fast and reliable, can be base ideology which challenges Achilles's heel of manual testing. And leaders should do hard work to ensure that everyone understands **why** the new set up makes sense and how it will affect the overall development process.


![Cultural change framework](/images/culture_change.png)

It's very important to have clearly communicated and agreed ideology, values, standards and principles. For instance: only accept code changes with tests coverage.

My conclusion is that there are things you can never achieve without having them as part of the culture. Rules and laws can assist, but never be a single pillar. Education and motivation(coaching, guiding, transparency, etc) hand by hand can be really  tools for achieving cultural changes. And it's not a one night project. As a leader you have to repeat, observe, learn and repeat again. Once engineers are convinced and truly believe they will follow this culture and even start advocating it.

# Some References.
[Disruptive Innovation](https://hbr.org/2015/12/what-is-disruptive-innovation)
[`Culture of experimentation`](https://hbr.org/2020/03/productive-innovation?ab=hero-main-text#building-a-culture-of-experimentation)