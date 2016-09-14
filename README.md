# KivaTeamApp

Investigating the possible development of a Kiva mobile app. As of now, I am envisioning an app where lenders can interact with their lending teams. For lenders that haven't joined a team yet or want to join more teams, they can get suggestions/guidance on teams they should join. Once these lenders become more involved in their teams, they (along with lenders that are already active on teams) have a mobile-optimized (lending team pages are currently not mobile-optimized) and streamlined place to look at team messages and stats. Rather than checking their email for team digests, they can simply receive push notifications on their mobile phone and browse on the go. 

Kevin's Roadmap: 
1. Validate your hypothesis that an app doing X will be useful/desired by some users
  - Read through team messages and jira tickets to see what users want
  - Talk to the product interns
  - Maybe ask a few people directly if they would use an app that did X if it existed
    -Get in touch with Lending Team Captains Nancy Summers and Susan ____ (don't know last name)
2. Create a rough wireframe of what your app's main screens would look like
  - A great tool for this in InvisionApp but can be as simple as Paint or plain ol' paper
  - Make sure to note the things that when clicked on will do some action
3. Show your wireframe to some folks to validate that it is what people are thinking the want
4. Decide if you are going to build a working prototype and if so choose an app builder
  - Compare free non-coding app builders: AppMakr, Appery, GoodBarber
  - Compare coding app frameworks: Ionic, Electron, React, PhoneGap
5. Try to produce a MVP, just the minimal amount that someone would actually try out the app and use it.

Features:
- Push notifications: 
  - Probably the most important aspect of the app. 
  - Push notifications can replace email digests of team messages, reucing email clutter 
  - remind inactive lenders to participate
  - Must decide how much push notifications to include, i.e., should users have the option to get all notifications, unrelated to teams (such as, "You have more Kiva credit to loan!") through the app?
  - Have to be careful not to push new lenders away with spam notifications
- Interact w/ other lenders on teams, manage your teams
  -Simple design to look at team messages (basically, the current Activity Feed but in mobile-form) and team pages 
- Browse new teams
  - If user hasn't joined any lending teams yet, prompt them with some categories to choose from 
  - If there is any way to narrow down (beyond what is already available on the main site) available lending teams, include this. Would probably involve lots of tagging of teams of some sort, not sure if this is very feasible

Questions to Address:
- Extent of push notifications: how much is too much?
- When a message links a loan, how do we manage that interaction? Do we include browsing loans on the app or is it taken to a separate web app or is the web browser embedded in the app (but not handled by the app).
- Similar to the problem of loans, do we also have all the lender profile data (for team members) available on the app?

InVision:
https://invis.io/S38E081Z6 link to inVision prototype app 

Some feedback from others:
- Brandon:
  - include new features that aren't already available on the web version
  - for example, a "reply" feature to reply to another member, and directly notify them
-Nancy, lending team captain of A+:
  - doesn't usually lend on her mobile phone
  - "would the app be connected to team message boards?"
    - yes – probably the main function of the app
  - "would it be connected to directly lending on the website?"
    - probably not directly – i.e., when a loan is mentioned, it takes you to the web. Or the web service is directly embedded in the app – Kevin O'Brien: thoughts on this? Would it be easier to take you out of the app to a web app or just put it inside the kiva app?
  - discussion within the group of a chat program to use? 
    - could be slightly alleviated by the addition of a reply feature
- Susan, lending team captain of Flying Spaghetti Monster team:
  - wary of making financial transactions on the phone –> not someone who would use a mobile app, probably
  - many Kivans disable emails: technically, they aren't being spammed, but they also aren't getting the messages being sent by other people
    - this is where push notifications come in: get a ding when you have a message, but doesn't go directly into the email so your email isn't clogged. Could toggle the notification preferences as well, so technically users could turn off those notifications as well, but hopefully having the lending team messages in a separate place encourages users to leave it on.
  - lender message threads: (not sure *exactly what this entails)
    - would be a great feature to add though
  - emails when people get repayments
- Abe:
  - ideally, whatever app you create will lie at the crux between a business-oriented goal and a user-oriented goal, meaning the app must be worth investing in for the business but also wanted by the users

Google Form
- Form to be sent out to current Lending Team users: https://docs.google.com/a/interns.kiva.org/forms/d/e/1FAIpQLSeRDGm1tEYRJbJWekFAToP6mGkCfBQxnXv9wZ9DnA3oEuZx9w/viewform (feel free to take the survey if you have feedback on the app)

Results from Google Form
- Out of 20 users who replied to the form we sent out, 90.5% responded that they used desktop for all Kiva-related activity, including looking at/interacting on team pages. Most of the respondents were not enthusiastic about the creation of a Lending Team App. In response to the question "If a Kiva Lending Team app existed, how likely would you to use it?", users answered:
1 (Not at all)	(7 users)	33.3%
2	(2 users)	9.5%
3	(8 users)	38.1%
4	(2 users)	9.5%
5 (Would download immediately)	(2 users)	9.5%
The most repeated feedback from respondents was that they preferred Kiva to improve the Lending Team pages on mobile rather than create an app. Other feedback included:
  - Easily jump between teams
  - Ability to link to lending
  - Have a general feed for the overall Kiva community, not just for specific teams
  - Have an official Kiva notifications / discussions section, e.g. to promote things like this survey to the whole community that goes to all lenders, not just to team captains
  - See team stats
  - notification of new messages
  - see borrower info & click links (to borrowers)
  - good statistic tool
  - Browse and join other teams; view team stats (current and historical).
  - Portfolio distribution
  - PLEASE make teams more obvious on the website as previously. Can't imagine anyone finds them now.
  - I would love if there was something to show that You've Got Mail. I get too many emails from Kiva and it's easy to miss a lender message.
  - fast messaging with group members
  - Bolded items are directions we could take now on the website and/or mobile site to improve user experience.

Conclusion
- Based on the feedback received in the survey, I have concluded that developing a Kiva Lending Team app is probably not the best use of time right now for Kiva. It would be much more worthwhile for us to improve the Lending Team pages on mobile first and further down the road look into creating a more general-use app. 
