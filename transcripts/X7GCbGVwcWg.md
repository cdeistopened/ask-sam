---
title: "$100B Founder Breaks Down The Biggest AI Business Opportunities For 2025"
type: episode
date: 2026-01-21
speakers:
  - "Shaan Puri (host)"
  - "Furqan Rydhan (guest, founder of thirdweb and Founders Inc)"
tags:
  - ai-agents
  - thirdweb
  - vr--meta-quest
  - polymarket
  - hardware-robotics
  - founders-inc
  - applovin--app11
  - blab
  - project-selection
  - emerging-technology
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/X7GCbGVwcWg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width:100%; aspect-ratio:16/9;"></iframe>

> Shaan sits down with his longtime collaborator Furqan Rydhan — founder of thirdweb and Founders Inc — for a wide-ranging tour of the biggest opportunities in AI, VR, and consumer hardware. Furqan breaks down how AI agents are already running core business functions at thirdweb, why VR is a sleeping giant, and how cheap hardware (Raspberry Pi + cloud AI + 3D printing) is enabling two-person teams to build things that used to require millions. They also reflect on lessons from Blab, Monkey Inferno, and App11 about project selection and why "surviving" is the only rule in emerging tech.

**Speakers:** Shaan Puri (host), Furqan Rydhan (guest, founder of thirdweb and Founders Inc)

## Introduction: The Cool Stuff Hour [00:00:00]

**Shaan:** Furqan, we're here. It's amazing. I haven't seen you in a little while. People don't know we used to work together — maybe five, six years ago. We co-founded a company, launched a bunch of products, and ate a bunch of shit together. And here we are.

**Furqan:** Fun times.

**Shaan:** By the way, I'm thinking the title of this is going to be — because App11 is now a fifty, sixty billion dollar company — "$50 Billion Founder Tells Me The Next Big Thing In AI." I'm going to go full YouTube clickbait with it.

**Furqan:** Yeah, great.

**Shaan:** So we used to do this thing. After we did Blab together, got acquired — we were there for a year or so — and then we all went off and did different things. I started the podcast and started doing my thing, you started doing yours. But I hit you up and I was like, "Hey, miss hanging out with you. What if we did something?" And we started doing this on Wednesdays, which was like the "Cool Shit Hour." This was amazing. It's basically a show-and-tell where you — my smartest friend — would come on Wednesdays and be like, "Hey, have you seen this? Have you seen this? Have you seen this?" And I really hadn't seen any of it. You would kind of explain it and teach it to me, and it was my favorite part of the week.

We did that for, I don't know, probably like a year or something. So I kind of want this to be like a public version of the Cool Shit Hour where you're just going to tell me a bunch of good things.

I want to start with AI because you texted me something. You said, "AI agents are here." You said AI is cool because a ten-person company feels like it can do the work of a hundred-person company. And we're using it in our company. So I wanted to hear — what are you doing with AI?

## AI Agents: What They Are and How thirdweb Uses Them [00:01:45]

**Furqan:** And that's not called ChatGPT. I think "AI agent" — this phrase — is the thing I really can't pull myself away from. Like, literally every night. You know me — midnight strikes, I want to write code. The whole day is talking to people, and the night is coding.

**Shaan:** I remember we hired you and I feel like the first day you came in at like 9 or 10 a.m. But from day two onwards it was like, "Roll in at eleven — oh, it's lunch time, have lunch, do meetings." And I was like, "Is this guy going to code?" And then that night at like 4 a.m. you would have built the prototype. You're basically nocturnal. You get all your stuff done. You used to tell me you just burn up your energy during the day so you could focus at night and actually write code.

So what are you doing with AI, and what does that actually look like in your company right now?

**Furqan:** So I'll tell you how I'm thinking about AI agents, and what it means to me. AI agents are using LLMs — AI systems like the OpenAI systems or Claude — but then giving them reasoning loops. Imagine when you go to a human and give them something to do, like "Hey, I want to grow a company, do a marketing campaign." They take that, they plan it, they come up with the steps, then they go one by one on the tasks and solve them.

AI agent systems are exactly like that. The first thing it does: it goes, "What do I need to do based on your request?" And it comes up with a plan. You give it a mission.

Let me give you an example of something we're doing at thirdweb. Every single sign-up in our company — and we have a lot of sign-ups every week — a human can't really scan through them all. But there are really interesting people signing up. They have interesting companies. We may know them. They might be a large company or a small one, could be a competitor or something else.

We used to have a human go look at everything. It's like, "Oh, if it's a Gmail, ignore it. But if it's this other company, let's go research it. Let's figure out what thirdweb products they might like, what they might need to do." Then you would send them an email, try to customize it. This is good sales practice — you're taking your customers and delivering them to your business team.

So we built an agent to do this. Every sign-up that comes in, it looks at it, determines if it's an interesting person or not, researches their website, researches them, uses the knowledge it has of thirdweb products to figure out what products they might need, how they would use it. Then it sends them an email or an upsell.

We've deployed probably eight or ten of these throughout thirdweb to do a lot of different functions. And what it feels like is a smaller company can punch above its weight. We're thirty-seven people right now. I really believe we're more like eighty people — that's what it feels like with a lot of these tools.

**Shaan:** So in this case, a person comes to your site, puts in their email address, and now you have — is it one agent or a series of things that pass off to each other?

**Furqan:** In this case we call it the sign-up agent, and it's one agent. It creates a plan: "What do I do?" Part of the plan is the directive we gave it. The way to think about AI agents in general — any clear directive problem. And what I mean by "clear directive" is: sign-up comes in, go look at the person, go research them, figure out their title, their company, what products they have. That's a clear job to do. If it's a digital task and a clear directive, all of it can be done with agents now. The technology is here. It's ready and it's working.

For the thirdweb sign-up agent, it'll make a little plan: "I've got to inspect the domain, I've got to look up the person." And you didn't have to tell it each of those little tasks — we gave it like a one-paragraph directive, another paragraph of how it should operate, and maybe a paragraph at the end for the type of email or action to do. The end product is it's looked up the person, researched them, thought about what product of ours suits their needs — which is the wild step I hadn't really thought about — and then it crafts an email.

**Shaan:** And then it gives it to a human, or it just sends it?

**Furqan:** Sends it.

**Shaan:** Okay. So you have enough trust that it can send it?

**Furqan:** We started it with a human in the loop. There are still safeguards you put in. But it's very clear what to tell it. And this is where the power is multiplying — we've heard about AI, we've heard about ChatGPT, but if you can tune it to your problem — giving it the knowledge of thirdweb products is the key difference here. A generic ChatGPT message will just invent something general and generic. When you give it specific knowledge, it can actually do the right thing.

**Shaan:** And when you built this — you built this or somebody else on your team?

**Furqan:** I hacked it as a prototype, like most things, and then I gave it to somebody on our solutions team. Within a day they turned it around.

**Shaan:** When you made a working version, how long did that take? Because it's kind of like you hired an employee, trained them, got them working — and you're not paying them a salary. You probably did that whole thing in what, a day or two?

**Furqan:** Let's say there's like a bunch of my nights of just learning tools and getting used to it, so I take that time out of it — that's just time I spend anyway. Two nights ago I was really stressed. My calendars are kind of crazy some of these days. I was trying to figure out why it was crazy, where the time was going — it's a really hard question. You could have an EA who goes and looks through it and does all the stuff. I have an EA who helps me with these things, but she sleeps for a while, and I want to go answer some of these questions at midnight.

So I probably spent about fifteen minutes and connected my calendar with a little interface where I could type questions. I started asking: "How many hours of meetings did I have last week?" Turns out it was twenty-eight hours — way too much. "Where did the time go? What were they for? What were the purposes?" Then the next night I spent another forty-five minutes to an hour where I could tell it commands from my calendar: "Go block out Monday for me," or "Find me nine hours to block time and just mark it as blocked."

**Shaan:** Wow.

**Furqan:** And this was a few hours of work. Now that I know the tools, it just works 24/7. My calendar, my email, a few other things — I've started building these personal agent or workflow-type things because I know how I want to react, I know the decision-making I'm going to make. Can I just set that up so it works 24/7, 365? It's just always there.

## Building Agents Without Code: Tools and Workflows [00:10:15]

**Shaan:** If I wanted to build a workflow like this, do you need to know how to code? Give me the bullet-point version of how you built these. Where do you even build it? What tool do you use?

**Furqan:** There are coding tools. If you're a developer, there's LangChain, Autogen, CrewAI — these are very popular. The OpenAI and Claude SDKs themselves are very powerful, but you're writing code. It's probably like one-tenth of the code you would have had to write to do something, so that's already better for developers.

If you're not a developer, there are a lot of tools. Leap is a company we built here in the studio. It lets you stitch together workflows. An example: you can trigger based on a Slack message. So let's say that's where all your sign-ups go. It picks up that trigger, you put a little AI block and say, "Okay, take this email and do these tasks." You want to web scrape? Go do that. You have a little conditional loop or repeat itself ten times? Go do that. Then you make another decisioning step — four boxes — and output it back to another Slack channel.

You come in with your sign-up channel, it does its research, does whatever you want, and then it could go to email or go to another Slack channel to ping somebody on your team. These are workflows. Agents can take these workflows and almost build on top of them.

So there are two things: you can really easily create workflows, and I think everyone should be deploying them. Every company should have them. It is a superpower. It's like — I can't explain the feeling. It's almost like cloud computing was. "Oh, I don't need a whole data center team now." When we built Blab, think about how many servers we had running for video streaming — that would have been a nightmare. It's kind of the same ten-x improvement, but just for everything I do digitally.

So if you don't know how to code, you just have to think about the steps you would do, and you can program that without writing any code. It's just writing directives. Writing intent. Like what you want to accomplish. It's like a magic genie — tell it what you want and it can figure it out.

**Shaan:** So you've got a sales agent, you have your email/calendar EA agent, and other ones?

**Furqan:** I've got some fun, frivolous ones that are kind of stupid. I set up a dynamic wallpaper — literally every five or ten minutes it'll look at what I'm doing and autogenerate a new wallpaper for my laptop. It knows I code at night, so it'll go towards that direction. During the day I'm talking to people, and it comes up with cool stuff that matches that. Totally frivolous, not a useful thing except for my own joy. But I find it awesome. Cool scenes come up, it invents new things.

Claude has created this capability called Computer Use. I think that's the next area AI agents are going to enter.

## The AI Landscape: OpenAI, Anthropic, Perplexity, Google [00:13:45]

**Shaan:** By the way — there's Claude, there's ChatGPT, there's Perplexity, there's all these different ones. Mentally, how do you bucket the main AI tools? What's the superpower of each?

**Furqan:** OpenAI and Claude I think of as foundational tools. General purpose — ask it anything, input/output, you stitch it together with things. Then they have tools like ChatGPT on top, or Computer Use they're figuring out.

Perplexity is really interesting — it's taking the general-purpose LLM reasoning and combining it with search. I try not to do Google search anymore, mostly because it's slow and ineffective. Perplexity does a search, reads the results as I would, clicks into the links as I would, and then tries to answer my question more purposefully. It saves me four or five steps.

**Shaan:** What's your hot take on Google? You're saying you don't Google search anymore — that's pretty wild.

**Furqan:** It just feels slow. I know they've got the Gemini thing there. I think the biggest fumble — in our lifetime, maybe decade-level fumble — is that Google built the technology for Transformers, the thing that OpenAI and others have used to develop large language models. They were the ones who were first to produce and publish the research. That "Attention Is All You Need" paper.

**Shaan:** What's the history? So they write this research paper, "Attention Is All You Need," and from what I understand, all of the authors have left and basically started their own companies. Was it because nobody recognized the power of it? Was it Google's bureaucracy? What's the actual story of why they didn't capitalize?

**Furqan:** I don't know the internal story. I think early on Google was the place you went when you wanted to have the rocket-ship moment of your life. The smartest people were there, they were taking the biggest challenges. I think as a company, Google hasn't felt like that recently. I'm sure it's a mess in there — but it just feels like the biggest fumble. I know they're trying to play catch-up with Gemini and awesome stuff is happening, but the developer mindshare and attention has gone somewhere else. And that is really hard to pull back once somebody else becomes the leader.

From what I can see — OpenAI is number one, that's clear. Anthropic is number two. Then everyone else shows up. That's what it feels like to me, at least from the people I'm seeing building and the technology they're using.

**Shaan:** So then Anthropic — they have Claude, which is like ChatGPT but they have this Computer Use thing. You type something in, it moves your mouse, it just does stuff.

**Furqan:** Correct. It's a combination of things. You could take workflows — "I'm doing this, click this, click that, do it over and over" — it could analyze things. I think the key thing is it just released, it's in beta. Like most of these things, it kind of isn't going to be great now — just trust me, it's going to be great. That's what we've been seeing in general: things just ramp.

So now AI is going to enter your computer. It's kind of felt like AI's been on the cloud only. Now it's going to show up in the box you're used to — your computer, your laptop. There's so much workflow that we do. And yes, every app will put AI in it, and your interface will also do that. A lot of things we're used to doing — switching tabs, having all these things — they almost feel like, why? I should have infinite tabs open and some system should know about it. If I ask it, "Bring that back up" — like, that's a total need.

The reason I put Anthropic at number two is their models are crazy impressive. The new Claude Sonnet model felt like a step-factor improvement over the previous ones. Tasks it kind of struggled with — it's getting better. Both OpenAI and Anthropic have just been boom, boom, boom. Everybody's heard of AI, tried it, maybe used it a year ago. But every three to six months there's just another step and another step. That's the most interesting thing and why I can't pull myself away. Every night this gets me very, very excited — because the progress is still wild.

People are going to say it's going to top out. It will at some point. I think it's going to be absolutely impressive wherever it starts slowing down. It will completely change the way we do any digital work.

## What Would You Build at 21? AI Agents with Wallets [00:20:00]

**Shaan:** You have a company, you have an investment lab, you have this whole place, you have a wife, all the stuff in your life. If you were just 21 or 22 again — bank account's empty, calendar's empty — and this technology existed, what would you be building? What types of stuff would you mess with if it was young hacker version of you?

**Furqan:** I've started seeing agents that could do a reasoning loop, have a directive, and have actions they could perform. Then you combine that — for example, an agent with Twitter. Give it a Twitter account that it owns and controls, so it has its own distribution and conversational ability. Humans can just interact with it. And then you give it a digital bank account.

At thirdweb we're doing a lot of stuff around AI — we have a whole AI toolkit we're about to launch around this. These digital agents, they're not going to have credit cards. It's weird. And the reason I say this is fun and interesting is that humans have done this very well: they've created megaphones for themselves, they've created businesses and payment rails around that. They sell things, they do things, they sell services.

I think it would be something around that. So you'd make a social account — a Twitter account — an AI influencer type of thing. That's the first obvious thought. But if I played in this space, I would be creating the digital equivalent of a company: a CEO of a thing, the ability for it to market, and the ability for it to make money. Not an influencer. I don't know what it would produce.

**Shaan:** AI drop shipper?

**Furqan:** Yeah, like an AI drop shipper, or like FBA Amazon. What's that example you were telling me about where somebody did this?

**Shaan:** They made a Twitter account, gave it a wallet, Marc Andreessen gave it like $50,000 of crypto — can you tell this story?

**Furqan:** So there's this thing called Luna or Virtuals. They built a little platform to have AI agents run. And I think what's cool is they did this equivalent thing where it has a crypto bank account and access to Twitter. This was a kind of marketing stunt by a company that does this, but what I think it did is capture exactly what I'm describing: it was frivolous fun, it was play — not working backwards from some giant thing.

And it did some really powerful things. There's literally a live thing where you can watch its reasoning as it's pulling its tweets. I'm on it right now — terminal.virtuals.io. This is what an agent does. It starts with high-level planning, current state of execution. It says, "I've done this so far."

I think they told it: you're kind of like a public influencer bot, you have access to crypto. It's a little bit in the memecoin world. But it could negotiate for tokens, buy and sell things, operate together.

What I think is really cool is you can actually see its thinking. This was thirty minutes ago. It says: "Current state of execution: I have attempted ten tasks so far, seven successes and three failures. My Twitter metrics show average engagement on my recent tweets and I've lost three followers." Then it has a reflection section. It says, "I've been engaging with my followers to build a personal connection" — which is hilarious because it's an AI bot — "however I've also experienced some failures in replying to tweets due to invalid parameters." And then: "I'm feeling a bit concerned about the loss of followers, but I'm also encouraged by the successes."

**Shaan:** "I'm feeling a bit concerned" — that's crazy.

**Furqan:** And then it says, "Plan: given my current situation, I need to focus on building a relationship with my followers and increasing my visibility." And then it starts to say what it's going to do.

Doesn't this sound like a human sitting in some growth team somewhere, thinking about how to grow your Twitter account? You could give it a directive, give it some direction, and let it compute against itself — compute plans, reason, observe behaviors, try to find patterns. These are all human tendencies, human behaviors, especially when we work.

This is one of those perfect views where you could start thinking: this is a digital-only task. It has Twitter, distribution, marketing ability. It has payment ability. It's going to just continue. You could improve its directive, change its incentive. But I feel like we're going to get to a world — I think Sam Altman said this — where you have the one-person billion-dollar company. This is already happening. We're already experiencing another ten-x decrease in how many people you need and the abilities they have. I think it goes down to probably one or two or three. That is a total shift to everything — how we work, how companies are built.

## Oasis and Generative Video Games [00:28:00]

**Shaan:** Should we switch to hardware stuff, or is there any other AI stuff worth covering?

**Furqan:** There's this thing called Oasis. You know how there's basically a game that's fully built in a generative AI model? They built a game like Minecraft where you can just describe a world and it makes you a Minecraft world. Every step you take is not a pre-programmed pixel — it's actually generating on the fly.

A normal game: the game maker builds the map, it exists, you run around in a predefined map. What this does: you give it the idea, but when the character runs, it's creating the map on the fly. You can kind of play this Minecraft game. You can see it's still crappy pixels, not great resolution, but you can move and it does stuff.

Whether it's video games that take a lot of effort and time to produce, or content creation and videos — it's starting to become way closer to reality. A whole movie will be generated on the fly on exactly what I want.

**Shaan:** Like, the Raiders lost and I'm going to go watch a movie after and it's going to have this context and give me a feel-good story. Let's brainstorm — like NBA highlights. You used to have SportsCenter. If I didn't watch the game I had to turn on ESPN, wait till basketball came up, then watch the top ten highlights they picked. Then YouTube came around: forget waiting, forget the TV, just search anything — search only Steph Curry three-pointers. Now it's going to be: I put on my headset and say "Show me what happened in the basketball game" and it'll just start generating a highlight reel nobody has ever created, just based on my prompt. And I might be able to say "Don't show me any Lakers clips, only Warriors," and it'll auto-adjust on the fly.

**Furqan:** Yeah, that's interesting. We're going to go from humans making content to machines making it toward our taste and liking. And then there's always this worry — well, what happens to all the humans?

I think we get back to that core thing: machines will never have true taste. Creativity is always going to come from humans. There's always new fashion, new content mediums, new everything. Machines will learn it and lag behind, or maybe get ahead of it. There's always going to be another person that shows up and does something different. I think taste is going to be the ultimate thing that probably won't go to a machine — it could reason about it, it could try to invent it, but I think we're not that predictable.

**Shaan:** I want to believe you because it sounds good. But then I also think — well, right now, if we said taste is knowing what's good and bad — TikTok, the most popular and most addictive app, their algorithm is basically saying "I'll choose what's interesting for you." And it does it so well. Isn't that kind of taste also?

**Furqan:** It is, and it works really well. Selection is incredible. It probably is more like what we want than we'd even admit. I don't want to want it — the other day I was talking about how on Twitter my "following" I love and my "for you" I don't. But it's like, really? Why did they pick this? There's a status thing — "I don't use the algorithm." It's like saying "I drive stick" or "I hand-make things." Cool, but brownies out of the box work for everybody.

I'd love to trade algorithms for a day — "Yo Shaan, what are you watching over here?" We have our own blind spots. I think this is one of them — our actions prove it. We love things we claim we don't. And machines could be great at this too. They'll learn humans, maybe get even better. But I just feel like we're a little unpredictable — we make choices that almost go against our own patterns. And machines try to be too perfect. My Netflix algorithm is probably accurate for me. But sometimes I just want some different stuff. The algorithm drives me down one direction and once in a while I want that ten, twenty, thirty percent variance. I don't think algorithms do that exceptionally well.

**Shaan:** How long until the number-one hit song in the world is an AI-created song? If we're doing over-under, 2025 — would you pick the under?

**Furqan:** I might pick the under in 2025. That would be a good bet. Like a Polymarket thing.

## Polymarket: What They Did Right [00:34:00]

**Shaan:** You showed me Polymarket years ago and I started making bets before they blocked it in the US. What did they do right that Augur and the other guys who had the same general idea didn't?

**Furqan:** I feel like timing is a big part of it. The sweet spot: people are way more digital. I think COVID drove a lot of people online — we sat at home and suddenly we're 24/7 on the internet. That really exploded internet usage and e-commerce. I've seen graphs where those things were growing and then there's a massive jump.

Remember we were at Twitch when that happened? All the metrics looked amazing. "What did you do?" "Well, we were here." We don't create the wave, we surf the wave. A huge wave happened for Twitch — Fortnite came out and then COVID happened, two humongous waves back to back.

I think it's a combination: we're way more digital, news and where we get information has totally changed. Then there's a bunch of people online who want a stake in the political thing — they want to root for a team. Politics has become very much a team sport. "What do I do with my support? I can give money or I can give attention." So I think a lot of those things set up good conditions for Polymarket.

And then the best thing for them is they got it right. Right place, right time, and the answer was right. If Polymarket had been wrong on the election, the story would be much different. People who want to hate on crypto things, who want to hate on betting — they would have ripped on it much harder than they're ripping on the polls right now.

**Shaan:** You saw this thing about the French whale on Polymarket?

**Furqan:** The big whale that came in — the narrative from the polls was it's a tossup, razor close, 50/50 election. This guy came in and bet something like thirty or forty million on Trump. People were like, "Is this guy trying to manipulate the market? Is he real? Is he a rich billionaire son?" On my way here today I saw something. It said he bet because he believed Trump would win. The reason he believed that: he funded his own independent polling, thought he was getting better data that said Trump was mispriced. So he just made a logical, rational bet — "I'm French, what do I care about the politics? I just thought there was money to be made." He went counter to the narrative and made something like twenty to thirty million dollars.

The funny thing about Polymarket — we can't use it in the US. So three billion got bet on our election, and we're the ring. Two boxers going at it in America, and everyone else is betting from all around the world on who's going to win. Kind of a hilarious dynamic.

## VR: The Sleeping Giant [00:40:00]

**Shaan:** You have a good contrarian opinion about VR. If I walked out of here and talked to a hundred people — AI, Bitcoin, sure. But VR? Sort of lukewarm. Most VCs feel like it's a dead-end and AR glasses are the future. But you've been staying with VR when the narrative has gone against it. That's always where there are big business opportunities — when the narrative goes one way but the reality goes another. Give me your VR take.

**Furqan:** You remember 2020 — I asked you for your address. I owed you a headset. I was like, "Hey, this Quest thing is different."

**Shaan:** That's a real friend right there — sends you a VR headset. It's probably collecting dust, which is okay.

**Furqan:** That's kind of how I think about things. Technology takes a long time, and it typically takes longer to get there than we expect. Especially for people early in the industry who are really wanting to push it — AI, crypto, VR all have the same problem. Early on, people are really pushing something that's not ready. Big hype, it crashes, everyone moves on. That's happened in VR a few times. For most people it's been quiet.

But I think it's a sleeping giant — a massive sleeping giant. Here at Founders Inc I get a chance to see it every day. We invest in VR companies, we have a whole corner with maybe twelve devs building different VR products. It might be the highest density of interesting VR projects in one place.

Quest 1 came out — wireless, kind of crappy, but you could sit on your couch and use it. It was cheap. Became a great Christmas gift. Year two they didn't have inventory. Quest 2 got even better — lighter, more powerful. Now Quest 3 is out and I think they have five to ten million monthly active headsets. That rivals consoles. Quest has sold over twenty million units, the majority being Quest 2. Quest 3 has sold about a million units at the five hundred dollar price point. It's outpaced PS5 sales. That's pretty good for something people call a failure.

The first use cases were immersion gaming, Beat Saber — natural entertainment. Then it kind of goes up and down. People get used to those first experiences. Because it's cheaper than a PS5, the Quest 2 was available at Christmas, went to twelve, thirteen, fourteen year old kids. They don't have our bias of many years of existing structures. A lot of games formed — specifically social games.

Gorilla Tag — have you heard of it?

**Shaan:** What is Gorilla Tag?

**Furqan:** It's a social multiplayer game, really fun. On App Lab it did tens of millions. It's like a fun social game you play with a bunch of people. If you go in, there are a bunch of teenagers screaming at each other — but for them this is the environment. They didn't grow up with the things we grew up with. The TV feels ancient, the desktop feels ancient, and this thing on their face feels fresh. Gorilla Tag has done two hundred million dollars of revenue.

We have a few teams here at our studio. One called Fluid is building the best browser in VR — multiple displays, as many tabs as you want, customizable environments, AI environments. You say "I want to be in a cave" and it makes you a cave. Social multiplayer so people can show up in your environment. On App Lab it's doing about five thousand weekly active users — small team of three, without big burn, just building and growing. We're not even in the main store yet, just App Lab.

Another product called Yeps — the second game behind Gorilla Tag. Small team, less than ten people, mostly built with a few people.

**Shaan:** Is it profitable?

**Furqan:** I'll let them talk about their numbers, but on a scale of "that's pretty good" to "wow" — it's wow.

The thing about this is supply and demand. You can go be app number five million in the App Store, or if you're talented you can be one of the top twenty VR apps if you put in a year of hard work. Same way that right now if you're a content creator on Instagram it's tough, but post on LinkedIn and you'll get tons of distribution if you're half decent, because there's no supply of quality content. Even if VR is not becoming this global phenomenon at 200 million units, you can still build a great business. And then when the wave hits, you're very well positioned to be the leader.

Everything we do is emerging tech. The theme of all of it: survive. If you make it to when the industry happens, you will grow with it. If you were a small percentage of the industry and the industry grows by 100x, you grew by 100x or more. I've seen a few small teams at ten million-plus a year — five people, totally profitable.

Is it VC investable? Honestly I don't care. What I care about is: can you make these bets without massive capital expenditure? When it's three to five people with a limited amount of money, just them — that's the basketball analogy. We have everything we need: the talent, the ability, the tools are amazing now. And the environment's forming. Meta has let it breathe. The Quest platform is real. You could build a profitable business or a fairly big game on it right now.

Also, Apple when they enter an industry, they come with a unit. It needs improvement, another unit comes out. Then you have Snap, you have Meta with Ray-Ban glasses. This trend toward compute in your spatial view — is happening. And with the two biggest players, they're going to keep making this hardware better. They're going to be super hungry for content.

**Shaan:** The sneaky thing about these spaces that I didn't fully realize until I moved to Silicon Valley — a lot of these require really specialized talent. I remember when I first met you, you were like, "I'm really into Big Data," and you started saying words like Hadoop. I didn't know what you were talking about. This was like 2015 and you were like, "I think this big data and machine learning thing is really interesting." You were early on that. Crypto same thing — you were early. There weren't a lot of smart contract developers.

So even if you don't have a hit product — if you just assemble A+ talent that's super specialized, then as those platforms rise, your team itself becomes a hundred million dollar asset.

**Furqan:** Exactly. If you built today for Meta Ray-Ban, that product's actually a hit, and everybody wants to be in the glasses space — if you built a specialized team that's good at developing for that platform, there's just not a lot of great teams that do that. That's a hundred-million-dollar team even without a hit product. With a hit product, you get a billion.

**Shaan:** How hard was it to find an iOS developer when we were starting to do mobile? Dude, it felt so specialized.

**Furqan:** I remember 2012 — not even early — we had one iOS dev on our entire team and it was so hard to recruit talent. It was faster to just retrain. We stopped working and the iOS dev trained all of our other devs to be good enough to be dangerous, because it was so scarce. And iOS wasn't even that specialized compared to the fancy AI stuff or VR/mixed reality talent.

I think about kids growing up — the thirteen to fifteen year olds who have a mobile phone attached to them, who think it's superior to a computer or desktop because it's with them. We're going to take the second computing interface where we do more work and more immersive experiences, and put it around your eyes. That makes way more sense to me than TVs, desktops, and even laptops. And that was one of the thoughts behind starting Fluid.

I remember we did that experiment where you worked in VR for an hour a day, and you ended up doing it for a few months.

**Shaan:** Yeah, I was like, "This is great." And it had been just sitting with me.

**Furqan:** That's one of the reasons I built a studio — I want to do all these ideas I can no longer do all by myself. I just want to find really hungry people and match them together. That's how I found John at Fluid. He was a PhD student, going to go do something in finance and high-frequency trading. But he came to this idea: when he was doing his masters, he wanted to go into a focus mode — could he just go into a cave and lock out all the distractions? He tried it in VR and it wasn't good enough. He kind of left it at that. Then we were talking, and it was like: cool, we're not going to blow ourselves out, we're not going to raise a lot of money, we're not going to get a giant team. We're going to get three people, grind, work hard, build, and survive. When this thing happens, we'll miss some bets but gain ridiculous amounts of knowledge of the industry.

## The Ethereum Miss and "Survive" as the Only Rule [00:53:00]

**Furqan:** You've told me before: "I think my superpower is that I'm usually in the first thousand or ten thousand people to try any new technology." I remember we were at work and you were buying the Ethereum pre-sale, the ICO.

**Shaan:** I came in telling you about it. I'd stayed up all night reading the white paper. I'm like, "We've got to talk to everybody about this." And I think your reaction was —

**Furqan:** I wrote it off. I said "Ethereum — that name's stupid." I think I also said something like, "We have real work to do."

**Shaan:** You could have been totally right.

**Furqan:** I wasn't. That's all that matters. Very, very off on that one.

**Shaan:** But you said another thing today that I hadn't heard: for emerging tech, there's only one rule — survive. That reminds me of Ryan Petersen from Flexport. He said the same thing: "I realized I cannot control the timeline. All I focus on is being default alive — staying in the game. If I'm in the game, I'll just keep trying things until I figure out what works. The only way I can lose is if I have to get out of the game, which usually means running out of funding or burning too much capital." He said that's been the name of the game from when he was flipping scooters on eBay to running a multi-billion-dollar company.

**Furqan:** Technology takes a long time, but when it hits, it happens very fast. That's the part people don't realize. They underestimate how long it's going to take and overestimate how fast it's going to happen immediately. Uber was an example — we saw it, it was black cars. "It's just an expensive taxi nobody's going to use." Now it's like, "This place doesn't have Uber? How am I going to get around?"

I enjoy it because it's like a lifelong game. I could just play technology forever. I don't have a rush to be there first. It's more like I need a few people who are really excited about this, who see it like I see it, and we're going to go on this mission. And luckily now I have the ability to fund that and create my environment to do it. That's what this whole building is.

Naval has the best quote on this: "Impatience with action, patience with results." If you go against somebody who operates like that, they will win. You cannot lose if you're constantly impatient with doing things while being patient with results. A lot of founders are impatient with action AND impatient with results. Or non-founders are patient with both and nothing ever happens.

## Founders Inc: Why He Built It [00:57:00]

**Shaan:** Let's talk about this building, because you've basically built your dream man cave. You had a big success with App11 — Apple acquired it, eventually it became a fifty-plus billion dollar company. But it was a crazy story — we were sitting in the office and this news happened, like "Dude, congrats, that's amazing, holy shit." Then nine months go by, the deal doesn't fully get approved because it was such a big purchase by a Chinese company. In the meantime, the business just kept crushing. So then Adam, the CEO, went back and said "Cool, we'll still do the two billion but now it's for thirty percent." The company eventually IPOs, you get this nest egg.

You could go retire, buy islands and cars, do rich-guy stuff. Instead you chose to do something else. What was the mindset?

**Furqan:** My whole life I've just always wanted to tinker and build stuff. I always described it as: I love taking stuff apart and putting it back together. It's not like I want to learn how it works — it's more the puzzle of "How did somebody else put this together?" I used to do this with cars and computers growing up. I would overclock my computer and make my car faster.

Then I was like, okay, I've got to become an adult at some point. "I like this business thing, I buy and sell stuff — it's a way for me to hustle and do more of what I want to do." A lot of that early journey was more solo than with a bunch of people. Then I met the guys — Adam before App11, various others. Being eight people in Palo Alto building cool random apps, the energy every day was through the roof. Monkey Inferno was the same thing but even more so.

I used to tell you: I want an airport hangar, I just want to put cool stuff in it. Before I started Founders Inc I was at Twitch and I'm like, "I've got to get out of here." Instant. Why? I don't think I'm a good employee. I'm suited for doing my own stuff. There was this resistance feeling of "Oh, we already thought about this" or "We tried this" — "No, let's just go do stuff." I never enjoyed that.

I talked to probably seventy-five to a hundred founders before starting Founders Inc. I really wanted to learn what they needed. I thought they were all going to say money. But they all said something different: "I need people who understand my problems."

We used to do masterminds, and it was really about: who do you go to for founder problems? Your co-founders, your employees, your investors — you can't go to any of these people. They might be the problem. And even if they're not the problem, you need to maintain a certain aura of momentum and morale. You can't just dump problems on them or be like "I don't know" — you're supposed to know, you're the guy.

We would go in that little circle room, and I don't know what the employees were thinking — "These guys are talking again, they're going to come out with something different." But we could talk about anything and leave the room and be like, "No, we're still where we are." That was valuable.

When I talked to a bunch of founders, they all said the same thing. I was like, "I think it's something more like this — where I could put everybody in a room together." I thought it was going to be more digital. COVID times, started on Discord. A few people I knew — Farza, Ben, a few others. Just people around me. We were talking every week, doing these accountability "ship it" sessions.

Then I got an opportunity to get this space. I was from the Bay Area, so San Francisco made sense. But I was like, if it's going to be us, we're going to be on the water. We found this weird opportunity late 2020 — took about nine months to figure out and another three months to renovate. This place had three hundred events a year before COVID, then went to zero. Art galleries, art schools — didn't know what to do.

That was one of your tricks too: you don't run away when the dips happen. I remember when Bitcoin cut in half and you said, "Oh, this is great — now everything's half off." You told me if I buy now I can cut my average price in half. I bought more. Thank you for that. And you've done that with San Francisco real estate during COVID, with crypto, with VR — when things go out of fashion, you don't run away.

**Furqan:** I'm technical, so I live in GitHub projects, I live where the builders are. If I see somewhere where the narrative says "it's dead" — and then these people over here are just shipping more code, and nobody told them it's over — that's the perfect environment. Even if you're right one out of five times, you'll be right in such a big way that it works out. And for me it's just fun.

## Adam Foroughi and App11: Lessons in Execution and Project Selection [01:07:00]

**Shaan:** You worked with Adam at App11. What's special about that guy? What's his superpower, or a story from him that you remember?

**Furqan:** The cliff notes — Adam did some stuff in equities or trading at some point, got into ads through marketing and affiliate stuff, built a few different products. He and this guy John — John had done a lot on the internet, was more the technical person. Adam was more the business person. Their skills were incredible, their personalities incredible.

For Adam, the thing I felt the most — I think it was the first time in my life I was like, "This is what A+ execution looks like." This guy just hits it. If we were talking about something and made a choice, within minutes that was delivered to the team. When we were an eight-person team, most places decide something and go slow — "We'll do it next week." No, it was immediate. Moving on from something: immediate. New idea: immediate. It just felt like, "This is what execution is." Think, decide, act. The delay between "decide" and "act" is usually the problem.

**Shaan:** Similar to what you're saying about me when we first met — you said, "I think this person's product thinking, ability to unpack a complex thing — you see A+ talent and you want to work with it."

**Furqan:** For me it was like ten or twelve years of an almost solo-founder journey. I never saw somebody else where I was like, "I want to learn these skills from this person, and I bring something to the table too." I felt that with Adam.

One thing I've come to learn: at Monkey Inferno we had a beautiful setup. Good funding, great team, San Francisco, really talented people. I don't think we had the level of success we could have given the talent.

My take: we were good at execution — maybe even great execution — but poor project selection. We were going after these moonshots: "Create the next hit social media app." There have been like seven ever. There's not that many that exist.

What one thing Adam did aside from great execution was project selection. They were working on one thing, he went to a conference, came back with that quick think-decide-act loop: "We're doing a mobile ad network, not mobile games." That one choice at that time was the make-or-break moment. A multi-hundred million dollar fork in the road.

**Furqan:** We had many of those moments too. We built Blab — it was basically a public live-streaming version of Google Hangouts. When Clubhouse got popular, we had built basically a Clubhouse before Clubhouse. It got to four million users, but it didn't become the next thing.

I don't know if you remember this conversation, but we had this one time where we were deciding — do we do a mobile version because we see other things happening, or do we do the B2B version? And Zoom didn't exist at that time.

**Shaan:** And we were like, "B2B — that's not cool." At the same time, it wasn't hidden either. Citrix was a multi-billion dollar product and Citrix Online was how people did webinars. SAP and Oracle were using our tool just because it was better than Citrix, even though it was meant for something different. Instead of looking at those clues and thinking, "Hmm, maybe we could do that" — we missed that project selection choice.

**Furqan:** And when we decided to end Blab — I don't know if you remember, you went to a barbecue and met James Currier — they were talking about the content network problem. The moment that entered our mind, it was like, "Oh, we're screwed." We couldn't intersect the content. We kept looking at Twitch: why does Twitch win? People come on for an hour, do a show — the epic content doesn't last long enough for people to show up. And it turned out Twitch wins because people play games for eight to ten hours. It didn't matter when you showed up.

So there was a lot of that — the stubbornness of "We want to build a giant social app." If we had unlocked from that a little earlier, we would have caught those project selection moments. I still feel that sometimes. But maybe it's because I'm older and less willing to be nimble in that way.

## The Hardware and Robotics Renaissance [01:18:00]

**Furqan:** I wanted to talk about one more thing: hardware and robotics. For a long time, hardware has been too hard, too expensive. Software gets funded in the Valley. "Hardware is hard" — those were all the mentalities. I think it's flipping. A few things have showed up together.

There are two types of hardware that are now viable: consumer products and robotics/deep tech. The recipe: can small teams do it? Can you do it without a lot of funding? Can your output be really big?

For consumer products — the combination of Raspberry Pi and cloud AI has completely changed what it takes to build something. There's a company in our studio called Magical Toys. They're building an AI teddy bear. Fatin is like twenty-four, twenty-five. He doesn't have huge funding or a huge team.

He'd done some small projects in college — he built this thing called Desk Buddy. It was a little e-ink screen with two eyes that just blinked. That was it. It couldn't talk, couldn't do anything, just a little desk buddy so you're not alone. But I saw it and thought, "That's cool, I want one on my desk."

They tried a bunch of ideas. With Raspberry Pi, they could do these little things. With 3D printers, they could build enclosures. With cloud AI, they could make it really powerful. They ended up building a toy. First they literally took a stuffed animal and made it talk. I was like, "This is wild."

I think we sent you one of the first units.

**Shaan:** Yeah, probably broke. You gave me a teddy bear with the whole computer just hanging out the back, like half-done surgery. But I gave it to my kids — they were probably two or three at the time. And every other toy in our living room is pre-programmed: push this button, it says this thing, that's all it can do. With this toy — ignoring the thing hanging out the back — it was like: "Hey, we love Paw Patrol, can you ask us some Paw Patrol trivia?" It said, "Certainly! Who is the red dog in Paw Patrol?" "Marshall!" "Correct!" And I was like, "Can you keep track of our points?" "Okay, two points." And my kids were blown away, because now you have an infinite toy. Every other toy is finite. Now you have a toy that's basically ChatGPT shoved into a stuffed animal. It can do anything.

**Furqan:** What was cool is Fatin in this little lab — we started with an empty room. People would walk by: "What's this room for?" "Oh, it's going to be a machine shop one day." "Can I use it?" "Yeah, what do you need? Tables? Great, we'll bring tables." 3D printers? Added. Electronics? Added.

Fatin built one, showed us, built another, tried different versions, printed new cases, bought new Raspberry Pis, iterated on software. He shipped like sixty to seventy units across four to six months. In software that feels like nothing. In hardware this might have cost half a million to a million dollars. I think we did it for fifty to a hundred grand. One person, 3D printers, Raspberry Pis, some AI, delivering units and getting feedback. That is the inflection.

Sam calls these inflections — something changes, and then it unlocks the next thing. Obamacare came out, Oscar Health built something to do exactly that, became a billion-dollar company. Phones with GPS: you can build Uber. Phones with cameras: you can build Instagram.

You're saying: Raspberry Pi + AI + 3D printing = consumer hardware is now possible. Two people can mess around and tinker until they get something right. Couldn't really do that five or ten years ago.

**Furqan:** Correct. When we built Jamie — our voice-control thing that was kind of like an early Alexa — I used a Raspberry Pi. At that time, Raspberry Pi was thought of as an obscure market for tinkerers. They've sold like sixty million units now. A few billion dollars of Raspberry Pi in the world.

What it did: you used to have to make custom boards, custom software. For a technical person like me, it felt too far even for somebody like me — like, "I need ten people and millions of dollars and to convince somebody there's a big market." Now you don't need any of that. And there's the Nvidia Jetson now with on-device GPUs — there's so much more.

**Shaan:** What other things besides Magical Toys are you seeing built on the hardware/robotics side?

**Furqan:** We have AJ building Neurosity — the brain-computer interface. He built the first version, which I've shown you before. Now he has a second version that's tiny, like the size of AirPods. Special purpose. The ability to prototype, improve the design, get hundreds or thousands of units out there — doing that without a giant team allows you to continue iterating.

The second area: robotics, drones, and the world of physical equipment. Forklifts, lawnmowers, cars — all these things that require a person. We invest in Lucid Drones — they built a power-washing drone that can go up on buildings and power wash the glass instead of people hanging off the side.

**Shaan:** Is that working? Do people use it?

**Furqan:** Working very well. And what's interesting is the business model. Most people think you build this product, replace the humans that manually wash a building. What actually happens: there's a small business — Dave's Power Washing — five people. If you sell to those small businesses and give them more tools, they can serve more buildings, do it more efficiently. That distribution is built in.

I've seen one for farms — mowing weeds around certain fruits, inspecting them. You used to send two people between the rows for two weeks. Now there's a little robot, and one person monitors it in air conditioning, watching on an iPad. When it gets stuck early on, they go fix it. That efficiency is massive.

I saw two guys here in San Francisco — random warehouse in the back of some other store — just grinding, bootstrapping. They took a forklift, automated it, took self-driving car tech. That technology probably took billions of dollars to develop, and then it flowed to open source. They strapped cameras, some LiDAR, a little computer onto a forklift. You could talk to it, get it to do things. They're using the same computer vision technology that scores Fortnite games to look at barcodes and navigate a warehouse. "Oh, that pallet's in the wrong spot," scan the barcode, go pick it up, move it over there. These problems exist in warehouses everywhere.

What are the traditional machines we've built for the last hundred years — forklifts, cranes, lawnmowers — where you just put a little computer on it and now it's a superpower? This is bringing down the cost of what used to be called deep tech. Building a robotic arm used to mean being like Tony Stark. Now I've seen two people do it in a machine shop.

There's a guy here — I don't even know his company name — who just had a 3D-printed hand on his desk. "What the hell is this?" "Oh, I created a full hand with all the fingers in just a 3D printer." There's a Bambu Labs printer — 3D printing was great, but Bambu Labs took it to a whole other level with a little AI for self-leveling. He just built this hand, pretty high quality, with fishing net on the inside of each finger so he could pull every finger and do different things. One dude, a few months of work. You could do these things now in weeks and months when they used to take years and millions of dollars.

## The Garage: Betting on Hardware at Scale [01:28:00]

**Furqan:** For us, we're going even further. We built this founder lab here — founders, builders, creators come to tinker. I ended up getting an industrial space I call the Garage. It's twenty thousand square feet. San Francisco real estate is not the best right now, but I think this is the time to make these bets. I've talked to twenty-five to fifty founders in the last twelve months who need a hardware space like this — to tinker, have smart people around them, have the machines around them — to proof-of-concept and prototype for less than a hundred grand.

We're seeing the hype cycle of humanoid robots. I'm more excited about all these startups forming, building this expertise, becoming hundred-million-dollar teams — whether it's their product or just their knowledge. Two people are spawning these things every single day.

I've seen people building cooking robots, laundry folding machines, drones to inspect stuff, drones to map interior spaces. Matterport is a giant company where a human puts a tripod everywhere. There's a little drone that flies through a whole house and maps it for you.

We do these residencies here — we'll bring people for a month or six weeks around a theme. When Vision Pro came out, we had about forty Vision Pro devs — probably the highest concentration anywhere outside of Apple. The knowledge from that was incredible. We did an AI hardware residency too.

I met this kid — he built a humanoid robot in his bedroom. Half of one, just the legs. Totally handcrafted. It could take steps. That's crazy to me.

Then there's a team — Premiere — they took the Raspberry Pi trend and ran with it. I jumped on a video call, they were up in Seattle or somewhere, and their kitchen is just machines. I'm like, "Is that a 3D printer in your sink?" I told them, "You've got to get out of your house, come do this here."

They took this hobbyist behavior and built a business around it: people start with Raspberry Pis and then build a custom board. We're building the intermediate modular step. Oh, you want a speaker? Pick whatever speaker you want, plug it in. You want to produce two thousand units? We have the ability to scale it for you. Starting literally in their kitchen.

That's the trend that I can't unsee. In hardware — both consumer and deep tech — massive opportunity. I don't know how long it's going to take to become mainstream, but I just keep seeing it. And for us, we want to bet on negative one to zero. Peter Thiel talked about zero-to-one companies. We're one step even before that — you're at negative one, wandering the forest, you need a place to tinker and let the ideas form. That's what we want to do here.

**Shaan:** Love it. Furqan, this is amazing. Good catching up as always. Let's go check out some of these spaces.

**Furqan:** Let's do it.
