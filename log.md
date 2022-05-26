# 100 Days Of Code - Log


### Day 32: May 26, 2022
**Today's Progress**: Day 30/31 of SoC Bootcamp, mindset, guest talk from Will Peaches SoC Director, recap of hosting databases on Heroku and connecting with node.js

**Thoughts on the day at bootcamp:**
- So today was better.  The entire day was basically a recap of what we did yesterday, but stripping bits out to focus on individually.  I needed this - I think we all did - and now I have a much better conceptual understanding of the moving parts
- This morning's mindset session looked at GROW and Humble Enquiry methods for personal growth and development.  Not gonna lie, Humble Enquiry sounded slightly like one of the circles of hell to me; would I try it if someone asked me to?  Sure.  Would I invite it upon myself?  Absolutely not lol  If I need help I want help, not an echo chamber.  I have enough racing thoughts, I don't need any adding in
- Then we had a talk from Will Peaches about designing data for making business decisions, which was really interesting.  I wish it had been longer as I think he could easily have filled more time, but yeah

**Thoughts on the 'coding':**
- Redoing some of the things from yesterday felt better today, having had the space and taken a step back with a much slower paced recap and more understanding of what I was trying to actually achieve
- Tonight I worked on refactoring a couple of my model functions and route handlers so that they talked to the database instead of the in-memory data, and I got them to work!  One of them took me approcximately ages lol  but I got there in the end and I feel like it stretched my javascript skills as well as my very new budding SQL abilities.  Such a good feeling getting things to work


### Day 30/31: May 24/25, 2022
**Today's Progress**: Day 30/31 of SoC Bootcamp, more PostgreSQL, guest talk from Ricky Birtles on Cyber Security, databases on Heroku, putting it all together

**Thoughts on the day at bootcamp:**
- SQL betrayed me.  After enjoying the introduction, I was rudely awakened to how complex SQL actually is when you start building queries
- Honest not got it in me to write tons, but today we had a short talk about Cyber Security which was cool - it's an interesting field even if right now the terminology mostly goes over my head - and then we moved on to putting everything together
- We span up a server with Express in node, created a database on Heroku, created and propogated the table using our server backend, and tested a query to see that our routes et al were working
- If I said it was intense I would be understating in the extreme.  Many people cried today

**Thoughts on the 'coding':**
- It was a lot.  It was...a lot lol


### Day 29: May 23, 2022
**Today's Progress**: Day 29 of SoC Bootcamp, introduction to databases and PostgreSQL, guest talk from Kyle Simpson

**Thoughts on the day at bootcamp:**
- Really enjoyed the introduction to databases and SQL, and from a very first look, the syntax looks much easier to get to grips with than Javascript, so...nice!  Obvs I fear this optimism will not serve me well lol
- Most of the afternoon was a guest talk by Kyle Simpson of You Don't Know JS (don't I know it) fame; really good talk, and a great Q&A session with some advice I really took to heart about looking at jobs and interviews, and reframing job specs/adverts to be a wishlist rather than a must-haves list

**Thoughts on the 'coding':**
- Not much coding today - just a little play on DB-Fiddle sending some SQL requests
- However, actually there was coding but outside of bootcamp (I'm just forgetting because lonnnnnnnng day).  I spent about half an hour looking at responsive CSS this morning, before some fellow bootcampers helped me out with the mess I got myself in trying to generate an ID.  Then tonight after bootcamp, I helped a fellow bootcamper with her models, and that felt great to be able to help someone :)


### Day 27/28: May 21/22, 2022
**Today's Progress**: Day 27/28 of SoC Bootcamp, weekend

**Thoughts on the day at bootcamp:**
- n/a

**Thoughts on the 'coding':**
- This weekend's recap tasks were to basically do the hackathon again on our own; I found a bug with the first DELETE request handler, so that was interesting and learned something fixing that (RE the arguments for splice()).  Still spent a good chunk of time doing it - maybe 5 hours or so on Saturday night
- Then Sunday I looked at the first bonus task RE splitting out code from the routes/users.js into models/users.js.  I'm not sure I fully get the concept and I hope it gets explained, but I managed to do it regardless and re-checked everything as I was going to make sure my requests still worked
- After that, I tried another bonus task of adding a generateUser(), but after about 3 hours I've admitted defeat.  I've googled, I've tried one thing, I've tried another...  Yeah - there's only so many times you can beat your head against a wall before it's unhealthy
- Overall, a rollercoaster.  Felt pretty good when I finished the initial task on Saturday, then felt awesome when I figured out the models this afternoon, but this function I can't figure out has brought me crashing back down


### Day 26: May 20, 2022
**Today's Progress**: Day 26 of SoC Bootcamp, Hackathon Friday!

**Thoughts on the day at bootcamp:**
- Today's hackathon was slightly predictable given then topics we've covered this week; we had to build an API backend with CRUD functionality
- My partner and I were quite proud of what we managed, particularly RE fixing the import/export syntax that had been setup wrong on the starter files provided for the task.  Myself, I was proud that I figured out the PUT request despite google failing me completely at every turn
- There were bonus tasks we didn't get to, and after scanning them I don't actually know where I'd start, so I guess that's something for me to work towards

**Thoughts on the 'coding':**
- I just watched a video of a Kyle Simpson talk where he said he cut and pasted and hacked at things for years of his career, and he's like a jasvascript guru, so I feel much better about that situation!  lol  There was a lot of copying and tweaking today, but it worked, so... :)
- I might do some responsive CSS but I am pretty tired and I want to make sure I don't burnout - I've felt a bit like that a few times recently and I know too-well the fallout of not looking after your health when work gets a lot


### Day 24: May 18, 2022
**Today's Progress**: Day 24 of SoC Bootcamp, still building simple APIs with Express in node, building on concepts and search abilities

**Thoughts on the day at bootcamp:**
- Taking our code from yesterday, we started to modularise is, splitting out the routes to their own folder and having the app.js file 'use' them
- We looked at making more specific get requests with queries and how to add search functionality to our route handlers
- We had an introduction to REST and what makes a RESTful API, with a basic introduction to CRUD request types

**Thoughts on the 'coding':**
- Again, there was a lot of copy/pasting today, but still do feel quite solid with the concepts, so I'm not fighting it.  We keep getting told syntax can be searched and copied and pasted, so yeah...
- With responsive CSS I learned that the fix I found with setting the height was unneccesary lol  But there you go.  I still managed to finish the challenge and make a responsive basic site!


### Day 23: May 17, 2022
**Today's Progress**: Day 23 of SoC Bootcamp, looking at creating a simple API with Express in node.js

**Thoughts on the day at bootcamp:**
- Good day today - didn't feel like everything went extremely over my head, which is always nice!  We used npm libraries and created a simple API, setting up get requests and listeners to return data
- Looked at CommonJS and ES6 syntax for import/export (require/module.exports)

**Thoughts on the 'coding':**
- It went ok today, but there was a lot of copy and paste so...I dunno, I'll take the win I think
- Worked on responsive CSS and managed to figure out a problem I was having setting the height on a div (needed to set the parent height as I was using %)


### Day 22: May 16, 2022
**Today's Progress**: Day 22 of SoC Bootcamp, introduction to node.js

**Thoughts on the day at bootcamp:**
- My new partner this week is great, we seem really on a level with our approach to things, so that's good as the last couple of weeks it's been a bit off in that respect (though working with nice people, just different mindsets)
- We started looking at node.js today, using functions and calling them to console log things, and using npm to access libraries and change the console log appearance with chalk

**Thoughts on the 'coding':**
- Going back to javascript after a week of UX UI was like being hit by a truck, not gonna lie.  Took quite a while to figure out some functions we needed to make, but got there in the end with quite a bit of help


### Day 20/21: May 14/15, 2022
**Today's Progress**: Day 20/21 weekend

**Thoughts on the day at bootcamp:**
- No bootcamp, but many hours spent on the recap tasks, starting to look at building my own site for me as a developer!  Putting all that UX UI goodness ot use and working on miro and figma to compile research and make wireframes

**Thoughts on the 'coding':**
- No coding really, but did do my responsive CSS course - got a bit stuck so waiting for the solution to be unlocked!  Not a nice feeling not being able to brain things :(


### Day 19: May 13, 2022
**Today's Progress**: Day 19 of SoC Bootcamp, former bootcamp guest speaker, hackathon Friday!

**Thoughts on the day at bootcamp:**
- Today's guest speaker was a former bootcamper who had so much energy compared to my tired, end-of-the-week-self it was embarassing lol  But it was great to hear from someone so upbeat and so positive about the job opportunities after bootcamp.  For someone like me - who knows exactly what they don't want to go back to - hearing that bootcamp puts you in such a strong position for getting a job is really a tonic
- Then today's hackathon!  Today we were designing a landing page for a business, following through from intial brainstorming of the business idea, to the user stories and journey, making initial low fidelity wireframes and then upgrading to high hidelity wireframes, then transfering to actual code.  This was a BIG project but honestly it was great.  The only bad moment was when our group and a little bit of a moment when deciding on colours...honestly, we were all very invested in our corners lol
- I got to work more on user stories and user personas, focussing on the UX side of things, before moving more to UI and working on the wireframes.  I made some leaps and bounds today with Figma and I was really pleased with what I was able to pick up and create.  Just goes to show, don't like something new intimidate you because it's complex - once you start working with it and breaking it down (and watching super helpful youtube tutorials) it starts to make sense.  And then the magic begins...

**Thoughts on the 'coding':**
- 2nd day of the responsive CSS course, and I learned about em and rem.  Useful stuff, and I'll be putting it to use over the weekend with the weekend tasks


### Day 18: May 12, 2022
**Today's Progress**: Day 18 of SoC Bootcamp, mindset session on Perspectives and Ideas, former bootcamp guest speaker on UI, session on Advanced CSS, and afternoon UI UX group workshop with presentation

**Thoughts on the day at bootcamp:**
- Joseph's Mindset sessions are probably my favourite part of the week.  EVery week he manages to somehow speak to me on a personal level and address something I'm having an issue with.  Today we talked about perspectives and ideas, and working with other people and groups, and how to better improve our interactions and communications by thinking generatively instead of positionally.  Great stuff, talking about how to let go of ownership of ideas so that they can flourish
- We then had a brief session on advanced CSS, which honestly, mostly went over my head...  It did however inspire me to start a course in CSS responsiveness - more below...
- Another guest talk, this time from a former bootcamper who now works in UI UX at Santander.  Her presentation was great, really backing up a lot of what we've covered this week and solidifying some of the concepts.  The former bootcamper talks are always doubly-inspiring because they've come from where we are now, and that's a really cool thing to see
- This afternoon was a group workshop and presentation, focussing on User Interviews (random selection from UXChallenges.com).  Honest, it was difficult; our group didn't really gel very welll and some people seemed disengaged.  But I tried my best, and I think what we managed was ok if not amazing.  I did learn some things about conducting and preparing user interviews from the research I did, and as I held an interview, I got firsthand experience of how it's actualy not an easy thing and would definitely be a skill to develop

**Thoughts on the 'coding':**
- No coding today, but as mentioned above, I did sign up for a 21 day CSS responsiveness course, and after bootcamp was finished I did the first day's worth of learning and challenge.  I'll crack this stuff, yet...

**Links to CSS challenges:** https://courses.kevinpowell.co/conquering-responsive-layouts


### Day 17: May 11, 2022
**Today's Progress**: Day 17 of SoC Bootcamp, guest speaker on UI, session on UI Design, and CSS organisation

**Thoughts on the day at bootcamp:**
- This morning's talk was from Luke at Intermediate, and it was nice to get another inside look at someone in the profession - this time someone working in a bigger organisation and with a different team and working structure than previous.  It's really great getting insights from these people and seeing a snapshot of the variety that's out there, as well as motivating that they really don't see lack of experience as a barrier
- We started looking at UI Design, creating low fidelity wireframes in Miro and then moving onto high fidelity wireframes in Figma.  To be honest I'm finding the week quite difficult as my partner doesn't really collaborate with me much - she either does things on her own when we're meant to work together, or redoes things we do together which invalidates my time and effort and just makes me feel like there's no value to what I'm doing.  I know internally there is, but the feeling isn't good.  If this were a professional environment I would raise it but we only work together for a week, so I'm just making the best of it and trying not to be too demotivated.  It does really send home the fact that it's important how you get on in teams and how you conduct yourself
- Difficulties aside, I quite enjoyed the wireframing; Miro was easier to get going with than Figma, but I think that just echoes the depth of the applications.  I'm finding UX UI interesting, but I do confess to missing coding (and also worrying I won't remember how to code when we go back that way)
- For the final part of the afternoon we looked at CSS organisation, and I quite enjoyed that.  I'd watched videos that sort of went over it, so I felt like I had a bit of an understanding already, and that was nice for once!

**Thoughts on the 'coding':**
- No coding today really, aside from a mini-Codewars session before our guest talk.  But yes, learning about new things in the tech sphere is still good 


### Day 16: May 10, 2022
**Today's Progress**: Day 16 of SoC Bootcamp, guest speakers from Nester on UI/UX, session on UX Design Thinking, and CSS variables

**Thoughts on the day at bootcamp:**
- Today we started the day with some Codewars, which admitedly isn't my favourite thing.  I did level up from kyu8 to kyu7 though so...yay me?
- Then we were treated to a guest talk from the CFO (I believe) of Nester - a peer to peer lending platform - and their UI/UX guy, Alex.  It was a really interesting talk, and found the information around portfolios and employer desires really interesting, alongside everything else
- We then had a morning session arround UX Design Thinking, looking at the 5 stages, and then encompassing Disney Ideation.  In our pairs, we picked an idea ofr a bootcamp and focussed on the application process, looking through in the various stages from empathy, define, create, prototype, and finally to test - but also taking into consideration the Disney principles.  It was interesting but certainly a new way of thinking, and perhaps not something that was quite natural in some repects
- This afternoon carried on with that, and then we looked at CSS variables and did a nice little workshop to work with those, including making a dark mode feature for a website.  REALLY enjoyed that - it felt like something I understood quite quickly, in contrast with how other things have taken longer

**Thoughts on the 'coding':**
- Again, really glad I worked on CSS because today built on it nicely.  From being really a bit scared/overwhelmed by the idea of CSS, I've grown to really like it just these past few days - goes to show that eating the frog is sometimes what it takes


### Day 15: May 9, 2022
**Today's Progress**: Day 15 of SoC Bootcamp, an intro to UI/UX and Agile

**Thoughts on the day at bootcamp:**
- So today started great with a guest talk by Paavan from And Digital, 'Do U(X) Believe in Magic?' - such an engaging and informative presentation.  Also he did some magic tricks and blew everyone's minds!  But yeah, UI/UX are completely new topics to me, and his presentation made them really understandable and accessable concepts
- We then had a session in the afternoon about Agile working vs. Waterfall, and the fact that there are tradeoffs between them but that Agile really is better suited to software development
- I met my new partner for the week, Cloe, and we did some spot the difference, looking at design features and starting to train our UI/UX eye
- We also, for some reason, were tortured by having to recreate the google home page without any tools, google, previews - basically just in a markdown style file, writing CSS in a style element and updating the html.  Honestly, it was a bit like, what?  But you know what, I was actually impressed with how much I kind of had a handle on.  Don't get me wrong, my attempt was pathetic, but it only took me five minutes after we were allowed to preview what we'd done for me to be able to fix it up a bit and get something that looked like google!

**Thoughts on the 'coding':**
- Really benefited from yesterday's CSS session in the google task today, and I was really pleased with the timing and confirmation of that
- Otherwise didn't do too much actual coding, but was good to expand the tech horizons with new concepts and areas of study


### Day 14: May 8, 2022
**Today's Progress**: Day 14 of SoC Bootcamp, weekend yo

**Thoughts on the day at bootcamp:**
- No bootcamp, but worked on weekend recap tasks bonus bonus bonus, ft. CSS

**Thoughts on the 'coding':**
- Another proud of myself moment.  CSS was becomming a bit of a bogeyman for me, but you know what?  I ate that frog.  I worked through the Flexboc Froggy game, and then I sat and worked with CSS on a couple of the weekend recap tasks
- I know have a prettily obnoxious cat pic generator which I love and keep going back to click, as well as a priority list maker with what I think is pretty nice styling actually...  I mean, it's got an obnoxious flare because that's how I roll, but it's elevated-obnoxious, yo

**Link to CSS challenge:** https://flexboxfroggy.com/


### Day 13: May 7, 2022
**Today's Progress**: Day 13 of SoC Bootcamp, weekend yo

**Thoughts on the day at bootcamp:**
- No bootcamp, but worked on weekend recap tasks

**Thoughts on the 'coding':**
- I'm so proud of myself lol  I worked on the recap takes last night and then again tonight, and though what was supposedly 2 hours of work has taken me approx 6, I don't care.  I mean...well I do, coz I'm tired and it would be nice not to be slow lol  But I'm so proud of what I've managed to do
- Basically been using the things we've learned this week and then expanding out, so async functions, creating arrays and pushing to them, creating objects in array, checking handed in values meet criteria, creating elements, event listeners...
- But yeah, I haven't had any help except one confirmation I was on the right track from Hannah (bootcamper), and a whole heap of googling, and I've managed to complete everything apart from the Bonus Bonus Bonus, which is CSS
- This is intentional, as I've already identified this as something I want to work on, so that's my goal for tomorrow and Monday morning (we have a late bootcamp start) 


### Day 12: May 6, 2022
**Today's Progress**: Day 12 of SoC Bootcamp, Hackathon!

**Thoughts on the day at bootcamp:**
- So today's Hackathon was utilising API fetch results, and we got to choose what API and what we made with the data that was returned.  My partner and I chose a Pokemon API and decided to make a Pokemon Battle game, like a card style game
- The plan was intially quite ambitious, and due to problems accessing the results of our fetch requests, we actually ended up scaling a lot of it back.  HOWEVER, my partner ducked in on a coach explaining something about this problem to another group and from there we were able to expand the functionality back out in our game by turning our data into arrays we could access outside of the function
- We used lot of features like async functions, for loops, if statements, fetch requests, query selector, creating new arrays, setTimeout...  All things I'd either never head of of barely understood at the beginning of this week
- The CSS was mostly my partner's handywork, but I did have some helpful input with a problem we had with the images shifting
- In the end, we had a functioning game and I was pretty proud of us, tbh...  We had to do a 2 minute presentation, in which I gave a general overview to how we started the project and our main issue with the data before we could build in the functionality.  I feel I was probably short of a minute, and it would have been nice to have control of the screen (but we shared Matt's as the layout was better to present), but I did ok.  Room for improvement

**Thoughts on the 'coding':**
- We hit a NUMBER of problems, but you know what, we worked through them all and I was really proud of my project/time management skills.  Not really coding, but important to the building/project process
- The coding we did was really advanced, and I definitely learned things today with math.random, and with async functions
- I really want to spend some time with CSS as I have really limited experience and practice with that


### Day 11: May 5, 2022
**Today's Progress**: Day 11 of SoC Bootcamp, mindset session on cognitive behaviours (personality types) and Javascript fetch

**Thoughts on the day at bootcamp:**
- Today we started the day with a mindset session and I really enjoyed it.  I think these are so beneficial and I think the delivery is great - we looked at how to work with people of different personality types; the kinds of clashes that might occur and how we can try to co-elevate
- We then had a short session about navigating data, looking at navigating the DOM and touching on fetch.  We then had a worshop to practice moving around objects and arrays, using dot notation and bracket notation, and then performing functions with data we navigated to (EG finding qualities about people and presenting them in sentences, or displaying a given person's email)
- The afternoon was a different vibe, and we were given a task/challenge with minimal instruction where we needed to interpret it.  It was essentially a coding escape room, where we needed to employ fetch to bring in data, and then look through that data to find a code to post back to the API.  Honestly this wasn't very fun because my partner and I took the wrong tactic and spent a lot of time doing stuff we didn't need to - then by the time we got pointed in the right direction we struggled to get into the fun of it.  But lessons were learned, and I would definitely know in the future to really sit back and question whether things were being over-complicated

**Thoughts on the 'coding':**
- The pair-coding went a little better today, but I'm still struggling to know WHAT I need to code to achieve things, which makes planning difficult
- The fetch process is interesting, and introduced JSON, which I feel like I will definitely need to learn more about as it seems to have different syntax and requirements to the JS ones I'm slowly getting used to


### Day 10: May 4, 2022
**Today's Progress**: Day 10 of SoC Bootcamp, more events in JS and an intro to APIs

**Thoughts on the day at bootcamp:**
- The pace today took a little step back, with the morning being largely a recap of what we covered yesterday, which I really appreciated
- We then started to look at asynchronicity with setTimeout and setInterval
- The afternoon session introduced more concepts that looked at asynchronous coding with JS, looking at using fetch with APIs (and introducing APIs)
- My partner and I actually finished the workshop tasks in the workshop time (first time that's happened for me!)

**Thoughts on the 'coding':**
- I actually don't feel like I picked up much code today sadly, a lot of that was a bit over my head, I do however, feel like I understood the concepts, and I think maybe that's a win in itself
- I'll definitely need to look more at how things are achieved with the coding when using async functions and etc...  Functions...  *sigh*


### Day 9: May 3, 2022
**Today's Progress**: Day 9 of SoC Bootcamp, the DOM and events in Javascript

**Thoughts on the day at bootcamp:**
- The day started really well with a guest panel of past bootcampers who all now work at Wise.  They were a lovely group of people and listening to them was so relatable, especially Joy, whose comments I adored and who made me feel so much better.  Lots of reassurance about sticking with it and about imposter syndrome being normal
- THEN the morning session introducing the DOM...  Well.  Yeah.  That was interesting.  I definitely need to finish reading the article on it, and maybe find a youtube video in the morning, because I still don't really get it
- THEN the afternoon session compounded my lack of understanding about things we'd covered by going over events in Javascript.  Some of the things spoken about actually made sense, but dealing with them in code was a whole other thing
- It was a really long day, and after that I had a meeting with my lovely mentor, Aidan - and felt bad because I had a headache and was trying to be engaged and not a numbskull.  Hopefull it worked.  We chatted a good hour, in which he reassured my about some industry questions I'd had, and he'd prepared a little demo to explain CSS positioning to me, which I thought was really sweet and thoughtful.  Having a mentor so willing to help and so aproachable is really great
- After the meeting it was back to Zoom to try and finish off the day's tasks...  I'm not gonna lie, I'm exhausted, finally getting off Zoom at about 8:30pm

**Thoughts on the 'coding':**
- I did some freeCodeCamp this morning on Javascript to try and just sink some basics in a bit more, I think some things are getting clearer
- The new stuff we did today with the DOM and events...I'm witholding judgement, because I felt lost but I also by the end of the forever-Zoom, felt like some bits were starting to go in...


### Day 8: May 2, 2022
**Today's Progress**: Day 8 of SoC Bootcamp, Bank Holiday Monday woo!

**Thoughts on the day at bootcamp:**
- No bootcamp today, but looked again at the tasks we were set, with some Codewars and freeCodeCamp

**Thoughts on the 'coding':**
- As above really...spent about 4/5 hours looking at things, but honestly they didn't feel like very productive/successful hours.  I think I need to move on from things that completely baffle me before sinking so much time into being lost


### Day 7: May 1, 2022
**Today's Progress**: Day 7 of SoC Bootcamp, but it's a Sunday so...chillin

**Thoughts on the day at bootcamp:**
- Gonna start nil-ing these bits on the weekend, apart from stuff like today where I helped another bootcamper on Zoom for a while with something they were stuck with (getting a password to limit at 10 characters)
- Felt good to feel helpful

**Thoughts on the 'coding':**
- I didn't do the freeCodeCamp I'd been planning on doing, but instead I started looking at and working on the Codewars katas we've been set.  I managed to do 3 of them but 1 of the initial 4 we were set was baffling.  I've got a video I'm going to watch on it tomorrow and hopefully I'll be able to follow that through
- I did see a feature on Codewars to 'practice' and apparently you can focus on a specific bit to do the katas on, so that might be good - I will investigate more tomorrow


### Day 6: April 30, 2022
**Today's Progress**: Day 6 of SoC Bootcamp, it's the weekend but there ain't no rest for the slow

**Thoughts on the day at bootcamp:**
- No bootcamp on a weekend, but the spirit was there; worked on finishing the tasks from the week that I hadn't completed, between 15:30 and 21:15.  So when I say there's no rest, I mean it
- I was struggling BIGTIME refactoring some code into a function, but thankfully a call for help was answered on Slack by the awesome Matt D, who took some time out of his Saturday night to go through the mess I'd created and help me shape it into a FUNCTIONing password checker
- Prior to getting stuck bigtime, I'd actually been feeling pretty pleased with myself...just goes to show, never be happy folks, it's an illusion

**Thoughts on the 'coding':**
- There are some things I'm picking up but definitely others I'm struggling with.  But you know what?  I look at what I've accomplished in the last few days and sure, I could beat myself up about it taking me forever in comparison to others, but f*** that - I'm pleased with what I've been able to do.  Do I wish I could do more?  Sure - but that's pretty standard of life so whatever
- Tomorrow I'm going to look at freeCodeCamp and really focus on functions, loops, and if statements
- Depending on how long that takes me, the plan would then be a bit of Codewars (which scares me, because last time I looked at that I hadn't got a clue what was going on)


### Day 5: April 29, 2022
**Today's Progress**: Day 5 of SoC Bootcamp, first Hackathon!

**Thoughts on the day at bootcamp:**
- Today was our first Hackathon, where we spend all day on a project to then discuss and look over at the end in a group
- Abdi and I did pretty well and I was happy to get the functions going at the beginning, but some of the later stuff was new and/confusing...
- Not gonna lie, I had a little cry at the end of the day when not for love nor money could I get something to work.  Hamza (coach at SoC) spent a bit of time with me after the wrap up and helped me, and I really appreciated it (I didn't cry on Hamza btw, it was a private cry lol - don't worry, he's fine)
- Also had an into meeting with Rikia who's my enablement coach; was a nice little chat and he was really reassuring.  Did feel bad I apparently gave him the worst confidence score (2.5 out of 5) from his group, but I'm a truth-teller lol
- Was quite upset we had weekend assignments to do, as I can see at my pace I won't have any time off :disappointed: I was going to be looking at stuff anyways but yeah, now I feel quite pressured.  Life is hard, yo

**Thoughts on the 'coding':**
- Javascript will always be a lot, but when you get something to work the feeling of pride is immense
- I forked the Hackathon afterwards to work on it on my own to try and progress, and I did some on it this evening and got another couple of tasks done, which made me feel much happier and less wobbly


### Day 4: April 28, 2022
**Today's Progress**: Day 4 of SoC Bootcamp, more Javascript and some mindset coaching.

**Thoughts on the day at bootcamp:**
- This morning we had our first mindset session, focussed on feedback, and I found that really good and timely after a pretty tough day yesterday
- We discussed the Hero's Journey, which reconated HARD, and also the good and bad way of giving/receiving feedback
- We recapped yesterday's Javascript then moved on to looking at Objects and Arrays; felt kind of ok on Objects until I didn't (lol) and Arrays...not so bad until starting to work with them and loops (While and For)
- Am pleased with the fact that I have learned some stuff, but still feel like a lot of stuff is going over my head
- Need to focus more on the computational thinking and breaking things down...may also need a new brain coz this one's tired and it's only Day 4 lol

**Thoughts on the 'coding':**
- Javascript continues to be a lot, but I do like it
- Loops, I do not like
- I had a look at Codewars (which I managed to finally get onto by passing the test) but the training exercises are all like WHAAAAAAT?  So I think I have some ways to go before I'm going to be able to be effective there
- I'm going to have a look at some youtube and try and get more of a handle on Loops


### Day 3: April 27, 2022
**Today's Progress**: Day 3 of SoC Bootcamp, started looking at Javascript.

**Thoughts on the day at bootcamp:**
Going to make these a little more succint because words...
- Started to look at Javascript and tbh, a lot of it went over my head.  We worked on a password checker and I think if we hadn't had some help from the very clevel Brycen, we'd still be scratching our heads
- Had the worst headache ever by the end of the day
- Met with my mentor and had a really good conversation; he's a really nice guy and what he said was a real comfort after a somewhat meh day of feeling like the worst coder ever

**Thoughts on the 'coding':**
- Javascript is a lot
- Loops have me foxed: I went and watched a handful of videos that night and tbh I'm not sure how much I gleaned from them
- I still felt itchy about the CSS positioning, so I watched some more on that, and while I am far from knowing what to do, I do understand it a little better

### Day 2: April 26, 2022
**Today's Progress**: Day 2 of SoC Bootcamp, worked on CSS koala and git/GitHub push-pull.

**Thoughts on the day at bootcamp:** The morning session covered a recap of html layout, the concepts of tags and requirements for instructing the computer.  We looked at VS Code - how it works, the terminal, some of the features.  There was a talk about code vs. programming vs. software engineering, and an intro to the concept of DRY (Do not Repeat Yourself) and making things as simple as you can - avoiding repetition.  We looked at the Netflix site and Chris went over how it could be broken down into parts so that the idea of creating it wasn't really that intimidating, and then Abdi and I looked at the Amazon site and did likewise.

Abdi and I did some more pair coding, trying to replicate a koala in CSS.  We were supposed to be looking at the principle of breaking things down, so we went about that by first trying to create some of the shapes we needed, before tackling their positioning.

The afternoon session was focussed on using git and GitHub, practicing the rhythm of add - commit - push - pull.  Chris then gave a recap as quite a few of us were finding it tricky.

I'd made a mistake in the morning by creating a repo in my root folder, so I spent a bit of time panicking and sorting that out, but hopefully I've now learned and won't be doing that again!  Was very tired by the end of the day, but at least I looked it and my mum offered to get fish and chips lol  Win?

**Thoughts on the 'coding':** We didn't do too bad with the CSS koala but I'm not understanding the positioning of elements so I'm going to go back over that with some youtube tutorials I think.


### Day 1: April 25, 2022
**Today's Progress**: Attended Day 1 of SoC Bootcamp, worked on some CSS challenges we started during the day.

**Thoughts on the day at bootcamp:** The morning session gave us all an introduction to School of Code and set out the principles it's founded on.  It resonated with me so much I went downstairs at lunch and told my mum, and honestly was a little emosh.  I wrote down something Chris said because it really struck a chord: this is about "becoming the type of person you want to become".

That's exactly it.  But anyways, not to get too deep...

I also met my 'pair' - Abdi - who seems very nice.  We had a chat to get to know each other, and then later on tried a bit of pair-coding.  That's a little strange to start with, just because it doesn't feel quite natural I suppose, but we did ok!  We looked at CSS selectors, but the exercise was more to get us into the dynamics of working together than the coding itself.

We also met other members of our group, which I think will be the group we work in going forward.  It was a bit strained at first, and honestly I think that maybe we just need more time to 'gel'.  But everyone was nice, and we're all here for the same reason - we even wrote a poem about it lol  (it was a task given to us, we didn't just to off on one and decide to get whimsical)

The afternoon session was focussed on an introduction to the SoC way of thinking - computational thinking - and the idea of breaking things down into more manageable and approachable tasks.

Horse-sized duck, or 100 x duck-sized horses?  You had to be there, but it was a fun conversation.

Honestly, as it got toward the end of the afternoon I really started to feel tired.  We hadn't really done much that was technical, but this whole day was something new and a different experience, which in-and-of itself was surprisingly taxing.  Plus, I hate being on camera and I think I made myself extra tired by trying to look innocuous instead of resting-bitch-facey all day...

**Thoughts on the 'coding':** I've only done very basic CSS so far as part of the pre-learning for the bootcamp, so a lot of the things I saw today were new to me.  As we were working in a pair/group during the day, occassionally I felt things escaped me a little, so I wanted to go back over this myself.

**Links to CSS challenges:** https://flukeout.github.io/ and https://cssgridgarden.com/


<br>
<br>
*I'm leaving the examples here so I can see the format.*

### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
