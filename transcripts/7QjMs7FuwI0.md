---
title: "Brainstorming $10M AI Business Ideas w/ the Airtable Founder"
type: episode
date: 2026-01-21
speakers:
  - "Sam Parr (host)"
  - "Howie Liu (guest, Airtable founder)"
tags:
  - live-shopping-with-ai-avatars
  - ai-personalized-news
  - personal-finance-ai-advisors
  - ai-voice-call-centers
  - cursor-for-email
  - ai-productivity-tools
  - exotic-ai-consumer-apps
  - airtable-product-direction
  - startup-frameworks
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/7QjMs7FuwI0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width:100%; aspect-ratio:16/9;"></iframe>

> Sam sits down with Howie Liu, founder of Airtable (valued around $10 billion), to brainstorm seven AI business ideas Howie would pursue if he were starting from scratch today. They cover live shopping avatars, personalized AI news, financial planning tools, AI voice calls, a Cursor-for-email concept, and exotic consumer AI applications. The conversation weaves in Howie's framework for evaluating startup markets — go very broad or very deep — and Airtable's own pivot toward agentic-first product design.

**Speakers:** Sam Parr (host), Howie Liu (guest, Airtable founder)

## Introduction [00:00:00]

**Sam:** All right, my friend. I recorded one of my favorite types of episodes. My friend Howie started a company called Airtable. They're worth around $10 billion. He has seen it all, he knows what's going on in the world of AI, and he has an amazing perspective. For this episode, I asked him a very simple question: if he were 21 again today, or didn't have Airtable, what companies or business ideas would he want to work on? He came with seven different ideas. So if you are looking for a business idea or you're an AI nerd — which a lot of us are right now — you're going to love this episode.

---

## Idea #1: Live Shopping with AI Avatars [00:00:35]

**Sam:** Tell me about live shopping with AI avatars.

**Howie:** I personally think this is a really interesting area. Think about live shopping, which is a huge thing in Asia — there's probably tens of billions, if not a hundred-billion-plus in GMV getting transacted through live shopping. This is basically where you have an influencer peddling a product right now.

**Sam:** Is this like — I pay a little attention to Asia, but is there a website I can go to to see this right now?

**Howie:** There's actually a big chunk of Temu that is powered by this. And definitely TikTok. TikTok has a huge amount of these influencers who basically go and peddle products — there's even a Shop tab you can click on. You see these products and it's a person describing the benefits. Think of influencer marketing taken to the extreme, where you just watch people peddling products and you click and you buy.

There's actually one company doing really well in the US called WhatNot.

**Sam:** Yeah, I like WhatNot.

**Howie:** Exactly. And what's cool about it is there's so much personality to the content. In a way it's almost like watching Twitch — it's not just about the actual product. It's about seeing this person talk about the product. Maybe it's a really cool new shoe from Nike, or a vintage shoe, and they're talking about their own childhood experiences with the Jordan brand. It becomes this really interactive experience.

My pitch for this idea is that you can have really rich engaging experiences in the very near future with avatars. If you go to heygen.com, it's a great avatar product — the easiest, fastest self-serve avatar product out there.

**Sam:** Are you an investor in those guys?

**Howie:** I am an investor in HeyGen. I really like the team there. They built the best, easiest-to-use avatar product — that was kind of their claim to fame. They have pre-made avatars, which are trained on or effectively created from real human actors they've licensed. So you can use one of their pre-made avatars or you can create your own.

I think of this as a really fundamental capability. Think about all the things you can do with avatars — sending a sales video where you're pitching each target customer in a personal way, or a CEO sending a thank-you note via video to every single attendee of their last event.

In this case, applying the avatar concept to live shopping: you can now have this one-on-one interaction with a celebrity. Maybe you get real influencers to sign on — like a Kim Kardashian type who's represented in avatar form — and each person shopping gets to have a one-on-one interaction with her about the skincare products they want to try out.

**Sam:** Are you guys using any of this at Airtable?

**Howie:** We actually do have an internal setup powered by Airtable. We use our own Airtable web agents to research different target customers, learn a lot about them, and then generate customized email pitches for each of them. Right now it's just email, but we are experimenting with more of the video stuff.

We have a setup internally where we can now generate an avatar video powered by HeyGen automatically from content in a row of Airtable. So it could be a list of different event attendees. That use case I just described — I may actually do it for thank-you notes for different events I host in the future. Like if I host a dinner with some of our customers, I could go and automate creating a video that looks like it's me. I'd probably be upfront about it and say, "Hey, here's an avatar version of Howie saying thank you for coming." The novelty of it itself would tickle people's fancy. But the idea of sending a personalized thank-you video from me to every attendee for all of our events — that's the use case.

**Sam:** Can you do that now? If I wanted to implement that, how would I set it up?

**Howie:** You can do it today. It just requires a little bit of scripting in Airtable, and you can actually generate that script with AI. The idea is you'd go and create a list of different people you want to send the video to — or a list of topics you want to create a video for — and then in Airtable we have a scripting layer where you can define arbitrary code hosted in our infrastructure.

In this case you'd just define the code to go and talk to the HeyGen API. A lot of these AI products have APIs, so you can create your own orchestration layer in Airtable to automatically ask HeyGen to generate a video programmatically for each row, using this avatar. Then you get a link to a HeyGen video that you can directly send to a customer, or download it and attach it.

---

## Idea #2: AI-Personalized News [00:09:20]

**Sam:** What's this AI-personalized news thing?

**Howie:** When I think about my news reading habits, I do sometimes appreciate reading just the front page of the Journal or the Financial Times. There is something valuable about that curated experience — everybody sees the same front page. I actually do get the print edition of newspapers because I like that physical and consistent experience. I know I'm seeing the exact same paper as millions of other people.

But for anything else, if I'm reading something online or if I see a link, I usually just take all the contents and copy-paste it into ChatGPT or Claude and ask it to summarize. I even have some saved prompts to do this.

But what I really want is not just to manually summarize each article. I want something that automatically looks for all the articles that are interesting to me. There are certain topics I care about, and I just want an AI news aggregator that knows what I care about. And more importantly, it doesn't just summarize the news into "here are the summarized articles" — it actually becomes an interactive agent that I can talk to.

You know your friend who's the super news expert, always reading all the articles? Like Nick, our mutual friend — he knows everything happening in the world. You go to Nick and get 30 minutes with him and learn about any topic you want. I want that. I want Nick in AI form, where I can just ask "tell me more about this" and it gives you more info.

**Sam:** Dude, my company — the company I used to own before we sold it — was The Hustle. It was a daily newsletter. This was our pitch to our customers. Our tagline was, "We're your smart, no-bullshit friend who will tell you what you need to know every morning."

And I had a team — it was crazy — three people who would reach almost 3 million people a day writing this newsletter. We were actually tinkering with this idea, and it was so manual. We were like, "What if a user tells us what they care about, we write tons of different bits of news, and we plug it into someone's email based on their interests?" And then we'd even go and get an expert like Howie to comment on some of the stuff and put it in the newsletter. And I was like, "Oh my god, this is so manual." What you're describing — whenever I think about newsletters now — I'm like, this changes everything.

**Howie:** Yeah, but you know, it could still be a great business. You'd just use AI for all of it.

**Sam:** Totally.

**Howie:** And maybe you take it to the next level — like Substack, you allow creators to actually create their own branded newsletters and push distribution for each one. Because you're powering this white-label AI-powered platform, they can very easily spin up their own custom newsletter.

Another direction: you create these different AI personalities. I think a commonly underappreciated thing is that AI doesn't have to be robotic. It doesn't have to be utilitarian "summarize this article in a clean AP style." You could inject it with tons of personality — say, be like a TMZ gossip reporter who sensationalizes the crap out of celebrity gossip. And I think there's just so many interesting ways to play with that.

News by nature is a very high-engagement use case — it's literally something you read every day, maybe every hour. The opportunity to change how people interact with finding out about this stuff — there's going to be a very large business created there. Buzzfeed, The Hustle, all of these were high-growth businesses in that era of news. I think now there's going to be a different high-growth era of AI news.

---

## Idea #3: AI Personal Finance Advisors [00:16:45]

**Sam:** Are you a personal finance nerd?

**Howie:** Kind of. I was a very early Mint user, and I remember really wanting visibility over my different expenditures and aggregating it. The tedious act of going and doing a lot of planning is not my forte. But I now have a multi-family office type setup that helps with a lot of that.

You listed on here: real-time AI avatar products for different vertical applications, like personal finance advisors. Tell me about that.

**Howie:** The idea here is that if you're a very high net worth client, you can get a very strategic wealth adviser who literally sits down with you, looks at your balance sheet, looks at all your assets, and talks about your goals. They actually come up with a plan almost as good as a CFO's plan for a real corporation — but for you as an individual. The business of you, Sam, as an individual. You can plan it out, think about the cash flow needs you have, what kind of assets you want to invest into for near-term versus long-term yield.

The reality is most people don't get that level of attention. They don't get that level of thoughtful design applied to a financial plan. And furthermore, most people don't even have access to a live financial adviser to just call up and talk to. There is something very comforting about literally getting to talk to somebody — maybe that's why so many banks still have retail locations even though for most transactions you don't really need them.

So the idea here is using the really smart reasoning capabilities of the newest models. I don't think you could have done this pre-o3, where you actually can come up with a very thoughtful personal financial plan and recommend "here's how much you should invest into equities versus bonds, here's how much you should spend" — but do it with an avatar on top, so it's a very human-like experience. You get to talk to them and just call them up anytime you're feeling stressed about your financial situation.

**Sam:** Do you use any consumer-facing personal finance apps at all?

**Howie:** I don't, because I have this team that I can actually go and talk to. But if everybody could have that experience — I mean, it's awesome. Everybody would be able to plan better.

**Sam:** Have you seen — let me show you one. It's called Kubera. Kubera.com. I have no association with these guys, but I've talked about them so much that I'm actually on their homepage because they quoted me.

**Howie:** Oh yeah, there you are.

**Sam:** And this doesn't matter if you're worth $50,000 or $100 million. A lot of people use software to aggregate their net worth because even if you only have $50 grand, you might own a couple cars, two bank accounts, some money in Robinhood, whatever. And if you're really wealthy, you have many dozens of accounts — some money with this person, some money with that person, probably some private investments.

**Howie:** Right.

**Sam:** And this does a really good job of aggregating all of it. A lot of companies claim they do that. The issue is —

**Howie:** Addepar kind of does that for the high end.

**Sam:** Yeah, dude. Addepar seems awesome, but I think you have to have — I forget if it was Morgan Stanley or JPMorgan — at least $50 million in liquid net worth with one of those banks to get access to Addepar. You have to be more than just ultra high net worth. So Addepar is crazy, but I've never even seen it.

With Kubera, they do such a good job of aggregating everything because the connections don't break. Anyone who's ever used Mint, or Wealthfront, or whatever — the connections to all your accounts break all the time and you've got to re-enter the password.

**Howie:** Oh my god, that's the biggest pain.

**Sam:** These guys have done a good job with that. And what they do is they have a version where you can export the information. Is it called JSON?

**Howie:** Yeah, JSON. So you could export it in JSON format, which is what ChatGPT uses. Or you could just connect your Kubera with ChatGPT. It started as an export, now it automatically does it.

**Sam:** And you can ask it questions. What I've done is I've used Kubera to upload all my accounts — when you do this, they don't actually have access to transact, they can only view your accounts. And then in ChatGPT I'll create a project that has a Warren Buffett book, or sometimes a book from someone who's written something on financial advising — because you have different gurus sometimes, different philosophies — and I can use this to ask questions and have my own personal finance adviser. You know what I mean?

**Howie:** Yeah. Yeah. Like, "Give me advice using the fundamental investor theory."

**Sam:** Exactly. So you'll say, "Look, my net worth is blank today. If I want to be at this mark in 10 years, show me what I should do." Or, "If I want to buy a house in 8 years, what would you suggest is a good budget based on what you know about me now?"

**Howie:** Yeah. I'm sure it works great for that.

**Sam:** Dude, it's awesome. Now, having a financial adviser is still great sometimes — the value often isn't in the advice they give, it's the fact that there's a human being you can trust. But anyway, this is how I've been using AI with my finances.

**Howie:** I mean, imagine that experience that you're getting — but to your point about feeling like you can trust a human more. How much of that is based on the fact that it actually is a human versus just the psychology of talking to a face?

**Sam:** I think you and I think that because of our age. Here's what I'd bet: the 18-year-old today, in 5 years they're going to go to the doctor and tell their doctor, "This is the illness that I have and I think it's this" — because what you and I would have said 5 years ago, or what your parents would have said, is "WebMD says it appears as though I have this illness."

**Howie:** Right. Yeah.

**Sam:** Now the young guys just say ChatGPT said this. And the doctor is going to say, "Well, I agree with you, and according to my belief, ChatGPT says blank." I think AI is going to be the stamp of approval. They're going to trust AI more than a human being. Does that make sense?

**Howie:** Oh, for sure. I mean, today it's already better — everybody should be taking all of their personal health diagnostics, like a blood test or whatever, and running that through AI. Upload it, ask it — "Here are my other symptoms, here's how I feel, tell me what I might have or what could be wrong." I've seen so many stories from personal friends and on Reddit and Twitter of people who caught diagnoses that their doctors just missed. Not necessarily because they're bad doctors, although a lot of doctors probably are bad doctors.

**Sam:** Dude, they spend 10 minutes with you. What are they going to solve?

**Howie:** Exactly. I got an injury lifting weights about two months ago and I just used ChatGPT to do PT. They told me what to do, I followed the routine for three weeks, and my back improved.

**Sam:** Totally. I mean, it's literally trained on the best knowledge out there. You're getting the wisdom of Peter Attia meets Huberman meets all of these health prognosticators informing ChatGPT's response to you.

---

## AI and the Disruption of Every Industry [00:29:00]

**Howie:** I've become the most extreme version of an optimist for new disruptive entrepreneurs and startups. The world moves through these different phases. In a stable phase where technology has been pretty stable — that was basically true of web tech from maybe 2018 until Gen AI hit — it was very stable, the technology became very mature, and it really became about how you can leverage your existing distribution if you're an incumbent. So it's really hard to compete against big existing players like Salesforce or Microsoft in that era.

Now it's like all of the assumptions are off and every company is kind of up for grabs. You can look all the way at non-tech companies — say you're a property management firm, half of your cost structure is automatable, if not more. In that world the margins on the business are so low. I actually talked to the founder of a company based in Germany doing exactly this — they're buying up different property management firms and using their own AI tech to automate a large part of the job. And they don't fire people. They keep everybody employed but take on more business as a result. They've quickly become one of the largest property management companies in Germany, if not in Europe, by aggregating these traditional businesses and creating that AI leverage. Taking what probably was a low-margin business to a tens-of-percent-margin business. From a PE standpoint, that leverage is huge.

I think that's a playbook we're seeing a lot of excitement around — every traditional business, especially one that has a large part of its cost structure that could be automated, is kind of up for grabs. Think about call centers, BPOs. There are a lot of offshore companies with literally thousands of employees that you can go and outsource rote tasks to — analyst work like combing through documents, looking for facts, doing research. Support centers themselves are a form of BPO. You have these big call centers that are client-agnostic, taking on business from any client. Traditionally that just meant humans sitting in a room somewhere, hired on demand. Now a huge amount of that can be automated.

---

## AI Voice Calls and the Current State of the Technology [00:33:15]

**Sam:** Dude, I get so many of those AI calls a day and a lot of times they say they are an AI. They're horrible. They still suck. Do you get a lot of those calls?

**Howie:** I do, although I don't pick them up.

**Sam:** Dude, I pick them up. I always pick them up. I want to get to know these people. Sometimes I can hear where they are. Here's what I get all the time — I get a text message that says, "This is Coinbase. Someone in Serbia logged into your account." And I know it's a scam, but I call them and I'm like, let's figure out how this scam works.

**Howie:** Oh my god.

**Sam:** I do it all the time. So I'll spend like — they're like, "What's your name?" I'm like, "Oh, it's Kevin Smith." And they're like, "Oh, I see your account right now." I'll be like, "You do? Tell me about it."

**Howie:** How much do you have?

**Sam:** Yeah. And they go through these whole scripts and I'm like, "This is awesome that you found my account."

**Howie:** That is really — you've got to figure out how to scam the scammer. Like by the end of it, get them to give you their info.

**Sam:** Have you seen the YouTube channels that do that? They're so funny.

**Howie:** No, I haven't.

**Sam:** Dude, there are guys on YouTube with 10 million subscribers. Really sharp guys. They'll pretend like they're old ladies using a voice changer, and they get the scammer to install software where the scammer's webcam comes on and they can control it — it's the greatest thing.

But these AI call companies — they're still horrible. Are you bullish on them?

**Howie:** I think the models have to get better at real-time synchronous interactions for voice calls to fully get taken over by AI. For chat, like you're chatting with somebody — it's already better in many cases. Those chat experiences are horrible with humans because the human is probably doing 20 different parallel chats. They don't really know or care about you. Whereas an AI can be fully attentive.

But I agree, voice is just not quite there yet. You've probably seen that Sesame voice demo — sesame.ai. You can literally call it.

**Sam:** Oh yes, I did see this. Is this a good product?

**Howie:** It's a research team and a demo product, but I think it shows where the models are going. It could be from this team or from OpenAI or 11 Labs — they're all working on making that interactivity better. OpenAI revealed the last voice mode release where you could actually interrupt the AI halfway through a conversation. That was kind of a big deal. It's still not there yet because it doesn't feel right — if you just talk to it, it doesn't feel like a human. But I think that's a frontier we'll cross in the next year or two.

---

## Idea #4: Cursor for Email [00:38:30]

**Sam:** So one of the last things you had on here was AI productivity tools. You said "Cursor for email." What does that look like?

**Howie:** I just generally think this form factor — it's not about using AI to completely replace the current workflow. The cool thing about Cursor is it's not just a chat interface you're using to generate code. It's actually an IDE. They forked VS Code, a popular IDE, and added this agentic coding experience on top. But as a developer you can still be in the code — I think that's actually the value of Cursor.

I just think applying that paradigm to a lot of other productivity experiences. One of them being email. You go in and usually you just click on each email, read each one. You can currently go to a separate product like Gemini, or now Claude and OpenAI have integrations into email and you can ask questions about your email. But I think the ideal experience is actually a blended one where you can do agentic workflows. Maybe AI is automatically doing some pre-reading of your emails, telling you what's important and what's not. Maybe even doing research across your other content sources — looking up info in your other accounts, in your calendar, doing a web search to help you decide, "Hey, I got this pitch from an entrepreneur who wants to be on my podcast. Is it worth my time?" And it can already have a recommendation for you.

You know, one of the places you spend a lot of time today — news, I think email, if you're a developer you're in your IDE — that's where I would attack. Start with where people are actually spending a lot of time, and on first principles, a lot of that time could be automated or augmented with AI.

**Sam:** I want to ask you how you would build this, because from my experience — I had an email company, I know a little about email — email sucks to build on top of because Gmail owns everything. And Superhuman did something interesting: for the listeners, Superhuman was a brand new email client. You download Superhuman and use that instead of Gmail. They recently sold, I think the rumor was $800 million, to —

**Howie:** Yeah, I saw that.

**Sam:** To Grammarly. And it was a very bold mission. I think they fell short — that's what I'm guessing if they sold. But it was a pretty magnificent effort. My question to you is: if you were going to build something like this, you'd pretty much have to start from scratch and build a new email client, not a Gmail plugin.

**Howie:** Interestingly, I also worked in email before Airtable. My startup before was a YC company, ETacts. I think we were the first startup to build a Gmail plugin — and it wasn't like an official plugin at the time. There was no plugin framework. We literally figured out on our own how to hack what's called the DOM, which is the HTML representation from Gmail of the email client, and we literally just injected a UI on top of it with a Chrome extension. We kind of pioneered this idea — "Oh wow, you can be in email and we added our own sidebar to every email to show information about who you're talking to."

**Sam:** But could they have banned you?

**Howie:** They could have certainly sent us a cease and desist and said what you're doing is against our Terms of Service. And they could do some things to make it annoying for us — it's almost like they could just keep moving the target. They could change the layout of the page HTML without making it look different to the user in ways that would break our integration. And that did happen. I don't think it was intentional — they would just update the page, rerender it, and it would change the layout. For a day our extension would be broken and we'd have to furiously code a fix.

That was the really early days. Ironically, Superhuman's founder Rahul was actually the founder of a company that kind of competed with us back then, around 2010.

**Sam:** Rapportive. Oh man. For anyone above probably 33 who was involved in technology, Rapportive was a game-changing tool. That was so cool.

**Howie:** Yeah. So email has been interesting because from the time that Rapportive and ETacts existed to now, email really hasn't changed very much. You look at Gmail — it's kind of the same product. The status quo argument is "it's good enough, don't fix it." But to me, Superhuman was an interesting innovation on email. I don't actually think building a new email client is that hard. Certain things seem really hard to do in theory, but in practice it's actually not that hard.

Like Airtable — obviously it's hard to build, but we ended up architecting our own proprietary database engine to power it instead of using something off the shelf like MySQL or Postgres to power the real-time collaboration parts. And it turned out that was the right decision. It was cleaner and better for us to go that route than to try to repurpose something off the shelf.

**Sam:** But it's harder. You have to raise a ton of money to do that. And getting revenue — I think it would be a slog. Superhuman did not do it fast.

**Howie:** Yeah. And Superhuman was interesting for a number of reasons. I think it was a really good product, but it was hard to articulate what the killer feature or set of features make it 10x better than normal email. It was like, it's faster, they had some nice features like email tracking — but it was hard to say "this is clearly a different paradigm, this is 10x better." And I think with AI, you could now build a product that actually is radically different and radically better.

A former Airtable employee of mine, JB, is now working on a company doing exactly this. I did a little funding round into it — Chiefso.

**Sam:** Oh.

**Howie:** Yeah, I think it's a really interesting space. And I actually think you can build this product without a massive team and a massive funding round. Part of that is because if you're very AI-leveraged in how you build products, you can get so much more done as an AI-leveraged team than you could have done in the past.

**Sam:** It's just hard to build a business when you charge $20 a month.

**Howie:** Meaning it's not enough?

**Sam:** The first one.

**Howie:** Yeah. So one of the premises here is that there is a top 1% audience — and not necessarily 1% richest people, but a 1% power user audience — for whom email is like their life. Probably for you, definitely for me, every VC, maybe even realtors and lawyers. Email is everything to them. If you can make them 10% more efficient at email, they'll pay not $20 but $200 a month. Maybe even $2,000 a month. If you gave me an awesome email product that saved me even 5 hours a week — and not only that, but allowed me to not miss key opportunities. I get literally hundreds of real emails every day that Gmail considers important. With that many coming in, I miss some. And sometimes they're really important.

**Sam:** I have a full-time assistant and it feels like a large chunk of her job is just categorizing my emails.

**Howie:** Yeah, for sure. Some people have a full-time EA who doesn't just categorize emails but goes through and does research on each one and tells you, "Hey, I did some research. This is how you should respond." I think it's a huge space.

One of my lessons learned from Cursor — did you invest in them?

**Sam:** You invested in Cursor?

**Howie:** I did. I was introduced to them by Peter Fenton from Benchmark, who's our investor at Airtable. One of the most phenomenal pickers of talent and opportunity spaces that I've ever met. I remember having a discussion with him: what is the TAM for something like Cursor? You have to factor in that Microsoft exists. They literally own VS Code even though it's open source. They already have GitHub, they have this massive developer audience. How big can an upstart get? This was when Cursor was probably at low millions in revenue.

My argument was that the developer audience for AI-augmented coding is so large. Today you might have around 30 million developers — that's the number Stripe always quotes. That number might actually expand to 50 to 100 million developers as it gets easier to develop. And on top of that, it would be perfectly rational for every single one of those people to pay at least $1,000 a year for an AI coding agent that makes them way more productive — not 10% more productive, but 2x. Maybe even rational to pay $10,000. Now you're talking about a $30 to $300 billion TAM. Carving off even a small few percent niche of that, especially when coding itself is so fragmented — different languages, front end, back end — all you have to do is win a sizable 5% niche and you've built a multi-billion revenue business.

---

## Framework: Go Broad or Go Deep [00:51:00]

**Sam:** Is that the framework for how you think about what's interesting for starting companies?

**Howie:** I think so. You can either go really broad — like the Cursor example, or "Cursor for X." Pick a market that's just so big. Tens of millions of potential target users at least, for whom the value is significant enough that they'll pay for it. Not a free ad-driven product, not a pure consumer product. Pick something broad enough and deep enough where there's a very large pie to capture value out of. And then even if you end up only capturing a niche of that pie, you have a really large business on your hands.

I think the alternate path is to go really deep and narrow. This is more like the property management example — you're probably never going to have a hundred million users who need property management software. But if you go into that vertical and attack it —

**Sam:** You might have 5,000.

**Howie:** Yeah. And if you attack it very deeply, for each one you can extract even more revenue. The most leveraged way you can extract revenue in that case is not just to sell white-label software that you charge a property management firm X dollars per month. You actually take the entire cake by buying them outright, running the PE playbook, and getting leverage on their economics.

**Sam:** And what is Airtable — the first one?

**Howie:** Airtable is definitely the first one. Especially now that we've relaunched the product as basically an agentic-first product. You can literally come in and talk to our agent Omni to ask it to build any app. It's very much akin to the vibe-coding products out there. But the difference is ours is backed by the reliable no-code components we've spent the past 10 years building and making scalable and real-time collaborative.

So if you want to build any business app — for you guys, for instance, if you want a CRM, a way to track people coming on your show, a content pipeline — we want to be the best way to spin up a reliable business app for internal operations. We're not trying to be an external consumer-facing prototype tool. If you want that, go to Replit or V0. But for a business app, the need is at least tens of millions of people who want to build apps for their own business. And every single business should be creating apps this way, probably replacing old legacy software with this over the next few years.

---

## Idea #5–7: Exotic AI Consumer Ideas [00:56:00]

**Sam:** Last question — all you wrote on the sheet was "exotics, question mark."

**Howie:** Exotic ideas for AI — more off-the-beaten-path stuff. I think there are some really interesting new niches that will be created. Like, what's the next consumer social app that's AI native? And I don't think that just means it looks like Instagram or TikTok and it's got some AI features to help you write posts. I think it might mean something like — there are a few startups trying to do this — you have social networks or chat groups where half the participants are actually AI avatars. What does that look like?

What's interesting about this space is that unlike the PE-AI approach, where it's like take a known problem and automate it — automate support costs, automate property management costs — you can very clearly visualize what that looks like. Here I think what's really interesting is that we don't know what the consumer behaviors are going to look like in an AI-native era.

We saw the transition from linear TV to internet to mobile. At each point there were some surprises about the way content and engagement patterns actually changed. It's not like we just took people watching linear TV and gave them YouTube to do the same thing.

**Sam:** We somehow went from TV to watching people play video games on my phone.

**Howie:** Exactly. Yeah. Nobody would have guessed Twitch. So I just think — when you have people who are not just technologists — the first wave of post-ChatGPT innovation was very much driven by technologists who were very close to the models and understood what they were capable of. I think we're going to see more and more people who are actually more artists than technologists, thinking about the artistry of what consumer psychology and behavior look like when you have this new paintbrush, which is AI-powered experiences.

In some cases I think you can create hyper-engaging consumer experiences that could be even more addictive than social media is today. Imagine you have the perfect girlfriend or boyfriend avatar. People are already kind of doing this with ChatGPT or Grok. Grok unhinged — I don't know if you've played with that, but it's pretty interesting. It's the Elon AI product, but "unhinged mode" is where they've taken off all the PG and safety features that ChatGPT and Claude have. So you could have a very explicit conversation with this AI and it will happily engage. Which just kind of shows you that most of the AI experiences we're getting, especially from the big model companies, have been very cleaned up.

**Sam:** Dude, I ask ChatGPT controversial questions all the time and it refuses. I can't answer that. Sometimes I ask about things where I'm just asking on like — for example I love history and if I'm reading about World War II, I'll ask about very sensitive topics, just "explain me this topic," and it won't even touch some of them.

**Howie:** Yeah, exactly. That's the whole debate — it's a little bit like the free speech censorship debate but applied to AI. Like, how much can you actually censor AI for safety and for moral reasons? How much of that is even globally applicable versus what's moral for one culture being immoral for another? It's interesting to see Grok push the boundaries. I mean, it's not completely unfiltered, but it is a lot more willing to go there.

You should try it today. Try the unhinged mode.

**Sam:** Like, I was just trying to learn about the Israel-Palestine conflict. Just trying to understand the background and ChatGPT wouldn't even touch some of the topics. I'm just trying to learn.

**Howie:** Exactly. And so I think that's going to be really interesting when you start to see people push the boundaries. They say a lot of great tech is always pioneered for the salacious, the black market — Silk Road-type stuff. So what does that look like in the AI era?

---

## Closing [01:01:30]

**Sam:** Well, you're the man. I appreciate your insight.

**Howie:** No, I enjoyed this. This was awesome.

**Sam:** It's fun because you have a really interesting perspective. You're a young guy, but you've been in the game for so long, and you have such breadth because of the size of your company. It's really cool to just see your thinking and how you're going to somewhat predict the future.

Dude, you're a badass. I appreciate you doing this.

**Howie:** Oh, thank you. Really enjoyed the conversation — happy to chat anytime, bud.

**Sam:** All right, that's it. That's the pod.
