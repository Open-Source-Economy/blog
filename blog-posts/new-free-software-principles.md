Time to Upgrade Stallman’s Outdated Free Software Principles
==============
***Version 0.0.1***

Is it exaggerated to say that for many engineers, Richard Stallman is nothing short of legendary? Perhaps not. Stallman, a titan in the software world, has etched an indelible mark on our industry. His unwavering commitment to the free software movement isn't just admirable; it's transformative.

However, as revered as these principles are, they were conceived in the 1980s—a different technological era. Today, they call for a refresh, an update that aligns with our rapidly evolving digital landscape. To honor Stallman's vision, it's time we adapt these principles to the realities of our modern world.

Before diving in, let's remember: this article is merely a starting point. It's an open invitation to the community. Your insights, debates, and proposed amendments are not just welcome but essential. Feel free to comment, discuss, and suggest modifications on our GitHub.

Let’s delve in! To start, what are Stallman's four essential freedoms?

--- 

# Stallman’s Four Essential Freedoms

0. Freedom to run the program.
1. Freedom to study and change the program in source code form.
2. Freedom to redistribute exact copies
3. Freedom to distribute modified versions

![fourfreedoms-640px.png](..%2Fassets%2Fnew-free-software-principles%2Ffourfreedoms-640px.png)
*https://systemreboot.net/post/what-is-free-software*

--- 

# The YouTube Problem

Now, let's take a contemporary example that is a pivotal piece of software in our lives: a social media platform. For the purpose of this discourse, we’ll use YouTube, a global platform that is widely used, as our example. However, the insights and concerns addressed here can totally be applied to TikTok, Facebook, Instagram, and more.

As Stallman says: 
[“With every program, there are 2 possibilities: either the user controls the problem, or the program controls the user”.](https://www.youtube.com/watch?v=n9YDz-Iwgyw&t=420s)

In the case of YouTube, their stance in this dichotomy, unbeknownst to many, is that the program controls the user.
To understand why, let's start with the basics: data handling. We know that YouTube collects our data, but we can not verify, control, or decide what they do with them.

The issue with YouTube, however, runs deeper. YouTube is a media platform - and media is often regarded as the fourth power (or [fourth estate](https://en.wikipedia.org/wiki/Fourth_Estate)) of democracy. But in the words of Winston Churchill, `“With great power comes great responsibility”.` YouTube has this immense ability to determine the fate of content to thrive or fail using algorithmic determiners.

Its recommendation algorithm doesn't just suggest videos; it subtly, yet significantly influences our political views. Moreover, the platform's approach to content moderation, largely mirroring North American cultural norms, raises questions. Isn't this somewhat akin to modern censorship?


---

# Applying Free Software Principles to YouTube

What if Google, the parent company of YouTube, recognizes the democratic challenges presented by YouTube, and decides to fully adopt Stallman’s principles of free software? Would YouTube continue to be in control like it is today? Could the issues we've discussed find a resolution?

## Freedom 0: to Run the Program

The freedom to run the program is based on the ability to run the program's code on a personal computer. This, however, encounters a significant hurdle: the immense data requirements for streaming videos. Even for those not versed in computer science, it's evident that YouTube's scale exceeds the capacity of a single machine. To run YouTube, we'd require a distributed architecture—a knowledge domain mastered by only a select few.

In essence, this freedom remains accessible to only a privileged few. Can we truly call it freedom when it's beyond the reach of most individuals? I would argue that it no longer embodies the essence of freedom.

## Freedom 1: to Study and Change the Source Code

Consider the second freedom—to study and modify YouTube's source code.

While it might be plausible to embark on studying YouTube's code. It's imperative to grasp the complexity of this codebase, particularly the intricate and critical algorithmic components. Even for experienced developers with ample engineering experience and intelligence, the task of modifying YouTube's source code to align the standards of democracy would likely span a lifetime - and probably even more!

So, the question, as with the first, arises: Can we still speak about freedom when it is nearly impossible to access?

## Freedom 2: to Redistribute Exact Copies

Let's shift our focus to the third freedom. It's important to note that YouTube's code is merely one piece of the puzzle; it's the data that truly breathes life into it. And redistributing the code without the videos just makes no sense…Even if we could redistribute exact copies of the code and the data, that would still make no sense, but let’s dive deeper into this in the fourth freedom below.

## Freedom 3: to Distribute Modified Versions 

This aspect carries significant weight. The concern with YouTube lies in its impact on democracy, affecting not several individuals but everyone. In order to make YouTube more democratic, convincing others to embrace a modified version becomes imperative.

However, consider the challenge: many have attempted to create YouTube alternatives, only to confront the formidable "network effect." With everyone entrenched on YouTube, including creators who derive their livelihood from it, persuading users to switch platforms becomes a monumental business endeavor. Without substantial backing from venture capital, it appears nearly insurmountable for creators.

For consumers, on the other hand, there are several "alternative frontends" (e.g. [Piped](https://docs.piped.video/) and [Invidious](https://invidious.io/)) that mirror their video data from YouTube, so the same videos can be consumed without the need to accessing YouTube directly. 

---

# Pioneering New Principles for True Freedom

Given the limitations of the original four freedoms in today's landscape, it's time to explore innovative ways to extend and adapt Stallman's vision. What principles must emerge to empower individuals to experience true freedom when using YouTube? What new frontiers of free software principles can navigate the complexities of the contemporary digital landscape?

## The Freedom 0: to Study and Change the Source Code, A Cornerstone

The foundational principle of freedom to study and potentially change the program in its source code form remains indispensable. This principle embodies transparency and the ability to envision a better future through code.

However, this principle presents a reality check: the sheer volume of knowledge and data on our planet far exceeds a single human lifetime. This principle essentially asserts that to understand what a program does, one need only inspect its code. But who among us has the time and energy to scrutinize every program we use? The far and few! Even software engineers who dedicate significant portions of their lives to the study and modifications of programs find this task insurmountable.

The ability to study and modify a program requires a certain level of knowledge and expertise that many experts do not obtain. It's essential to ensure that individuals who aren't software engineers or lack equivalent knowledge can still exercise the same freedom. They should have a voice in shaping the software's code

Lastly, when we encounter programs with their strength rooted in the network effect, like for YouTube, those aspiring to modify them for a better world should not find themselves in an uphill battle.

That is why we are proposing new essentials freedom.

## The Freedom 1: Clear and Up-To-Date Documentation

One of the new freedoms in software is the right to clear, comprehensive, and up-to-date documentation.  This principle recognizes that time is a precious commodity, and to maximize the engagement of a diverse audience with a program, the path to understanding must be made as straightforward as possible.

This principle acknowledges the subjective nature of what constitutes `clarity` and `comprehensiveness` in documentation. What may be crystal clear to one person might still be cryptic to another. As such, software developers and communities should adopt a `best effort` approach.

This best-effort approach is about recognizing the fluidity and diversity of the software user community. When a developer encounters an unfamiliar code base, a brief guide that explains the core architecture and points to the starting section of the code.  For example `An event-sourcing architecture, implemented with Akka. Starting at the gRPC class Service.scala` can be already immensely helpful.

## The Freedom 2: Community Control

With this principle, we are beginning to diverge significantly from Stallman's vision. Stallman primarily focused on code and what it could achieve. However, as we've seen with examples like YouTube, merely discussing code is insufficient because it excludes a vast majority of users of that code. The problem we encounter with YouTube is a collective one.

If we intend to ensure that every user is not controlled by YouTube, the entire YouTube platform should respect the freedom of all its users. This marks the commencement of a new era in the free software movement. So, how can we maximize the freedom of the YouTube community, encompassing viewers, YouTube creators, employees, customers, and so on? We're talking about millions of people here, and the most effective approach we've discovered thus far is a democratic system.

YouTube should be controlled by the community. This represents our third freedom. This concept raises numerous questions, such as what exactly is a democratic system? Depending on where you are in the world, democracy might seem like a fantastic idea or something that doesn't work at all. The effectiveness of a democratic system is an ongoing debate. We need to draw inspiration from the functioning democratic systems worldwide. The political system of Switzerland is a prime example of being one of the best models for this to date.

If you would like to learn more about this topic or enter the discussion, [join our community](https://www.open-source-economy.com/subscribe-to-governance-newsletter)!

## The Freedom 3: Decentralized Competitive Business Model

Noble intentions alone will not be enough. If YouTube begins to respect the freedom of its users but starts losing income as a result, it may become less competitive and gradually be replaced by another platform that may not prioritize user freedom. People may shift to this new platform, and the fight for freedom could be lost.

To challenge and compete with this proprietary model, one must generate comparable revenues and attract similar levels of investment. If you follow this logic, revenue is also an integral part of the product. Therefore, revenues should also be under community control.

So, the fourth principle is that free software should possess a competitive business model with decentralized governance.

---

# Conclusion

This is our first draft - we invite you to participate and propose changes to this proposal. We fully acknowledge that it takes a village to find viable solutions that work for the majority. 


