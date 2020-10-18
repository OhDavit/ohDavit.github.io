---
layout: post
title: Addressing problems in cultural way
author: Davit Ohanyan
tags: [Culture, Team Culture]
---

I was driving to supermarket and while was waiting under traffic light noticed that someone threw cigaret from the van. By approaching a bit closer I noticed that the van belonged to the company which was responsible for keeping city clean! I was really shocked: how can one do actions which are completely opposite to her professions' principles; in this case keeping the city clean.
In a world of software development coding standards, test coverage and team's disciplinary should be part of company's, or at least part of the team's culture.

Below I am going to present a framework how to make automated testing as part of the team culture. Please note that testing topic is just an example here and the framework can be used for other topics/ideas as well.

  **Step 1.** First step is to deconstruct existing approach/culture.
Particularly, when engineers don't write tests usually they say we don't have time to write tests and we have QA team which will do testing for us! Indeed, at the beginning writing tests for the features can slow us down. And nowadays there are various opinionated frameworks which enable us to quickly create apps, features and present to users. And Product owners and managers usually are happy with this as they can deliver features to the end users in a very fast manner.

  **Step 2.** Cultural disruption: identifying the Achilles' heel.
Once your application grows you realise that you constantly get bug reports, changing one feature implementation is having side effect on another feature, i.e. you have coupled components in a code. And suddenly your backlog is called buglog, because you have more existing features to fix rather than to develop. At some point your application's code is called [`legacy`][https://softwareengineering.stackexchange.com/questions/94007/when-is-code-legacy/94011#94011].

  **Step 3.** Mine the cultural vanguard.
It's already possible that one of the engineers is writing tests before actually implementing code of the feature. It is very important to support these type of engineers by providing them enough time and reasonable freedom and turning them into cultural vanguard. [`Culture of experimentation`](https://hbr.org/2020/03/productive-innovation?ab=hero-main-text#building-a-culture-of-experimentation) can be one of the ways to find vanguard of changes.

  **Step 4.** Create an idealogy that challenges the Achilles's heel
Cultural vanguards are great source of idealogy. Their experience and input can be used to set up new practices and standards. For instance, they can organize demos, knowledge sharing sessions, etc to explain how TDD approach enforces to have decoupled code design which will make application extensible and scalable. I am not going to dive into manual vs automation testing topic, but one of the well known limitations of manual testing are human errors and testing time. Therefore, decoupled code which enables high standard code, automated testing which makes testing very fast and reliable, can be base idealogy which challenges Achilles's heel of manual testing. And leaders should do a hard work to ensure that everyone understands **why** new set up makes sense and how it will affect overall development process.


![Cultural change framework](/images/culture_change.png)


It's very important to have clearly communicated and agreed ideology, values, standards and principles. For instance: keep our city clean, only accept code changes with tests coverage, etc. Once people are convinced and truly believe they will follow this culture and even start advocating it.

My conclusion is that there are things you can never achieve without having them as part of the culture. Rules and laws can assist, but never be a single pilar. Education and motivation(coaching, guiding, transparency, etc) hand by hand can really be tools for achieving cultural changes. And it's not one night project. As a leader you have to repeat, observe, learn and repeat again.

# Some References
[Disruptive Innovation](https://hbr.org/2015/12/what-is-disruptive-innovation)
[`Culture of experimentation`](https://hbr.org/2020/03/productive-innovation?ab=hero-main-text#building-a-culture-of-experimentation)