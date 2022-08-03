# 100 Days Of Code - Log


### Day 100: Aug 2, 2022
**Today's Progress**: Day 100 of SoC Bootcamp, project and backend

**Thoughts on the day:**
- It's day 100, bitches!!!  Hahahahaaaaaaaaa I'm done!
- No but seriously lol  I find keeping a diary really hard - it's never been my thing - and I'm glad that I got to the end of this but I'd be lying if I said I'd enjoyed it lol  Still, I think it's great to have this to look back on, and I actually think I'll try and keep it going intil the end of bootcamp in a few weeks, as it's been more than the 100 days challenge for me because it's been chronicling that journey
- We put together backend today and setup a Heroku database, then realised the frontend pair working on the component that uses it had changed the data structure, so...funtimes
- In the evening I worked some more with my AMong Us portfolio and battled with transparency on image backgrounds, realising I'm an idiot because I thought the background wasn't changing when actually I was forgetting the button background. Doh


### Day 99: Aug 1, 2022
**Today's Progress**: Day 99 of SoC Bootcamp, project and deployment

**Thoughts on the day:**
- Today was a good day with the team; we merged everything into development and then to main, and then we deployed with Netlify.  We had two errors I was able to fix straight away after my Saturday of deployment hell (so I felt ace about that) and like magic, it was live!  There were a few bugs with android vs apple, but we solved a couple of them, and the other is to look at still
- We switched up a bit and I worked with Amanda on some styling; it's nice seeing pages come together even if a lot of it is fighting things into place lol
- Afterward I worked on my Among Us portfolio a bit more and honestly it was a train wreck - I don't know how I managed it but I broke the CSS so badly I thought I was losing my mind.  It was doing stuff I'd never seen before lol  But in the end I stripped it all out and started over, and I finally got somewhere :)
- Had a terrible headache all night though, and I think I need to learn to step back earlier


### Day 97/98: Jul 30/31, 2022
**Today's Progress**: Day 97/98 of SoC Bootcamp, weekend!

**Thoughts on the day:**
- This weekend I was super awesome :)  I finished the last couple of pages for my mental health app and then I deployed backend with Heroku and frontend with Netlify - and that makes it sound simple and easy but it was ANYTHING BUT.  It took me literal hours of googling error after error on failed builds; adding procfiles and redirects, making dotenv a production dependency, tweaking this, amending that...  I was so damn proud of myself once I got it up though :)
- I shared the link with Katie, Brycen, and Rory (who asked via Katie to see it) and they gave me some great feedback.  I fixed a couple of small issues, and I have a list of improvements I want to make (which were half in mind already), but repsonsiveness is the main thing, which I already knew.  Feel like that's gonna take me a while...
- Then on Sunday I put together a portfolio front page (a jokey one but I absolutely love it) using tsparticles, which wasn't as easy as the youtube tutorials made it out to be!  But I got it working and now hopefully I'll be able to make the serious version with stars :)


### Day 96: Jul 29, 2022
**Today's Progress**: Day 96 of SoC Bootcamp, project

**Thoughts on the day:**
- Today was a good day; Mat and I finalised the Exchange component pretty much, and we moved on to the Emergency Contacts.  We looked at an API but the results it gave weren't great for accesibility and the format was unreliable, so we're going to go down the route of having a backend database.  I prefer this tbh - just feels more rounded and also we control the data going in
- We did some team building on Scribblio and it was hilarious - Jed is terrible at it, and we all just had a well-needed laugh
- Right in the middle of that (ofc) Nadeem came in to have a check on us and see how we were doing, and he seemed pleased with what he found so that was reassuring.  He asked where we were with deployment (which I had been trying to get us to) and the team said they'd decided it was a stretch goal, and he basically shot that down and said "do it" for which I will be eternally grateful lol
- So far the app is coing along well, though there have been big issued with accessing the data from the weather API for the Forecast page, but yeah other than that I think we're all quite pleased
- In the evening I worked a bit on my mental health app and started on the last couple of pages


### Day 95: Jul 28, 2022
**Today's Progress**: Day 95 of SoC Bootcamp, project

**Thoughts on the day:**
- Bit of a struggle this morning merging our branch because of a conflict with package.lock.json - in the end I had to delete my file and merge, and then we were able to sort it
- Mat and I continued working on the Exchange component and FINALLY got the graph working with dynamic data!  Woo!  I was really pleased because I figured out how to drill down into the results coming back from the API to get the arrays we needed to pass to the graph :)
- We had some conversations in the afternoon about reiterating on our design and made the call to remove the search bar off the homepage as it's incredibly unlikely we'd be able to make it do what we would like (set the state for all pages), having had so much difficulty in setting the individual states because of what APIs expect and etc, so now we're heading with a larger banner image with an ACTUAL image and I'm really glad because I think this will look better anyway
- Thinking more and more we need to deploy but I think it's a conversation for Monday next week.  Also thinking we need to look at the authorisation aspect again and really try to get that
- Worked a little bit more on my portfolio but achieved nothing; was playing with displaying transforming images but didn't get anything that looked very nice.  I'm going to work on this over the weekend and look at Framer Motion
- I had to speak today in the standup meeting and at retro of retros, so yeah, I consider that some personal growth (even if I thought I might die)


### Day 94: Jul 27, 2022
**Today's Progress**: Day 94 of SoC Bootcamp, project

**Thoughts on the day:**
- Drama this morning, as someone had gone off on their own at night to work on a feature and installed a massive library dependency that we'd said we were going to discuss because we weren't sure we wanted to use it - this then also caused problems with another team member who git pulled and suddenly had a load of errors because of that library clashing with the one already in use.  Was an uncomfortable morning and we lost time fixing it and peeling it out, and the person responsible didn't take it well and at retro blamed lack of clarity in communication...  Funny, because we spoke about NOT doing everything they had done...but you do you, boo.  It's also in our manifesto not to work on things alone because we work as a team.  And we all decided the manifesto together, in one of our many many group chats/sessions
- So it was another day with our Exchange component, and we got the conversion working and installed Chart.js to start looking at that - had a bit of toing and froing about faker (a dev dependency that gives you fake data to display a chart) but it was fine when we installed it and we were able to see what a graph would actually look like on the page!
- Some struggles with API data and API keys; we keep getting blocked, so we created some dummy data using a Postman request to copy it as we couldn't copy and paste from the console
- Overall going well but can see accessing the data for the chart dynamically being difficult


### Day 93: Jul 26, 2022
**Today's Progress**: Day 93 of SoC Bootcamp, project

**Thoughts on the day:**
- We started coding!  At last! lol  I intentionally picked a trickier component because one, I wanna get the harder stuff done earlier if we can, and two, I figure I'll learn more or experience more
- We used a spinner to pick groups to split into pairs and I was kind of relieved with who I got - we get on ok and we started working on the exchange component, having little mini celebrations whenever something appeared on screen lol  Never gets old
- I managed to figure out a tricksy mathsy thing with a UNIX timestamp and converting it over to the format we needed, which was 😎


### Day 92: Jul 25, 2022
**Today's Progress**: Day 92 of SoC Bootcamp, project and guest speaker Gunnar from Capgemini

**Thoughts on the day:**
- Today we made our final design choices on the high-fi wireframes, and then discussed our tech stack and components. We setup a trello board for tickets and started to log what tickets we could see, then from tomorrow we can start working on these and hopefully have minimal clashes with Github and merging and etc
- We have a long talk from Gunnar about interview tips and advice, and though a lot of it (to me) was common sense (I've done a lot of interviews, I'm old) it's still good to go over that stuff
- I don't feel I'm the best fit in my team; it feels like my opinion is always opposite to everyone else's and I get not shot down but yeah...it feels pointless me speaking to be honest so I sort of disengaged a bit today. Might not be the best thing but at a point you have to protect yourself and it was getting really negative
- I did a little bit of fixing on my mental health project after the end of the day, just changing some styling points and fixing a bug I'd noticed with one of the return links - flex was putting a div over the element and making only a corner of it clickable (thank you dev tools for that, coz if I hadn't used that I would have been clueless)


### Day 90/91: Jul 23/24, 2022
**Today's Progress**: Day 90/91 of SoC Bootcamp, weekend!

**Thoughts on the day:**
- Did LOADS of work on my mental health app this weekend, getting three pages up and running, linked to the cards page I got up and running last night.  I managed to hook up the reddit feeds, transfer a copy of the cat generator, and build a sticky note page which uses the backend and has a database (so also setup the database)
- Was really pleased with myself but there were a few little style things I wasn't sure of, just like backgrounds and stuff, so will have another look


### Day 89: Jul 22, 2022
**Today's Progress**: Day 89 of SoC Bootcamp, project

**Thoughts on the day:**
- We worked on wireframes, colours, fonts, names etc today - and I learned that some people legit don't understand what democracy and vote rigging is.  Probably should have taken it more lightly, but the voting process in our group is painfully slow and it really just ran out my patience if I'm honest lol  Anyways, by the end of the day we had a design, a colour palette, a font and a name. Boom
- After bootcamp I finished off some wireframe designs I was working on to give us a headstart on Monday, and then I went to work on my mental health app project, to create the cards element.  I followed a tutorial but it all went a bit pear shaped when half of the css started clashing lol  Did some work on the classes and managed to fix it, and what do you know - working cards! :)


### Day 88: Jul 21, 2022
**Today's Progress**: Day 88 of SoC Bootcamp, project and guest speaker Leigh Rathbone from Gear4Music

**Thoughts on the day:**
- SO today wasn't the most fun morning...  We did our ideation which obviously lef to critic and realist stages, and this is where I'm most at home and especially as I already had concerns about what people wanted to do.  I brought up the issue of persistent and private data, and the fact we'd need user accounts (not something we've done so would need to be a thing we implemented from no knowledge at this point) and that a lot of the features would rely on this.  Prdictably people pushed back against things (and wasn't just me, but I did feel like the voice of shitting-on-things) but we managed not to fall our and I think everyone was respectful and managed to approach things in a professional way
- Little bit annoyed when something I said about designing for mobile/desktop got shot down, and then 5 minutes later when the penny dropped, the same person picked up what I'd said like it was their idea...  Grrr...  Doesn't matter how much you think "teamwork teamwork teamwork" that will never be not annoying
- BUT we hammered out our MVP, and that made me feel a bit better
- The talk from Leigh Rathbone was so interesting and he seemed like such a nice guy!  I think everyone on the bootcamp flocked immediately to Linkedin to connect with him lol  So cool hearing about someone having worked on so many things that turned out to be so massive and mainstream; every single one of us has something in our life NOW that was affected by the stuff he'd worked on.  Very cool


### Day 87: Jul 20, 2022
**Today's Progress**: Day 87 of SoC Bootcamp, first day of projects!

**Thoughts on the day:**
- My group this time is much better balanced in terms of talent, I think :)  Which was a relief because I had envisions essentially not sleeping or resting for 4 weeks if it was a replay of the week project.  I'm not so happy to have been put in a group with one of the girls I'm friendly with, because I see some issues knowing our personalities, and honestly I'd rather be able to support each other from different groups than butt heads in the same one, but luck of the draw
- We got to know each other a little bit and then brainstormed ideas for what we wanted to do - in the end three people had the same idea so we were never going to end up doing anything else and all my ideas went on the scrapheap lol  No biggie, I'm happy with majority rules.  Though it was amusing that we set our manifesto etc for decision making, and then when it came to choosing a team name we followed it and people started to dissent and overruled it to another option...  Amusing in the sense it put me on edge if I'm honest lol
- I'm not too keen on the idea and from what I'm hearing at this very moment in time, it's a year long project for a 4 week one, but yeah...


### Day 86: Jul 19, 2022
**Today's Progress**: Day 86 of SoC Bootcamp, still postponed

**Thoughts on the day:**
- I got some feedback on my early CV draft from Nadeem, which was great - I mean, sadly everything I'd written down was useless, but it was good to find that out at an early stage! lol Also got some really supportive advice on the project and interviews, and really the guy is amazing.  Such a good mentor, and just speaks to the spirit of SoC as well
- So I shelved that after the feedback because basically I need to structure it in a way that I need projects done and stuff.  Plus, my laptop got so hot today I couldn't work out it for more than a little bit without turning it off in fear
- I did a little bit of work on colour schemes and wireframes for the project with Brycen, and that was about it - oh, and we decided on the excalidraw font because I looked into it and found out it was opensource :)


### Day 85: Jul 18, 2022
**Today's Progress**: Day 85 of SoC Bootcamp, project postoned for heatwave

**Thoughts on the day:**
- So that didn't go as planned!  As we're having an unprecidented heatwave, SoC decided to postpone the beginning of projects until Wednesday, and I think that was a great decision because who works best when they're hot, tired, and grumpy?  Not me
- I decided to spend some time working on my CV and tinkered with a CSS project Helena had setup to make a CV using styled components.  Now, while I like the idea of styled components, actually putting into practise was a fricken nightmare hellscape.  I couldn't seem to do basic things, or make things work the way she had in the demonstration.  Obviously a PICNIC thing but still...
- Then it was too hot to work at my laptop so I printed off these logs and started summarising down everything for actual CV content


### Day 83/84: Jul 16/17, 2022
**Today's Progress**: Day 83/84 of SoC Bootcamp, weekend before final projects!

**Thoughts on the day:**
- Saturday I spent having a play tbh - I learned how to set gifs as background images and decided to make something funny, with a joke portfolio that was just a React app with pages on React Router, each one with a different gif and just an amusing thread of text.  It was nice to not be too serious and I was still practising skills, so it made me happy :)
- Sunday I started working on my project with Brycen!  We're making an app for people to be able to set reminders to take a break/have some water/sit up straight, just a little wellness thing really.  I'm looking forward to it but also trepidatious coz it's Brycen and he can run code rings around most people, let alone me lol


### Day 82: Jul 15, 2022
**Today's Progress**: Day 82 of SoC Bootcamp, connecting frontend and backend hackathon

**Thoughts on the day:**
- I felt really lucky to meet two new people and work in a lovely group today; we built a todo list app, and though we didn't get everything working, we all managed to have access to our own database, and me connected front and backend so that we could display a list of todos through from Heroku.  We had the input element working but ran out of time to hook up the frontend to our backend POST request (which was working with Postman tests)
- It felt good to go over something I haven't done in weeks and just refresh it and pick up some new things, like a reset script to drop/create/populate the table
- In the evening I finally got myself to look at my mental health project and fix the CSS modules, and it was such a relief to get it sorted and hopefully be ok going forward.  I had a hairy moment where it seemed like it was going to break the writeout element, but I worked through it and it turned out fine :)


### Day 81: Jul 14, 2022
**Today's Progress**: Day 81 of SoC Bootcamp, guest speakers Nadeem and Camille from talis, interview prep, working on DELETE route

**Thoughts on the day:**
- Interview prep...nope lol  I mean, obviously it has to happen but atm I think I'm more concerned with skills.  Still, I worked on it with a fellow bootcamper, practising answering a codewars and talking through the process...not a very comfortable thing but hey ho, if that's the game then imma play
- After that we had a really good talk from Nadeem and Camille, focussing on how they work at talis; the different groups and working practices, elements of design, production...  It was interesting and though BIG not too overwhelming
- The afternoon was spent working more on recapping basics and the todo list.  I'm not going to lie and say I'm comfortable with stuff but I do feel much better for having the opportunity to go over things


### Day 80: Jul 13, 2022
**Today's Progress**: Day 80 of SoC Bootcamp, recapping React and backend

**Thoughts on the day:**
- We had the opportunity to go into a separate Zoom for the rest of the week and work on things we felt needed more attention, recapping more basics - grabbed that opportunity with both hands!  Learning new things is great, but it's been weeks and weeks since I looked at some stuff (for the first and only time!) and I felt like my attention would be better served focussing on solidifying some of that
- I worked on a todo list, building a frontend and a backend and getting them to communicate


### Day 79: Jul 12, 2022
**Today's Progress**: Day 79 of SoC Bootcamp, guest speaker Dan Newns of Jump24, portfolio day

**Thoughts on the day:**
- It's great hearing from different employers, and Dan was a really nice sounding guy with a great company ethos and real interest on people being happy at work.  That's so great to hear coming from so many places where - pardon my lanaguage - they didn't give af.  Makes me hopeful for the future
- The rest of the day was then to work on our portfolios.  Now I'll admit, I just don't know where to go with mine and it's got me stumped.  I asked Nadeem (from talis) for his insight as an employer, and he very graciously took some time to go through some of the things he found important and some that he didn't.  Inspired by what we went over I shelved trying to design my portfolio for a while (both he and Dan that morning had said they didn't really look at them) and instead I worked on my Github profile - because that's where my project info will live and that's somewhere people probably will land


### Day 78: Jul 11, 2022
**Today's Progress**: Day 78 of SoC Bootcamp, guest speaker Valerio Cippola previous bootcamper, UI libraries

**Thoughts on the day:**
- Valerio was on the last bootcamp before ours, I believe - such a nice guy and very good at motivational speaking.  He really left a good impression with us all but also really emphasised having drive and pushing yourself
- We looked at UI libraries in the afternoon, and our group pulled Ant Design.  Wasn't the one I'd have preferred to look at, but that's life!  Still, it was a good introduction and we managed to get elements rendering on the page, figuring out inline importing and importing as components, as well as some in-line styling
- In the future I really want to look at Material UI, and I've heard Tachyons is good - so definitely have that on my radar


### Day 76/77: Jul 9/10, 2022
**Today's Progress**: Day 76/77 of SoC Bootcamp, weekend!

**Thoughts on the day:**
- I spent most of Saturday working on a text area and transition for one of the pages on my personal project, and was SO chuffed when I got it working! Honestly...I learned quite a lot, and as frustrating as it was to try things and them not work, and to not be able to find out how to do what I wanted, it was so gratifying getting to the final point
- I used state and set timeouts, and I learned about transitions with CSS (like that it's not possible with gradients, grrrrr), and I created a really cool effect I was really pleased about :)
- Sunday I didn't do as much, but put a Figjam together for mine and Brycen's project, as well as a couple of initial wirefram designs in excalidraw. He's busy getting married so they're very much subject to change, but it was good to put some stuff down and sort of clarify the idea a little bit - even if it does flesh out differently when he's back!


### Day 75: Jul 8, 2022
**Today's Progress**: Day 75 of SoC Bootcamp, AWS

**Thoughts on the day:**
- AWS is difficult - even signing up for it is difficult. This is another one where it felt like "Ok great, but for now too much". I think what I plan to do is circle back to this AFTER the bootcamp; there's a 13 hour course to try and get the entry certificate, so I think I'll aim for that and look at it properly
- After bootcamp I had a mentor meeting and worked on soem CSS with my mentor for my personal project. Figured out a couple of things, and now know how to use CSS modules correctly, but also broke some of the responsiveness on my app... Not sure how to go about that... He's taking a look to see if he can see what's going on as the behaviour was unexpected - basically everything below what's visible on screen cuts off if you scroll. Cool huh?


### Day 74: Jul 7, 2022
**Today's Progress**: Day 74 of SoC Bootcamp, 10 second intros, Couchbase

**Thoughts on the day:**
- The morning was spent talking in our little group and trying to figure out our elevator pitches for ourselves. Honestly I find talking about myself really difficult, but I fully appreciate the need to work on this and have been thinking about it on and off since. I came up with a couple of jokey ones, but actually I think the second one is pretty near the mark...
- The rest of the day was a talk and demo from Couchbase, and honestly it was a write-off. With only one screen it was next to impossible to follow along with the labs, and the pace was really fast. There also seemed to be an assumption of much greater knowledge that at least I possess on the subject of databases and just many many other things that came up. I don't honestly feel like I'm going to spend much time looking into it because it's a paid service anyway, so I wouldn't use it by myself, and I would rather focus on other basics


### Day 73: Jul 6, 2022
**Today's Progress**: Day 73 of SoC Bootcamp, levelling up React with useContext and custom hooks

**Thoughts on the day:**
- So context...not gonna lie, I didn't love it...and writing this on Sunday because I'm playing catch-up, I can't actually remember what it does for my life. So that probably says all I need to say about that
- Now custom hooks I like the look of. The minute I saw them I was like "could have used that in the project" - but then actually putting them into practice was more difficult. Still, this is definitely something I can see using in the future
- And I just remembered more about context. Yeah, I wasn't 100% with it, but just need to spend time with it I reckon - like most things! That's the big problem with this course for me, we spend so little time with something and then move on, and it's not enough time for me to really get to grips with stuff


### Day 72: Jul 5, 2022
**Today's Progress**: Day 72 of SoC Bootcamp, deployment with Netlify and Heroku

**Thoughts on the day:**
- Today we deployed a fullstack app, with backend in Heroku and frontend in Netlify.  The deployment itself wasn't too traumatic though it was pretty much guesswork sometimes, and we ended up with an extra slash in our domain path because we didn't realise you shouldn't put one at the end - will know better next time
- But despite that causing errors, we figured it out and hacked around it by adding another slash in the backend path
- Then we looked at expanding the functionality of the app by adding a PATCH route (which I don't think I've done before) to update the boolean status of whether a shopping list item was completed, and honestly it was just a massive guess.  I feel like I did alright on the backend logic, I sort of fluked the right thing, but frontend?  Nah mate.
- Worked on my personal project in the evening and realised the landscape orientation of the image request wasn't working correctly.  Also problems with opacity on backgrounds, and just like...yeah.  Think the design might need to change coz it's getting to me a bit
- BUT did get the image working in at least some capacity


### Day 71: Jul 4, 2022
**Today's Progress**: Day 71 of SoC Bootcamp, deployment with Netlify

**Thoughts on the day:**
- So my partner this week actually was starting a new full time job today and somehow expects to also be on the course but not be there at all...interesting lol  I decided to remove myself from that situation immediately and joined another group
- Today we looked at deployment; what it is and what it does for our lives
- We then specifically looked at using Netlify, which specialises in static site deployment and isn't really as suitable for projects with a backend as it's main thing is serverless functions
- We managed to deploy a React app (boilerplate one, nothing fancy) by linking to Github - we then amended the domain name and also made and pushed a change to see that deployment was reactive and handled this change - which it did!
- Started looking a little bit at Bootstrap and think I'm going to follow Net Ninja's course on Youtube
- Also worked a bit more on my project and managed to get the quote displaying on the frontend, along with the author, and messed around with the styling.  Some more questions for Aidan, but yeah, was chuffed to make progress!


### Day 69/70: Jul 2/3, 2022
**Today's Progress**: Day 69/70 of SoC Bootcamp, weekend baby!

**Thoughts on the day:**
- This weekend I worked more on my personal project, finishing off low-fi wireframes and making a high-fi wireframe for my landing page.  As different parts of the site are going to look different I decided to take the approach of high-fi-ing them as I get to them
- I had a BATTLE to get the background image displaying correctly, and not knowing where I should be in CSS modules...  I've already asked Aidan to look at that with me at our next meeting.  But eventually it was there, and then onto other problems
- I sort of hacked a side nav bar, but again, not happy with how I got there and want to get a bit of help with it
- THEN the first fetch request to the quote API for a positive quote to display on the homepage...  I've never liked positivity less, let me tell you lol  Because of a CORS issue I couldn't send the request just through frontend like I have before with API calls, and had to proxy it through the backend.  That was NO small feat, and eventually managed to get something coming back just not the right thing lol
- This is where I learned a very important lesson: in development, when you make changes, RESTART YOUR FRONT AND BACKEND.  Because sometimes stuff just won't work until you do
- Eventually got the quote coming through on the backend!  And decided to call it quits before I ran into another disaster lol


### Day 68: Jul 1, 2022
**Today's Progress**: Day 68 of SoC Bootcamp, Auth0

**Thoughts on the day:**
- Well today was a shitshow, pardon my not-french.  I got to work with Katie, Shiv, and Amanda - as well as Nas, who was off yesterday - so that was great, and being able to support each other after a tough week was good.  Right until one of the team was brought into a whole scenario of having a chat with the person who made her miserable last week
- Honestly...don't want to go into it much and not my situation to talk about, but one person's actions and inability to work with others hampered our whole day collectively.  THAT'S why soft skills and interpersonal skills are important; dealing with that situation collectively derailed our entire day and we got nowhere near as much done as we otherwise would have, nor had the focus we should have had
- Still, managaed to get Auth0 working on a React app, displaying user details and (lack of) meta data, as well as logout functionality working


### Day 67: Jun 30, 2022
**Today's Progress**: Day 67 of SoC Bootcamp, the project is dead!

**Thoughts on the day:**
- Today was our last mindset session with Joseph :(  I'm gonna miss that even though working with some of the smaller mixed groups could be an experience lol  Today our group looked at analysing how we'd working in teams and what we did well/could have done better/etc
- After that, I honestly am struggling to remember what on earth we did...
- Guest speaker!  We had a talk from the guy behind Code Creative on Youtube - he went over some ways to improve with React and was a really nice sounding guy, lots of time for questions and really honest with when he couldn't answer something.  A lot of what he said sort of went over my head (a lot of acronyms!) but I took notes and I'll go over again to digest a bit more
- We then did a research task on authentication and authorisation, and the pros and cons of implementing this yourself or using a 3rd party


### Day 66: Jun 29, 2022
**Today's Progress**: Day 66 of SoC Bootcamp, more documentation

**Thoughts on the day:**
- So honestly I'm playing catchup as I have once again slacked off on filling this in...may be brief lol
- Today I pretty much wrote the documentation for our project single-handedly.  Backend said they'd refactored but actually they'd done pretty much nothing and there was still a tangle with two functions where only one was necessary and working.  The person looking at this swore black's white they'd tried every combination and they both needed to be there for it to work, but I went off and tried it myself and what do you know - got it working with one function and model.  I sound like I'm being horrible but actually it was just tiring working on the project and trying to pick up from other people not knowing what they were doing or making solid effort in some cases
- The person who had the testing done yesterday was off and ofc hadn't pushed this up, so...no testing
- But yeah, the documentation came out ok and we sat with another group and looked at theirs, and overall wasn't a terrible way to spend a day.  I enjoyed playing with markdown as well :)


### Day 65: Jun 28, 2022
**Today's Progress**: Day 65 of SoC Bootcamp, documentation

**Thoughts on the day:**
- So today some more videos, looking at how to go about documenting your code/project.  Documentation is something I've struggled with (in terms of reading docs for techs I've been using) and so I have a vested interest in learning how to make mine approachable and useful
- Having some time to also refactor our code and add more testing, we split off and I looked at refactoring the frontend code (since I worked with it most).  Cleaned it up and made it look nice, removing any unused imports and unhelpful comments; made sure everything followed naming conventions to make it easier to decipher.  Also removed some inline styling and put it in the css file.  BUT perhaps biggest accomplishment, took the accessibility score on Lighthouse from 83 to 100 by adding aria roles and alt text :)  Sweeeeeet
- Got a start on writing the documentation, but that's tbc tomorrow
- After bootcamp I had a mentor meeting, and my mentor was reassuring me not to be down about project week and to not compare myself to others.  He said the bootcamp has always seemed to skew higher ability groups and judges, so at least I don't feel like that's just me thinking that
- Then after THAT (omg no wonder I'm tired all the time) I started a Youtube project to build a meditation app https://www.youtube.com/watch?v=oMBXdZzYqEk&t=1400s
- My hope was to be able to put this into my personal project and bodge from JS into React, but I'm not so sure at this stage that I'll be able to.  Definitely need to complete it and then see where I am, because as of right now I can't see how I'd be able to transfer it over :(


### Day 64: Jun 27, 2022
**Today's Progress**: Day 64 of SoC Bootcamp, project retro and code review

**Thoughts on the day:**
- So, disappointingly (for me) the project isn't dead yet; this week we're working with the same team and looking at other elements of the job, starting today with a retro and then a look at code reviewing
- Our team retro wasn't great tbh - everyone was sore about the judging situation from Friday, and the meeting wasn't really very productive.  Some of the lads wants to give the app a face lift, which is funny since they did none of the styling and we all picked our MVP style together - and the app is pretty damn close to the style we picked.  I think they just want to throw colours at it because it's plain - which is fair enough if that's your bag - but yeah, they wanna restyle it they can go ahead, because I did that styling on my own time so that we didn't have something awful to showcase lol
- Learning about code reviews was good, started with watching a video and then we hooked up with another team and swapped projects - they reviewed ours and we theirs.  It was nice to see another team's work and a completely different idea as well
- Overall I thought all their review comments were fair and they seemed to feel likewise with ours.  Definitely important to communicate well and in a positive way
- Rounded off the day making a few low-fi wireframes for my mental health app project, and used a new tool called excalidraw as recommended on Twitter - I love it!  Really cool little tool! :)


### Day 62/63: Jun 25/26, 2022
**Today's Progress**: Day 62/63 of SoC Bootcamp, weekend

**Thoughts on the day:**
- So after last night, I tried to feel better by focussing on what I did achieve over the week and not what I didn't.  I learned a lot and I think I navigated quite a difficult, low-ability group well
- I decided to plan out my own project I felt more strongly about that wasn't selected, and work on a mental health app for bootcampers.  I made a FigJam board and started planning, and put quite a lot of time in.  I also created a React app and started building the backend, at which point I realised how shaky my backend skills were after no use since what - week 5 of the bootcamp?  But I'm not getting discouraged.  I just need to practise
- I researched some things I want to be able to do within my app, and I'm going to spend some time looking at React Framer Motion, and may also look at particles.js - I want to be able to do some animations and pretty things :)
- Haven't done wireframes yet, but I plan to once I have more of the backend put together.  I was starting to feel anxious about it and the best way of addressing that, I think, is just to work on it
- Finally started feeling better throat-wise after two days of near-silence lol  God, it's nice not to have to speak!


### Day 61: Jun 24, 2022
**Today's Progress**: Day 61 of SoC Bootcamp, final (thank god!) day of project week - presentation time

**Thoughts on the day:**
- So today really was just pretty much ALL working on our presentation.  Getting 5 people onto the same page and timings and everything else for a presentation, is like herding crackhead cats.  Do not recommend, would not go back.  Not with this team anyway, and that's not me being horrible, it's just the truth.  Some wildly different ideas on what's appropriate and what's important
- We hammered out the presentation by about 11, having finalised our slides (which myself and Shiv had been working on throughout the week) and then got down to practising out loud.  I struggled with a couple of points in the presentation where other people were saying things I didn't necessarily think were great or true, but at a point you can't pick up everything anyone says because you're just a bitch, so I had to bite my tongue and just let it go.  Difficult
- Honestly, writing this out I feel like it must be me...  I don't know.  I just have high standards and yeah.  I'm not going to apologise for caring and for wanting to present something in a way I feel best reflects the project and us as a team, in a positive way
- Anyways.  Afternoon came and we gave our presentation, and the judge had no questions for us and...I felt deflated.  It felt very much like "oh"
- After it was over, I saw a few people demoing their groups' apps, and I just felt like shit.  We accomplished nowhere near what other groups did, and honestly, I had a big cry.  It's so frustrating...so many people on the bootcamp are so talented, and quite a few groups got that bunched up.  Our group didn't have that, and as hard as I - and we all - tried, we just didn't have the capability to deliver something like that in a week.  It was quite despiriting


### Day 60: Jun 23, 2022
**Today's Progress**: Day 60 of SoC Bootcamp, fourth day of project week

**Thoughts on the day:**
- I worked with the same partner today, and also a third team member who finally reappeared after having no wifi the first three days.  Working with him was quite stressful because he was very negative about his experience of the week and down about what had happened, and it was hard to get him to move on and just contribute as much as he could now - he'd pretty much decided he just couldn't.  But we tried and tried, and eventually he snapped a little bit out of it
- We worked on some unit/integration testing with Jest and React Testing Library, and managed to get a single test working mostly by luck.  Testing is something I have no confidence with and really struggle with
- The other two people worked on Cypress end-to-end testing, but one disappeared partway through the day for no reason, and the other hit a technical problem that took up a lot of time.  Honestly...it was stressful trying to keep myself from saying something, especially since I'd been ill most of the week and was feeling rough (thanks, tonsillitis)
- But by the end of the day, we had some Cypress testing, a Jest/Testing Library test, and we could move onto CSS.  We got the page styled a little bit and people were happy - me?  No.  I was not happy because it was still way off lol
- So I spent my evening fixing as much CSS and prettying it up as much as possible.  I was quite pleased with some elements of it, but it was a very plain design so I can't lie and said I did anything amazing.  But still, it was nice


### Day 59: Jun 22, 2022
**Today's Progress**: Day 59 of SoC Bootcamp, third day of project week (halfway point)

**Thoughts on the day:**
- My partner today was someone I hadn't worked with before but we got on nicely, and we focussed on getting our List and List item functioning with dummy data from a branch of the backend, as backend was still not configured to get data from the database
- We got this working and were really pleased, but when it came to lunchtime and we got back together with the rest of the team, we discovered they'd not done anything we'd discussed in the morning standup, and were no closer to getting the backend talking to the database.  We went over what had to be done and pointed out some areas they were working on that...tactical...weren't going to be productive - and then I went for my lunch before my mind exploded
- In the afternoon, the other pair in the team got the backend up and running with database routes, after seeking some help from Slack, and we could start looking at how to link front and back end.  This was a process we'd never done before, so my partner and I went off and researched, and finally - with the help of multiple articles and bits of youtube tutorials - we managed it.  It took about 10,000 console logs to refine how to set our state, but we figured it out, and by the end of the day we were successfully fetching data on the frontend through get requests on the backend.  Woo!
- I believe this is the video by Codr Kai that finally got us there: https://www.youtube.com/watch?v=3isCTSUdXaQ&t=2043s
- So yes, by the end of the day the backend was mostly up and running - some issues with route paths which some people overcomplicated *cough*, but we got there
- At the end of the bootcamp day we could successfully render a list of links as their descriptions, but we couldn't figure out how to have those come out as document and video lists, nor could we figure out how to get them printing up once.  I can't remember what the issue was, but they would pull through twice with whatever we were doing.  That night I managed to figure it out and get the list broken down into a document list and a video list, by creating another set of components (VidList and VidListItem), and chaining .map() and .filter() based on a null value in the table.  To say I was chuffed would be an understatement.  That pretty much got us to MVP


### Day 58: Jun 21, 2022
**Today's Progress**: Day 58 of SoC Bootcamp, second day of project week

**Thoughts on the day:**
- Today I worked with someone I'd been partnered with earlier in the course and we started on the frontend with creating the React app.  I had mixed feelings about working on frontend, as I kind of wanted to go back over bacmkend as I haven't looked at it for so long - BUT I see the upside in working with React still to cement it a bit more
- Our first big challenge came when trying to figure out how to have different pages for our app, as so far we've covered and worked with SPAs.  I managed to find what we needed in React Router (my mentor had also mentioned this) but then my partner and I ended up looking at different versions.  In the end we decided to go with the latest version (as why learn old software, right?) and we got going
- The docs for React Router 6 - imo - are terrible.  They focus on you downloading and working through a tutorial, which we just didn't have time to do.  If we weren't going to be able to implement pages we needed to know ASAP so we could reassess our plan as a group.  Thankfully I found a tutorial on youtube that held my hand through it, and while my partner was off at his enablement coach meeting and taking a break, I figured it out on my own.  I mention this specifically as I was really proud of myself in that moment
- The tutorial was PedroTech https://www.youtube.com/watch?v=UjHT_NKR_gU
- After that it was a bit of a blur, but basically focussed on getting the various pages up and running, and then started in on building components for the List and ListItem
- The day was hard and long, not gonna lie, but I was really happy with my personal journey with React Router


### Day 57: Jun 20, 2022
**Today's Progress**: Day 57 of SoC Bootcamp, first day of project week

**Thoughts on the day:**
- Aside from being anxious and stressed to the eyeballs, I was really...no I can't lie - I was really not look forward to this
- Had mixed feelings about my group tbh, I think there are a couple of personality clashes potentially, and we have a team member with such bad internet he was missing the vast majority of the day.  So...yeah
- Still, we got the bulk of our planning done, decided our team manifesto, set up a Trello board for project management, brainstormed and picked our project, did our user research/stories, figured out our MVP, and low/hi fi wireframes
- I spent an extra hour and a half at the end of the day putting stuff into presentation format to save time later on and deal with it while it was fresh and in front of me
- And yeah.  Current mood is please kill me now coz I am STRESSED


### Day 55/56: Jun 18/19, 2022
**Today's Progress**: Day 55/56 of SoC Bootcamp, weekend yo

**Thoughts on the day:**
- So this weekend I recapped the CSS I'd covered with my mentor and set myself a CSS challenge to design (UI I guess as well) a landing page for an application with a background image and implement some lovely styling.  Was really pleased with what I managed to do, and looked up some really cool things to implement as well as practising some things Aidan told me about
- After that, I made a calculator app from a Youtube project, which honestly wasn't great.  I got it to work, sure, but I don't know that I can say I really learned anything (aside from the fact that people use calculator logic from a library for a reason).  So...busy work maybe, I'm sad to say
- Then I started bigtime stressing about project week and slightly fell apart, I'm ngl.  Tried to do some reading and revising of notes, but mostly lost all ability to focus and concentrate


### Day 54: Jun 17, 2022
**Today's Progress**: Day 54 of SoC Bootcamp, hackathon Friday!

**Thoughts on the day:**
- Actually a really good day today, my partner and I worked really well together and managed to make our MVP.  I was a bit...disappointed isn't the right word - but a bit _something_ about the fact we did something very basic, but neither of us were confident going on and taking some pressure off seemed a good way to go
- We made a full stack React app, a cat pic generator to be precise, which was something I did for week 2 recap but obviously in a completely different way.  This was something we decided because we knew the API was stable and the information accessible, and we also wanted time to be able to style the page if we could get the basic functionality up and running
- Was really pleased with the CSS we did, which utilised a button from a UI resource.  I then managed to extrapolate the right bits of the CSS code to give the image border the same effect, and overall the site looked really cool :)  we got a nice big round of applause and it felt good
- So yeah...wish we'd managed more and wish I'd felt capable of more, but don't want to dismiss what we did.  It was simple but it worked, and we made decisions that were rationalised and agreed upon as a team 
- After bootcamp I had another session with my mentor looking specifically at CSS and working through some techniques to recreate a design I had pointed out, and this was good to pick up some tips and see how beneficial the dev tools can be


### Day 47-53: Jun 10-16, 2022
**Today's Progress**: Day 47/48/49/50/51/52/53 of SoC Bootcamp

**Thoughts on the day:**
- Yes that's right, I did not fill this out for a week and now I hate my life lol  Ok, so gonna switch up the format and get this down as best I can, but will just explain the reason why I haven't been here.  The past couple of weeks have been my wobble and I got to the point where reflection wasn't going to be helpful; I was putting my head down, trying to work on the code and the theory, and everything else was excess.  I don't regret taking that approach even though it means I now have to recap a week here
- I've also decided I'm going to scrap the *Thoughts on the Coding* section, because I feel like everything can go under the one heading of *Thoughts on the day*  So without further ado...
- 
Day 53: mindset session on Group Dynamics, GitHub branching, guest speakers Nedeem and Camille from talis, research task on Agile Standups
- Phew so today was a busy one!  But a good one - I always enjoy mindset, and was happy to see the return of Joseph.  We went over some concepts that should help us next week in our first larger group project, which in all honesty, I don't like thinking about mostly because of group dynamics lol  The coding will be what it will be - I'll struggle with that no matter what, I'm sure - but who is in the group and how we interact...  Yeah, that's a worry
- We had a talk from Nadeem and Camille on RESTful APIs - another hint-hint, project week thing - and was 'nice' I guess to be reintroduced to some of those things in preparation
- Then the afternoon was working in a group of 4 and researching (for our group) Standups in Agile.  We had to make a presentation and record it, uploading it at the end of the day.  Honestly I'm never going to love presentations, but our group worked well together, and I think we came up with something nice and digestable and information, so I was happy

Day 52: guest speakers Mark and Hailey from Experian, Testing Library in React
- The speakers from Experian were great, and it sounds like a good environment to work in; really supportive of new talent and fostering an atmosphere of growth and development, as well as being positive about remote working.  Yup - there will be fights on the cohort when it comes to applying for roles with them lol
- We then moved on to looking at testing in React, using Jest (as we looked at previously in week 6) and Testing Library.  I'm ngl testing isn't my favourite thing (even if, contrarily, I really like the reasoning and everything behind it).  I find it difficult and I think it exposes the fact that I'm not super confident about my ACTUAL code - so I think testing and I will be better friends at a later time, when I've got more experience and confidence under my belt
- Saying that, I did manage to write a passing test on my own later that night, testing for the correct number of list items in an ordered list.  Go me!
- Oh and also was introduced to aria roles (which aside from other things, are useful in testing when using getByRole - the prefered query method)

Day 51: finite state machine, 
- Chris took us through the theory of finite state machine and I found that really cool - easier to grasp in theory than to enact when putting into practice (like most things I guess!) but yeah, really interesting way of looking at things and sort of streamlining the development process
- FSM have a finite number of states and to get between states we have to take an action – of which there are a finite number - which makes them predictable 
- This led on to looking at useReducer in React, which takes a state and an action and returns a new state (to boil it down!)
- Reducer functions make things testable and maintainable, and are good for complex state management where you have multiple states changing
- We looked through documentation (which we've always been pushed towards, but now even more so as we get further into the course) and it wasn't toooooo bad in terms of docs, which definitely vary in quality and usefulness

Day 50: pure functions, useEffect hook
- I enjoyed the theory about pure functions and why this way of writing code is more manageable for various reasons - it made sense and was nice to hear actually.  Things don't have to be fancy and convoluted, in fact it's better if they're not
- We were introduced to the useEffect hook in React, which runs AFTER the app rendering and helps keep things in sync.  It's not a function we should be using a lot, but for awareness it was good to look at (and apparently it confuses even snr devs, so yeah...marginal comfort if struggling)

Day 48/49: weekend, yo
- The weekend recap tasks were also dreadful.  It was another React app task (a blog app this time), and at a point I had to draw a line under it, stop trying to bang my head against a wall, and go to basics
- I turned to the React Beta Docs and I started reading and working through the examples.  Ngl, I still struggled - and struggle - but I feel like this was the best thing I could do
- By the end of the weekend I managed some of the recap tasks, and that was better than nothing.  I was proactive and spoke to my mentor, asking for specific help on what I was struggling, both this and CSS

Day 47: Hackathon Friday!
- This was the worst hackathon yet.  My partner and I really struggled (as did a lot of people in the bootcamp - which makes me feel better) and my partner also got quite upset during the day which was tough to take.  It's very frustrating when you're trying to hard and just don't get something, and it takes a lot to power through
- In the end, we achieved what we did with the help of other bootcampers (btw the project was a React ToDo List app).  There are some lovely people on the course and though struggling can be really difficult and infuriating, there's always someone or a moment of light that will bring you through


### Day 46: Jun 9, 2022
**Today's Progress**: Day 46 of SoC Bootcamp, guest speaker Javid Karim from Nester, mindset with guest coach Trenton, spread and slice, map and more

**Thoughts on the day at bootcamp:**
- Today was full-on.  Because we had mindset and a guest speaker, the actual sessions and workshops got crunched up and honestly, it was a whirlwind
- Mindset was different - Joseph wasn't there :(  But we had a great guest coach called Trenton, who was so energetic it was a bit of a shock lol  We looked at communication styles, and I'm a Thinker apparently.  Tbh it fit when he was explaining it, so yep.  We discussed treating others how THEY want to be treated not how WE want to be treated, which makes a lot of sense
- Javaid is so nice - he gave us a really good chunk of time and honestly I think he would have given more, but Liz K was keeping us to schedule.  He gave a really interesting rundown of the tech landscape and how things have evloved, feeding into that his experience of coming to new technologies and how he came to React.  He went over how he and Nester choose their libraries and what they work with, and that was a really good insight to industry practice and actually just being a good developer
- We then had the speediest rundown of some more JS methods and how to use them with regards to immutabilility, to be able to reliably change things in React, and though we didn't have much time to practice, I think I kind of took some of it on board

**Thoughts on the 'coding':**
- We didn't have much time during the day, but tonight I finished off the workshop on my own, writing functions to change arrays and objects immutably.  I was really pleased with myself and my googling skills, and my functions all passed the Jest tests, woo!


### Day 45: Jun 8, 2022
**Today's Progress**: Day 45 of SoC Bootcamp, guest speakers Tom and Dan for Adaptable, more React and intro to useState and Hooks

**Thoughts on the day at bootcamp:**
- Well, it was a Wednesday, which means our brains collectively melted...  Actually no, I didn't fare too badly today :)  Doesn't mean I got it or found it easy BUT I did follow the bones of it.  Syntax I'm way off, but I will get there
- We looked at props and hooks, both of which are concepts I'm ok with I think, but using them?  Haha - havin' a laugh aren't you?
- Our talk this morning was great - it's really nice getting such a wide variety of speakers from different places in industry.  I liked the sound of their culture, and the guys were really nice
- Quite tired this week...don't know if it's mentally or physically, but yeah I'm getting to mid-afternoon and I'm wiped out.  Aside from a haircut I have no plans this weekend, so I will hopefully have time to do recap tasks and zone out for a bit as well to rest

**Thoughts on the 'coding':**
- Yeah the coding was a mixed bag - some of it went nicely and then other bits were like hitting a wall  BUT seeing progress in some areas, and finding it easier I think, just to read code now


### Day 44: Jun 7, 2022
**Today's Progress**: Day 44 of SoC Bootcamp, guest speaker Nick Truby from BT, more React and intro to create-react-app

**Thoughts on the day at bootcamp:**
- Nick was a great guest speaker but he talked to us a bit on interviews and tech tests (following the Q&A) and honestly it really intimidated me and sent me into a bit of a spiral.  I'm not there yet and thinking about it just makes me panic.  I guess this is natural (?) but yeah, it didn't feel great if I'm honest...
- Create-React-App, finally! lol  Seen it in the videos and been waiting (im)patiently to get there!
- Good mentor meeting with Aidan, who made me feel better about testing week not going so well - he's not used much testing at all so far in his career, so yeah

**Thoughts on the 'coding':**
- We really just had a little peek at create-react-app and started looking at file/folder structure, so there's a long way to go.  I watched some of Net Ninja's react series and I followed quite a lot which was nice.  STarted to get trickier at the end though, not gonna lie...


### Day 43: Jun 6, 2022
**Today's Progress**: Day 43 of SoC Bootcamp, guest speaker Piper Bates (former Bootcamper), into to React

**Thoughts on the day at bootcamp:**
- Piper was a brilliant guest speaker, oh my days.  I think they made everyone feel better, saying how they struggled on the bootcamp but demonstrating how you can come out of it successfully regardless.  It really made me feel better
- The intro to React was good, taking it quite slow.  We're learning how to write things in ways we won't be going forward though, and that gives me some reservation because it's like "learn this - then throw it out, you need to do it differently" lol  I know it's building a background of knowledge and supposed deeper understanding, but actually to begin with, it's just really confusing (for me at least!)

**Thoughts on the 'coding':**
- We didn't do too much, but it seemed ok.  Honestly more ideas than coding, which not sad about because hopefully it will stand in good stead.


### Day 42: Jun 5, 2022
**Today's Progress**: Day 42 of SoC Bootcamp, Sunday

**Thoughts on the day at bootcamp:**
- n/a

**Thoughts on the 'coding':**
- Read several articles about React to get an idea of what we'll be moving onto; looks interesting and also like it will bridge some of the gaps I'm aware of in my knowledge, so hopefully this is the case
- Also watched a few little videos that demo'd React and yeah, looking forward to it.  No doubt it will be rock solid lol


### Day 39/40/41: Jun 2/3/4, 2022
**Today's Progress**: Day 39/40/41 of SoC Bootcamp, bank holiday!

**Thoughts on the day at bootcamp:**
- Worked on some more SuperTest/Jest testing, also looked at the structure of the workshop we had, with it's drop table and seed table scripts - this wasn't something I'd done or dealt with before so that was interesting to see
- But no bootcamp, just tasks

**Thoughts on the 'coding':**
- Moving away from testing and looking at React from tomorrow.  I want a good start to next week


### Day 38: Jun 1, 2022
**Today's Progress**: Day 38 of SoC Bootcamp, Cypress and SuperTest

**Thoughts on the day at bootcamp:**
- Honestly, these three days have been a bit too fast.  Three types of testing software in three days - I have them jumbled in my head and I'm not very confident with any of them
- I feel confident with the concept of testing, but lack confidence in the use of the tech

**Thoughts on the 'coding':**
- Jumbled...


### Day 37: May 31, 2022
**Today's Progress**: Day 37 of SoC Bootcamp, guest speakers from Cypress, more on testing and Jest

**Thoughts on the day at bootcamp:**
- We looked more at writing tests with Jest, and looking at documentation.  I'm not going to lie, it didn't go particularly well.  I feel like docs are still very hard to read and put into practice at this stage, and honestly I'm struggling with javascript after not really writing these kinds of functions for a while (weeks)
- The afternoon was pretty much all a presentation by two guys from Cypress about their end-to-end testing platform.  It looked really cool, and I've bookmarked the Cypress learning to look at, because I would quite like to see how I fare following through that

**Thoughts on the 'coding':**
- Never saying I like anything again


### Day 36: May 30, 2022
**Today's Progress**: Day 36 of SoC Bootcamp, guest speaker Nadeem Shabir from talis, intro to testing and Jest

**Thoughts on the day at bootcamp:**
- The talk this morning from Nadeem was really good, and I loved how he addressed not doing too much and not killing yourself to get everything, because it's just not possible and it's not healthy.  The way he talked about softskills being important cheered me
- Introduction to testing was pretty good; I found it an easy idea to latch onto even if it's got a lot of nuance to full comprehend, but having working in places with QA depts and being familiar with that side of things, the concept of testing made sense
- Jest was pretty decent to work with after a rocky start installing it in the wrong folder lol  not a move I would recommend!

**Thoughts on the 'coding':**
- I worked on finishing the rest of the tests from the task after bootcamp and was really happy to get them all done, even a tricky one to test an error throw, where the variable needed wrapping in a function to stop the error throwing erroneously.  Is obviously very new, but I think I liked it :)


### Day 34/35: May 28/9, 2022
**Today's Progress**: Day 34/35 of SoC Bootcamp, weekend

**Thoughts on the day at bootcamp:**
- n/a

**Thoughts on the 'coding':**
- The weekend task was a lot like the hackathon, only solo and a bit less hand-holdy.  I was pretty pleased with myself until I got to the end and there were bugs I just couldn't figure out (GET/POST seemed to fire in random order from the button the the front page, meaning sometimes a new cat would be displayed upon button press and other times the page would need refreshing; couldn't figure how to wrap the results on the page; blank entries were able to be added...)
- I was however pleased with some of my CSS on the front page, and overall, I think I'd picked up concepts quite well in executing what was essentially my first full-stack project.  Still a lot to learn


### Day 33: May 27, 2022
**Today's Progress**: Day 33 of SoC Bootcamp, hackathon!

**Thoughts on the day at bootcamp:**
- Today's hackathon was pretty predictable - build a RESTful api, creating and hosting a database, populating it with SQL, and building CRUD operations.  This wa sprobably my favourite hackathon...maybe?  I don't know, it's hard to think back over them and compare in those terms.  But yeah, it was tough but I felt like I understood the concepts
- I managed to help a couple of other teams too, and that felt really good; it's making me feel more confident about things, and exposure to error messages helps you learn how to read them, so I definitely feel like I learned from that today

**Thoughts on the 'coding':**
- Was really proud of myself for getting the CRUD operations working :)  Considering we had what - a day looking at SQL?  Yeah I think I did pretty well, even if they were 'simply' queries.  They didn't feel simple, and fitting everything together from models to routes felt epic


### Day 32: May 26, 2022
**Today's Progress**: Day 32 of SoC Bootcamp, mindset, guest talk from Will Peaches SoC Director, recap of hosting databases on Heroku and connecting with node.js

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
