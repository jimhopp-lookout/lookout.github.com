---
layout: post
title: The art of teaching a technical topic
author: achentir
tags:
- google
- talk
- android
---

Recently I gave a couple of talks at the Google Extended 
Day in Algiers (Algeria). [Google Extended](https://developers.google.com/events/io/io-extended) 
are events happening all over the world that Google sponsors and co-organizes with 
the local communities to allow the developers who couldn't make it to their annual event
[Google IO](https://developers.google.com/events/io/) to connect with other developers, 
learn about new trends/topics, try new hardwares and talk to Googlers. I was invited as a speaker 
to the event, in order to teach the local community how to develop an Android application.

I gave three talks: 

1. Android Overview - kind of a 101 session.

2. Android DevTools - introducing different tools used to: develop, debug, test and deploy
   your android application.

3. Advanced Android Development - live coding session with an emphasis on best practices 
   to follow while building a mobile app in general and an Android app in particular.

This was literally my first experience as a speaker and I found the task very 
challenging and fun.  In order to share that experience, I decided to come up with a 
list of good practices to consider when teaching any technical topic; here they are:

### 1. Set very clear expectations from the beginning
My talks had to be 45 mins long at most (including the Q/A sessions). That's a very short 
amount of time and no matter how focused your presentation is, it is hard to teach 
everything that your audience needs within that timespan. On the other hand, your audience 
comes to your talks hoping to learn everything they need to magically build their 
first MVP (Minimal Viable Product) for the Hackathon. 
So, if you don't want to disappoint them, it is important to set very clear expectations 
at the very beginning of your talk. Ultimately you want your audience to understand some 
fundamental notions and then take it from there to learn more by reading the online documentation. 
Your goal here, is to be the ice breaker between them and the technology you are presenting. 

### 2. Choose your content carefully
As time is limited you have to make sure that every instant of your presentation is worth 
an important information. Prior to your presentation, you have to triage the different things that 
you want to teach. A good process would be:

1. Brainstorm and write down all the notions you think should be taught.
2. Classify those notions within 3 categories: Mandatory/Important/Optional. 
3. Prepare your normal presentation with the mandatory and important topics first. 
4. Take your time explaining the topics by their order of importance.
5. Prepare some extra-slides with the optional notions in case you have extra-time or if they come up in the Q/A session.

### 3. Know your audience
In order to shape the right presentation, it is important to know who you are going to talk to.  Are they students? 
Are they professionals with a lot of experience? Are they technical at all? Obviously, your material as well as 
the vocabulary that you are going to use will vary depending on who your audience is.

### 4. Have a clear narrative
There is a notion in writing called: the [Tree-act structure](http://en.wikipedia.org/wiki/Three-act_structure). 
It is basically a model used in writing a modern storytelling which can be found in a wide range of 
domains: Drama, poetry, comics, novels, movies, video games, to name a few.

This notion basically states that to tell a good story we have to structure it in 3 acts:

1. Acte 1: The Setup, which is where all the major characters of the story are introduced.
2. Acte 2: The Confrontation, which is where all the story, its characters and conflict are all established.
3. Acte 3: The Resolution, which represents the final confrontation of your story or dénouement.

The nice thing about this structure is that it provides a clear path to bringing some knowledge to 
an audience. In the case of Android, we could imagine the 3 following acts:

1. Acte 1: Setting up the context, introducing the software architecture, explaining some fundamentals notions 
like the Android Runtime, what's Dalvik and how it works,  how does Android manage memory etc.  This is probably the most 
boring part of the talk but it's so important that you have to find an entertaining way for presenting it.

2. Acte 2: Use the notions taught during Acte 1 to explain how to build an Android application.

3. Acte 3: Do a demo.

### 5. Make sure that your knowledge is correct
There is nothing more embarrassing that teaching something wrong.  Now, I suppose that you have been 
given the responsibility to teach a large group of people about a topic because you clearly have some 
experience in it. But here is the thing, because you are experienced and because you are using this 
technology everyday at work you are probably making a lot of assumptions about how certain things work 
and those assumptions might be a little off. There is a great quote by Yogi Bhajan that says: 
*If you want to learn something, read about it. If you want to understand something, write about it. 
If you want to master something, teach it*.  Because your audience will drink your words as if it was water, 
you can't afford being too vague you have to own your topic and master it. For example if you want to pass on
some details on how Dalvik works, you could take an hour reading the official specification rather than trust 
whatever is written on Wikipedia.

### 6. Be prepared to fail
This is a no brainer and kind of related to any type of presentation that involves demoing something. 
To put it simply: Expect everything to fail! That includes: Internet connection will go down during the event,
your favorite IDE will crash, your project won't compile for some odd reasons and so on. When preparing for your 
presentations you have to prepare at least 1 backup plan for each failure scenario. Internet will go down? 
Then download everything that you need so that you can use it offline (example: save the result of 
an API call in JSON in a file). Afraid that your favorite IDE will freeze and crash many times during the demo? 
Then be ready to use Vi/Emacs/Sublime Text/ or whatever you love and be ready to use the command line to build 
and deploy your project.
Now, if you experience a demo fail during your presentation then instead of apologizing and running away try 
to discover what is going on live by thinking loudly and by showing them the tools that you use in order to 
track down bugs and fix them. Once you recovered from that failure, pass the details along to the audience, 
explain why it failed and how it is possible to avoid it in the future. This is how you should apologize, 
by making the failure useful.

### 7. Be funny & entertaining
You, as a teacher, have great power and that comes with great responsibility. As a matter of fact, the way you 
are going to teach is likely going to determine whether your audience will develop a passion for that topic or will 
develop an aversion for it. Everyone has some bad memories about that weird, boring, tyrannical teacher who made every 
instant of their classes, feel like a nightmare. It is possible that some students end up hating the subject just 
because of the teacher.  The moral of that, is that by making your presentation pleasant to watch and 
entertaining you are eventually going to create passion for whatever you are teaching. Passion is important, because 
this is the reason that will motivate your audience to spend their free time reading the official documentation or the 
specification and building interesting stuff.

### 8. Only teach topics that you are interested in
This point is slightly related to the previous one. If you want to entertain and interest your audience, you have to 
show some passion on the topic you are presenting. If you are bored, your talk will be boring and your audience will not follow.

### 9. Take advantage of the situation to find talent
When teaching a topic to a group of people, you'll likely encounter three 4 types of persons: 

1. Those who don't pay too much attention (wrong room may be?)
2. Those who pay attention but struggle at understanding the content.  
3. Those who understand everything.
4. Those who understand everything and who want to know even more details about each topic. By their questions, 
they sometimes force you to think hard and they might as well teach you something new.

This is the ideal situation for you to track down the persons who fit into the last category. Go talk to them after 
the sessions or during the party, find out who they are, where they work and hire them!

### 10. Determine success
It is important for you, to determine and measure the success of your interventions. That way you will know what to 
keep and what to change next time (and yes there will be a next time). In the case of teaching Android to beginners, 
I defined success by the following metrics:

1. The number of questions asked during Q/A.
2. The quality of the questions asked during Q/A.  Are they silly questions, like: 
What is the difference between an Activity and Intent again? Or are they more specific and clever? 
3. Whether the attendees knew how to start building their application during the Hackathon and whether they followed 
the platform guidelines.

By the way besides all of these points, you should also consider all the good practices that you need to follow to 
do a great presentation.

### Final words: why you should care about doing it well?
Teaching is hard, doing it well is even harder but if you are successful at it, the return on investment will be huge 
for your company:

1. Attendees will be happy and will associate their happiness to your products. 
2. These guys will ultimately be your best ambassadors, they will talk about you and your company to their friends and colleagues. 
3. You will attract talented engineers to your team. If you show passion and a certain level of mastery on the topic 
that you are presenting, it is likely that the talented engineers who attended your talks will develop interest in your 
company and will try to know more about it and eventually they will want to join you there!
4. If your presentation was good, it will be shared hundred or even thousands of times.  It will go viral!
5. The Q/A session might bring some interesting discussions from which you can learn new things.

And finally, if you can, take some time to network, socialize and talk to other developers or even non-technical participants. 
A simple discussion during an event like that can be the origin of your next big idea!

So go out, teach what you know and do it well!

\- [Amokrane Chentir](https://github.com/Amokrane/)
