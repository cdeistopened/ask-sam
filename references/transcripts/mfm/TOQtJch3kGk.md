---
title: "How To Build A $10M AI App In Literally 30 Seconds (this is insane)"
youtube_id: "TOQtJch3kGk"
url: "https://www.youtube.com/watch?v=TOQtJch3kGk"
date: 2026-01-21
speakers:
  - Shaan Puri (host)
  - Sam Parr (host)
  - Amjad Masad (guest, CEO of Replit)
topics:
  - Replit and AI-assisted coding
  - Amjad Masad's origin story
  - Coding in an internet cafe in Jordan
  - YC rejections and Rick-Rolling into YC
  - Magic School AI and fast-scaling AI companies
  - The era of the "idea guy" / citizen developer
  - Shopify for software analogy
  - Steve Jobs and the Pixar story
summary: >
  Amjad Masad, CEO of Replit, joins Sam and Shaan to share his journey from coding in an internet cafe in Jordan, through four YC rejections, to building a billion-dollar platform. The conversation covers how Replit's AI agent is enabling non-coders to build real software in minutes, the wild growth trajectories of AI-native companies like Magic School, and why the era of the idea guy has finally arrived.
status: polished
polished_by: claude-sonnet-4-6
word_count: 9800
---

## Opening Clip [00:00:00]

**Shaan:** This is the first AI agent thing that has been a mind-blowing moment for me — where I am not a programmer, I am not a coder, but I can now create software.

**Sam:** Well, that's insane.

**Shaan:** There are apps built on Replit's agent that otherwise would take probably $100,000 of developer time, and you can build it for $25 paid to Replit.

**Sam:** It's pretty wild how fast these companies are scaling. I don't think in the history of Silicon Valley we've seen anything like that — even in the Web 2.0 era.

**Shaan:** So what is a fast ramp for an AI company? What's impressive that broke the frame of how long things would take?

**Amjad:** I would say reaching $10 million in three to four months ARR.

**Sam:** Oh my God. That's wild.

**Sam:** Can I ask a blunt, crude question? How can I use your software to become a billionaire?

## Amjad's Origin Story: Jordan to Silicon Valley [00:01:30]

**Shaan:** Okay, so Amjad — you're today in a position that a lot of people want to be in. You're doing the Silicon Valley dream. You had this idea, you went through YC, you've raised hundreds of millions of dollars, you're valued at a billion-dollar valuation. That's today.

But the cool thing about your story is that didn't seem likely ten years ago. You went through YC, but you were rejected a bunch of times. You're in Silicon Valley now, but you started off coding in an internet cafe in Jordan. That's what's interesting to me.

We asked you beforehand — we said, what killer stories could you come on the podcast and tell? And you wrote this, so I'm going to read it word for word: "Rejected four times and Rick Rolling into YC, raising tons of money, and meeting amazing billionaires." Let's do the first part. Rejected four times and Rick Rolling into YC — can you tell that story?

**Amjad:** Yeah. So I left my job at Facebook in 2016. Replit had been a side project for a while, growing. I was working on it nights and weekends. It grew to a point where the server cost was meaningful, and I was like, okay, I guess I have to start a company around it.

So I went to my manager at Facebook and said, look, I have this side project — can we make it somehow a project at Facebook? We looked into it. I sent Zuck an email at the time, and he ignored me. So I was like, I guess I have to start a company.

I quit my job, applied to YC the first time. We did the form, the video, all of that. We didn't even get a call. Just got the rejection letter.

**Shaan:** How much money was that? Like $70K or something?

**Amjad:** Yeah, something like that.

**Shaan:** What was the original product?

**Amjad:** It was basically an editor and a console. You could type code, run it, switch languages. That's it.

**Sam:** By the way, have you ever used it? I was using it today before this. It's magical. You tweeted about what it's like — your doctor wanted you to track your sleep, so you uploaded the PDF he gave you into Replit and it made an application to track it.

**Amjad:** Yeah, it's pretty magical.

**Shaan:** Sam and I have both joked around — maybe five or six times — we've said we're going to learn to code this summer. It's like a New Year's resolution where you keep saying you're going to do it, you do 20% of it, and you give up. We bought the Udemy courses, Learn Python the Hard Way, and nothing ever stuck.

One of the biggest problems is nobody really talks about this: you think learning to code is like learning Spanish. But before you can even write a line of code, you have to download this program, then download all these packages, and you're not even to the part where you actually write code yet. Just setting up the environment is so confusing to a beginner. Replit solved all of that.

**Amjad:** And actually — correct me if I'm wrong — the reason I wanted to build this kind of online environment where everything's hosted was because when I was younger, living in Jordan, I used to go to an internet cafe to code. Every time I went, I had to set everything up from scratch, because it wasn't my home computer. That's why I felt the problem more deeply than a normal person would.

**Sam:** Yeah, Paul Graham talks about it all the time — the best startups are solving your own problem. And you felt it really deeply.

## Building Replit: The Technical Breakthrough [00:08:00]

**Amjad:** Basically, every time I wanted to do a little homework I had to spend an hour setting up the environment. And the web was moving so fast — we had Google Docs, Gmail, all these client-side JavaScript apps — and I'm like, okay, why can't I just type code into the browser and run it?

I started looking around and turns out nobody had solved this problem. There were some experiments, and it was almost like finding a $100 bill in Grand Central Station. Like, I found an idea nobody was paying attention to.

**Sam:** Is that crazy? Like, was there some technical challenge? Because it seems like an obvious thing.

**Amjad:** Two things. There's the technical challenge of making this all work in a browser — that was not obvious. And then second, the thing that made it unavoidable to me was the internet cafe situation. Anybody else learning to code at home in America might set up the environment once and have a little problem, but they're not running into it face-first every single day.

**Shaan:** That's Paul Graham's thing, right? You felt the problem x10 compared to what a normal person would feel.

**Amjad:** Exactly. So I started working on it. I discovered why it's hard — it's hard to run different languages in the browser. You can run JavaScript, but you can't run Python. So we started writing interpreters and compilers. Then in 2011, we had a breakthrough: we were the first to compile Python, Ruby, and a bunch of languages to JavaScript and run them straight in the browser. That went super viral on Hacker News.

**Sam:** Can you put that in context for a non-engineer? On a scale of one to Satoshi Nakamoto solving the double-spend problem — how hard of an invention was that?

**Shaan:** That's the nerdiest analogy you've ever come up with.

**Sam:** That's what I'm here for.

**Amjad:** It's definitely not on the order of the double-spend problem. It's more like pushing a huge rock up a very steep mountain. It took so much grit and obsession to hack the browser to run things it wasn't designed to run. I'd say it was solving hundreds of problems as opposed to one fundamental invention.

**Shaan:** You were doing this without Financial rewards, without fame, for how many years?

**Amjad:** 2009 was the original idea. 2011 was the breakthrough. And when it went viral on Hacker News, I remember Brendan Eich — the inventor of JavaScript, who was CTO at Mozilla — tweeted about it. I was like, wow, a kid from Jordan made this fundamental breakthrough in browser tech and I'm getting this recognition.

All that was also evidence for my O-1 visa to come to the States. I mean, I'm 36 now, and I've been working on this since I was 21. That's your whole adult life.

## YC Rejections and the Rick Roll Story [00:16:00]

**Amjad:** So I got the visa, went to work at Codecademy. They used the open-source version of Replit to create interactive courses. Suddenly the world opened up — job offers everywhere. We decided to go to New York.

Then I quit my Facebook job, put half my savings in Bitcoin, the other half into the company. Applied to YC the first time. Rejected. Just got the rejection letter.

**Shaan:** What were the other rejections?

**Amjad:** VCs mostly wouldn't talk to us. We'd get meetings and some of them were yawning. One guy actually fell asleep mid-pitch.

**Sam:** That happened to me once. A guy literally fell asleep. It was Friday at 4 p.m., warm in the office, and he just... yeah.

**Shaan:** What did they not see in you? Because looking back, you seem like you have the "it" factor.

**Amjad:** I think Silicon Valley is the most meritocratic place in the world, but it was also status-driven at the time. If you look at the typical YC success stories — Stanford dropouts, that kind of thing. My background wasn't interesting to them. I didn't have fancy colleges. And being a married couple was somehow seen as a disadvantage.

You didn't match the patterns. Not the Stanford pattern, not the co-founder relationship pattern, not the trending categories.

So we continued applying to YC every season. Our thesis developed. We started making some money — maybe $10K a month. The first person who bet on us was Roy Bahat from Bloomberg Beta. That meeting was so refreshing — he was a straight shooter, told me exactly what he thought. He gave us $500K on a $6 million valuation.

Then one day in December 2017 I wake up, there's a DM on my phone — it's Sam Altman. He says he runs YC and they're interested in what we're doing. I'm like, I know who you are.

He says, come to this address. It wasn't the YC address, which confused me. I go there and it's the OpenAI office in the Mission. He turns his computer around and shows me an email from Paul Graham saying this company is very important, you should reach out to them.

He says, okay, talk to Paul. I'll give you his email.

So I started this email relationship with Paul Graham, which was fascinating. He's a great writer. We talked about Replit, about the problems of setting up environments. Turns out he had been working on something similar himself after selling Viaweb. I would spend hours crafting those emails.

**Shaan:** Were you intimidated?

**Amjad:** Yes, but I was never nervous about meeting famous or established people. I think that helped. Because when you have a goal in a meeting, it puts you in a very different mindset than just fanboying.

Eventually Sam Altman says, the batch starts tomorrow — why don't you fill out an application? I'm like, you're making me fill it out again? I did it four times already. So I did a bare-bones application, and for the video I just pasted a YouTube link.

**Shaan:** What was the YouTube link?

**Amjad:** A Rick Roll.

**Sam:** Oh my God.

**Shaan:** And then the interview?

**Amjad:** We go the next day. Jared, Adora, Michael Seibel — the CEO at the time. I shake Michael's hand and his grip is a little too hard. I sit down, and the moment I sit down Michael looks at me and says, "Why did you Rick Roll us?"

I'm like, we applied several times, I thought this interview was just a formality...

He was very angry. Turns out they'd been getting heated inside, seeing this Rick Roll application.

**Sam:** Did you realize how you were coming across?

**Amjad:** I was nervous and immediately regretful. They must be thinking I'm just another entitled tech guy — they don't know I'm an immigrant from Jordan who scraped his way here. The reality of who I was and how I was coming across weren't connected at all.

So I go outside, tell my co-founder, let's call an Uber. We don't need YC. Just as the Uber is about to arrive, I get a call. It's Adora. She says: "You got in. Come back, the kickoff is starting."

I was stunned the whole day.

**Sam:** What a great story, dude.

## Building Replit at YC and Early Scale [00:26:00]

**Amjad:** The YC office is all orange — bright orange — and it has this cult-like environment. Sam Altman stands up and tells everyone: this is the hardest three months you're going to work. Tell your friends and family you're going away. My co-founder and I took that very seriously.

We transformed the product in three months. It went from a simple editor-output thing to a place where you can host real applications. We went from three people to five. I called my brother in Jordan — taught him programming when he was a kid — and he's still with us today. Called my friend from Codecademy, Moody, also still with us.

We were one of the hottest companies in YC at the time.

**Shaan:** Give us some brag-worthy stats.

**Amjad:** Replit was very easy to get started with. People would start using it in college or high school and continue using it for years — it was sticky for junior developers. It spread on its own through word of mouth. You can share a URL and suddenly you're in the same environment as someone else, collaborating.

COVID was really great for us because we were probably the only collaborative editor experience on the web. Growth went off the chart — servers going down. The marginal cost per user was still $1 to $5 a month, so it was hard to monetize at first because developers weren't used to paying for things.

AI was the thing that changed that. The productivity benefit of AI is obvious — people can see it saves them time, makes them better developers. And now we have 35 million signups, probably 2 to 3 million active users a month, 100,000 apps hosted on Replit.

## Sam's Live Demo of the Replit Agent [00:35:00]

**Shaan:** Sam, check this out. Have you tried the agent yet?

**Sam:** No.

**Shaan:** Okay. So yesterday I was supposed to be doing research for this episode and I just got sucked into messing around with Replit. Here's the exact prompt I typed:

"Build me an app that will text me every morning asking how I ate yesterday, let me answer via text message, and track the results on a monthly calendar grid. If texting doesn't work, you could also use WhatsApp or something else."

Then it goes — and this is like ChatGPT — "Absolutely, let me propose what we'll build." It just explains the project like a project manager. Says, I'm going to help you create a food tracking app through SMS messaging with calendar visualizations. Starts with SMS, can add WhatsApp as alternative. Prioritizes things, proposes a plan.

Then I click "Build the initial prototype" and it just starts auto-scrolling, writing code. I'm literally sitting back with popcorn.

It says, I'm going to use Twilio for the SMS — can you go to Twilio and give me your account and phone number? So I do that. And then it made the thing exactly how I wanted.

I got a little stuck on the Twilio verification step — Twilio has to verify your phone number, so I can't send messages yet. But you can see it trying to send me the message, it's just awaiting Twilio verification.

**Sam:** It's almost absolutely incredible and then kind of frustrating at some point where you have to fight through some walls.

**Amjad:** I think I tweeted something like: I want people to be able to build an app faster than they can Google the answer to a question.

**Sam:** That's exactly what happened. This is another one of those mind-blowing moments in my tech career. You know, I graduated in 2010 — the first time I took an Uber I was like, holy crap, that was amazing. ChatGPT was another one. This is another one. I am not a programmer, I am not a coder, but I can now create software.

Can I ask a blunt, crude question — how can I use your software to become a billionaire?

**Amjad:** How do you ask someone to take their clothes off on the first date...

**Sam:** That's basically what I'm asking, yeah.

## Magic School and AI App Growth [00:43:00]

**Sam:** Okay, you had some examples in what you sent over. Tell the Magic School story.

**Amjad:** Magic School is an AI application for educators — basically helping teachers use foundation models to do assignments, create lesson plans, do interactive AI experiences with students. The guy who created it was a teacher. He took time during COVID to learn to code, started using Replit, and him and one other person built the initial version entirely on Replit.

The revenue ramp was one of the craziest I've seen, especially for education. You know how they say education is the hardest thing to sell into — teachers are overworked, underpaid, no time to learn a new tool. But this was amazing.

What it does is: a teacher says, I teach fifth grade biology, I want a pop quiz about mitosis. It creates the lesson plan, the quiz, the student workbook. A teacher doesn't have to spend four hours a night creating materials anymore.

They launched in July 2023. Over four million educators are using it. Similar Web shows millions of monthly uniques. They raised about $20 million.

**Sam:** That's crazy. And you only made $20 a month from that company.

**Amjad:** Yeah, Replit has always had a problem with value capture. That's partly why VCs struggled with it for a long time. But with AI, we're working on ways to take a cut when people monetize apps on Replit via the agent. If we reach scale and people are paying not just the base $20 but incremental credits on top — I think we can capture more.

**Shaan:** Are there other companies like Magic School that we haven't heard of?

**Amjad:** There's a company called 11x. They create AI SDRs — AI sales development reps. Companies can have one AE running tens of AI SDRs. The revenue ramp on 11x was also crazy. I don't think in the history of Silicon Valley we've seen anything like what's happening with these AI companies — even in the Web 2.0 era.

**Sam:** What's a fast ramp for an AI company?

**Amjad:** I would say reaching $10 million in three to four months ARR.

**Shaan:** I invested in Jasper — one of the early ChatGPT-wrapper companies for marketing copy. Their graph — in 10 or 11 months they scaled to $50 million in annual recurring revenue. I had never seen anything remotely close to that. It broke my frame of what's possible.

## The GPT Wrapper Problem and Moats [00:50:00]

**Shaan:** Now there's the big question in the investor community right now — the moat question. A lot of these companies get labeled as "GPT wrappers," which is a condescending way of saying if you can build it in a month, so can everyone else. You'll compete on price, margins go down, ARR is great but Anthropic or OpenAI is capturing most of the value. Is that a valid concern?

**Amjad:** Totally a valid question. Moats develop over time through strategy and technical excellence. Some of these companies can go down pretty fast — there are examples of that right now. But if you build real technical depth — like Replit's runtime environment, deployment infrastructure, databases, integrations, end-to-end environment for making software — catching up takes years. Though technical advantage is also not a long-term moat by itself.

Strategic things — reaching scale, making switching costs high — that may be a way to have sustainable moats. But it's definitely still an open question.

**Sam:** You know what's crazy, Shaan? For the longest time, building a web app was just literally impossible if you didn't know how. Now, Amjad is making it so anyone can do it. And what I think is: guys like you and me who have an audience — why aren't we constantly launching companies using this? Our ability to get users, because we can just get on the mic and talk about it, is a competitive advantage. Being technical is still an advantage, but getting customers is now the hard part.

**Amjad:** So the playbook I'd use: go into some inefficient, familiar industry and build the AI app to automate some of the work there. You could do it a hundred times and one of them will take off.

**Sam:** It's the era of the idea guy. Our turn to shine. Because the key unlock is: do you understand a problem well enough to point this really powerful magic wand at it and make it more efficient?

## The Shopify for Software Analogy [00:55:00]

**Shaan:** I'll give you my personal epiphany. I invested in Replit mostly because I thought you were smart and I saw developer growth curves. But here's how I think about it now:

I think Replit is to software creation what Shopify was to creating online stores.

**Amjad:** That's it. Eyes just lit up.

**Shaan:** Here's my example. A few years ago I started an e-commerce brand, and we just crossed $50 million cumulative revenue. And I was telling a friend about it — he's not an entrepreneur — and he's like, wow, I'd love to learn how to make products and websites. And I was like, I don't know how to do any of that. I've never manufactured a product in my life. I've never built a website that's used by customers. But I was able to skip all that work by stacking Alibaba and Shopify.

Replit is going to do that for the software space. It used to be that the job was "software engineer." Now it's going to be "software creator." I can create software without being a programmer. That shift is huge.

There are maybe 30 million software engineers in the world. Now there are going to be 300 million people who can create software. If you've got the internet and a phone, you can build an app.

**Amjad:** Yeah. Even in our original seed deck back in 2015, there's this master plan: we build a platform, we grow it, and then AI is going to make the thing a lot more accessible. Our mission was first "make programming accessible," then we updated it to "create a billion programmers." The moment GPT-3 came out, I wrote a thread on Twitter about how AI agents will change how programmers work.

## Snakes, Employees, and the Singularity [01:03:00]

**Sam:** I saw this video on Twitter of a snake that got its head chopped off, floated around, and bit its own tail, and the body reacted. Your employees — are they thinking you're doing that to them? When you joke about not needing as many programmers, are they sitting there like, does that mean us?

**Amjad:** I've always wanted the company to be lean. For a long time we were 10 people. Now we're 70, which is still nothing. But here's the thing — citizen developers are going to go from zero to 10x. And existing software engineers are going to go from 10x to 100x. They're becoming more and more productive.

The moment we automate all of software engineering — that's when agents can rebuild themselves, and you get into this loop where each version builds the next version. That's the intelligence explosion, the singularity. I think it's coming — maybe 10 to 15 years away. That's when the world really radically changes.

## Amjad's Favorite Silicon Valley Stories [01:07:00]

**Sam:** Have you met anybody in the tech industry who blew you away? I saw a picture of you with Jensen — you've met Paul Graham, Sam Altman. What are your favorite inspiring or crazy stories?

**Amjad:** One curious story: when we were raising from a16z, Marc invited me to breakfast at his house at 10 a.m. I expected to talk about the business. We spent two to three hours talking about politics, the world, all these interesting topics. I felt like this guy is more than just a technologist — he's a philosopher.

What's interesting about a16z is that Marc and Ben are this duo of the philosopher and the executor. Ben wrote The Hard Thing About Hard Things — what it means to run a company, hire executives, scale. And Marc has these big ideas about the world.

When I met Sam Altman, he was on his computer as I was talking. I was like, yeah, we're fundraising, I went to talk to a16z, I'm a big fan of Marc. He typed into his computer: "Okay, I'll introduce you to Marc." And when you email Sam, he replies quickly with a few words. I saw how effective you can be. That's not naturally me — I value quietness, thinking about strategy — but seeing it inspired me.

**Sam:** You tweeted a story about Steve Jobs buying Pixar for $5 million, investing $50 million, operating at a loss for a decade, cutting personal checks to make payroll, and somehow turning it into a $7 billion exit. Why did you like that story?

**Amjad:** I think Steve Jobs is underrated in one important way. People think about him in terms of the flashy things — the iPhone, the keynotes. But the thing I like is when he was lost in the desert for 10 years.

He was fired from Apple, created two companies that were failing — NeXT Computing and Pixar. Just investing more and more of his own money. Probably was going to go broke. But he kept going for 10 years. How do you do that?

Pixar became hugely valuable. And NeXT — which people thought was just a failure — actually saved Apple. Apple needed a new operating system, tried to acquire companies, couldn't find a great OS. NeXT had one, and that became macOS. Objective-C, from NeXT's obsession with object-oriented programming, is deeply embedded in what Apple builds on today.

**Sam:** I thought NeXT was just a failure. I didn't realize it actually contributed.

**Amjad:** Not just an acqui-hire, no. Going the distance is an advantage for entrepreneurs. I love that story because it mirrors what I've tried to do.

## Closing [01:17:00]

**Sam:** Dude, I know we kept you half an hour over. I apologize, but this was amazing — one of my favorite episodes in a long time, and I'm not just saying that. You can check all the other episodes, I don't say that at the end.

Where should people follow you?

**Amjad:** Twitter is the best place. I'm @amasad on Twitter, and the Replit handle is there too — just @Replit. Thank you so much.

**Sam:** Of course. My pleasure.
