---
title: "SpecOps Revived"
date: 2018-11-27 21:20:00 +1100
categories: experiment
tags: todayilearned specops ionic4 reactnative angular
classes: wide
---

# TL;DR
* nice visual upgrades for `engine`
* retrospective on SpecOps, lessons learned and moving forward
* `ionic4` might be the next big thing for mobile development

---

# Some upgrades
Everything looks **so** much better using this `minimal-mistakes` theme. Took a while to configure certain parts of the system, like links to my other websites and being able to share on social media.

Which got me thinking, I'm *pretty sure* `#fullstack` doesn't just mean online web content and SQL databases, but also the mobile environment, such as phone apps.

Back in the days there was an idea where a group of friends (myself included) thought it's about time we made a phone app for *something*. We were **really** excited about it all, meeting up regularly to talk about how we were going to approach it and see if its actually feasible. We were off on a good start but we couldn't quite hit our targets. It was a pretty demoralising moment in my life and I've always regretted how it ended. 

But this is `#justdevtings` right? This kind of stuff happens all the time when it comes to creating something new and innovative.

So... what then? Is it just done and dusted, or are we going to learn from our mistakes?

# Failing before succeeding

But what were our mistakes?

## Experience

Well for one thing we had *very* little developer experience when it comes to phone apps, especially for myself where I've only had a `functional` understanding of back-end development with my `C#` and `SQL` experience over the course of 2 years.

A bit of our goals were:
- learn what the full `SDLC` _(Software Development LifeCycle)_ of phone apps are
- learn how to manage a project
- how much resources we need for a joint venture
- where do our **passions** lie?
- have fun

We definitely had fun, it was a good bonding experience as well as a slap in the face that we weren't ready to commit to something we thought should be *okay* to handle.

## Time & Commitment

We were all employed full-time, and for some of us we were juggling university study as well _(thank God its over now)_. I think that we underestimated how much time we had left in the day to then put into SpecOps.  

We also have our own personal lives to attend to, being an adult is hard :sweat:. 

We were also volunteers at our church, serving in our ministries _(yes, plural)_ and that takes a lot of our days as well. It's not an excuse but it does show where our priorities are, and God is **definitely** something we didn't want to leave behind.

## Too much at one time

Gosh there was a lot of features we had planned for the app. We were really excited for what we could bring to the table, as well as how much quality of life improvements we were going to introduce to such an already manual process. It still surprises me **to this day** how much paper gets used in an organisation...

But we had to start somewhere, and I think because we didnt have the `DevOps` set up, we couldn't decide on what should be done first, and we still didn't know how `ReactNative` did stuff (more on that later), we didn't really *finish* anything.

> Stop starting, start finishing.

Classic `Agile` mentality would've been great here :sweat_smile:

There's probably more that I missed but these were the ones that struck out to me the most. It doesn't mean that I regret SpecOps, if anything I regret that it hasn't come into fruition ... yet.

Definitely learned lots though, and I definitely had fun doing it which matters to me the most.

Because why do anything if you don't enjoy it?

# A new challenger has arrived!

So now to some `#justdevtings` talk!

To make the app we were looking into [React Native](https://facebook.github.io/react-native/) which is a framework built by Facebook _(I know right?)_ that transpiles to the native language of the target platform, using `JavaScript` as the intermediary language.

... It just means that it builds the app using the language specific to the phone OS (Android or iOS).

This had a lot of benefits including:
* native code base for pure optimisation
* hot-reloading onto an emulation or using a real phone to see it in action
* uses Javascript, a language used globally
* its used by the Facebook app <-- not sure if this is a **real** benefit but anyway

However! I came across this video on YouTube about [Ionic 4](https://ionicframework.com/docs/)!

{% include video id="34fDUKaJBtw" provider="youtube" %}

Which brings up **a lot** of great points:
* closely models an `angular-cli` webapp
* nice default styling
* can test in a `WebKit` browser (like Chrome)
* angular routing

Oh man this made me **really** happy to see that I can use my `angular` knowledge in building phone apps as well! Especially with routing.

Seriously, using a stack to track navigation is a pain in the butt. `angular-routing` is the next best thing imo.

But the video does come with a *disclaimer*, that it should be used for the **right** use case, which at this point I'm not quite sure. Maybe it might fit, maybe not, but just like with the first iteration of SpecOps it might be another great learning opportunity to see where it can take us. Either way though as long as we can deploy to both Android and iOS then thats great! Else... sorry iOS :confused:

---

What do you guys think? Is this a good idea or should I stick to my other hobbies?
