---
layout: post
title: WhichHire
---

I took part in [Static Showdown](http://www.staticshowdown.com/), a 48 hour hackathon featuring static web apps the weekend of January 24/25, 2015 and built [WhichHire](http://www.whichhire.com)

![WhichHire](/img/whichhire-logo.png "WhichHire - Filtering UnderDog Candidates")

Although I coded WhichHire by myself, I have to give a shout out and thank y you to [@jeaninehender](https://twitter.com/jeaninehender) for creating the logo

Before the hackathon I was trying to hire and used [UnderDog](https://underdog.io/) to get access to candidates. If you are unfamiliar with UnderDog, basically they connects candidates with startups by using human intelligence and technology. UnderDog reviews and ranks applicants and sends hand-picked candidate batches to companies. UnderDog sends these candidates via an email with an attached JSON file of the data. 

Each time I received one of these emails I would review the candidates, but wanted more of a workflow and came up with the following steps:

1. Read each candidates info and checkout their personal and social links - **Add Candidates**
2. Select that individual or move to the next to build a list of qualified candidates - **Select Candidates**
3. Reach out to these qualified candidates via Email - **Contact Candidates**

I took this blueprint and started to think of how I could create a simple static wizard as part of the Static Showdown, dare I say kill 2 birds with one stone. Let's Take a look.

##Step 1 - Add Candidates

![WhichHire](/img/whichhire-add.png "WhichHire - Add Candidates")

You could either add them individually 

![WhichHire](/img/whichhire-add-user.png "WhichHire - Add User Candidates")

or you could add the JSON file from UnderDog - or if you just want to test, click the mock data as it uses [RandomUser.me](https://randomuser.me/)

![WhichHire](/img/whichhire-add-json.png "WhichHire - Add JSON Candidates")

##Step 2 - Select Candidates
![WhichHire](/img/whichhire-users.png "WhichHire - Users Candidates")

You can select a individual user or load the first one and use the right arrow key to go to each of them one by one.

![WhichHire](/img/whichhire-user-modal.png "WhichHire - Users Modal")

If you like the candidates you can "Select" them and continue on

![WhichHire](/img/whichhire-select-user.png "WhichHire - Select Users Modal")

Once you selected your candidates you can move to Step 3 

##Step 3 - Contact Candidates
Simple mailto link so you can just click and open in your default mail app.
![WhichHire](/img/whichhire-contact.png "WhichHire - Contact Candidates")


>Although I want/wanted to build a full blown HR app, doing a static hackathon limits what you can build in 48 hours and with what tools

![WhichHire](/img/whichhire.png "WhichHire - Filtering UnderDog Candidates")

|[Please Take WhichHire for a spin](http://www.whichhire.com)|

