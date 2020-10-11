---
layout: post
title: Task Item List
author: Davit Ohanyan
tags: [Culture, Team Culture]
---

I was driving to supermarket and while waiting under traffic light noticed that someone threw cigaret from the van. By approaching a bit closer I noticed that the van belonged to the company which was responsible for keeping city clean! I was really shocked: how can one do things which are completely opposite to her professions' principles; in this case keeping the city clean.
Likewise, in a world of software development, coding standards, test coverage and team's disciplinary should be part of Company's, or at least part of team's culture.

Below I am going to present a framework how to make automated testing as part of team culture. Please note that unit testing topic is just an example and the framework can be used for other topics/ideas as well.

**Step 1.** First step is to deconstruct existing approach/culture. 
Particularly, when engineers don't write tests usually they say we don't have time to write tests and we have QA team which will do testing for us! Indeed, at the beginning write tests can be slow and with nowadays frameworks you can quickly create apps, features and present to your users. And Product owners and managers usually are happy with this as they can deliver features to the end users in very fast manner.

**Step 2.** Cultural disruption: identifying the Achilles' heel.
Once your application grows you realise that you constantly get bug reports, changing one feature implementation is having side effect on another feature, i.e. you have coupled components in a code. And suddenly your backlog is called buglog, because you have more existing feature to fix rather than to develop.

**Step 3.** Mine the cultural vanguard.
It's already possible that one of the engineers is writing tests before actually implementing code of the feature. It is very important to support these type of engineers by providing them enough time and reasonable freedom and turning them into cultural vanguard. [`Culture of experimentation`](https://hbr.org/2020/03/productive-innovation?ab=hero-main-text#building-a-culture-of-experimentation) can be one of the ways to find vanguard of changes.

**Step 4.** Create an idealogy that challenges the Achilles's heel
Cultural vanguards are great source of idealogy. Their experience and input can be used to set up new standards and principles. For instance, having decoupled architecture with high quality implementation, automated tests, etc can be great candidates of idealogy. And leaders here should do a lot of work to ensure that everyone understands **why** it makes sense and how new set up will affect blabla.


![Tux, the Linux mascot](../assets/images/culture_change.png)


It's very important to have defined and clearly communicated and agreed vision, ideology, values, standards and principles. For instance: keep our city clean, only accept high quality code changes, etc. Once people are convinced and truly believe they will follow this culture and even start advocating it.

My conclusion is that there are things you can never achieve without having them as part of the culture. Rules and laws can assist, but never be a single pilar. Education and motivation(coaching, guiding, transparency, etc) hand by hand can really be tools for achieving cultural changes. And it's not one night project. As a leader you have to repeat, observe, learn and repeat again.