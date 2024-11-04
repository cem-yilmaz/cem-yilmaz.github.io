---
layout: post
title: How I use Obsidian to study
date: 2024-11-03
description: A timeline of my relationship with the excellent Markdown editor Obsidian, and how my note-taking workflow has evolved over uni.
tags:
  - uni
categories: 
thumbnail: 
featured: true
toc:
  sidebar: left
---
August 12th, 2023. This was the day I stumbled upon [this video](https://www.youtube.com/watch?v=DbsAQSIKQXk) by *No Boilerplate* about a program called **[Obsidian](https://obsidian.md/)** that I'd never heard of before. 

Obsidian is a free Markdown editor with an emphasis on linking notes together to form connections. It's garnered quite a lot of popularity in the past year or so especially amongst tech-savvy users, which I attribute to it's "almost open-source" nature.

Obsidian *isn't* open-source. It's free for personal use (companies must pay for the commercial license, although I'm unsure if this is only enforced to the same standard that *WinRAR* would do so), but offers such a [rich plugin system](https://docs.obsidian.md/Home) that you could probably add any feature that you want to.

I'm not about to tutorialise Obsidian here as there are plenty of video tutorials on YouTube that do a much better job than I could ever hope to achieve. This post is intended to describe *how I currently use Obsidian to take notes in university*, so hopefully people - potentially students - willing to take the plunge with Obisidian can take the advice I wish I'd known when I started. 

Of course, following a retrospective[^skip] look into how I've taken notes during my time here at uni.
# A brief history of note-taking
## First Year
I started university with a spring in my step and a notebook in my pocket. No, seriously[^rb].

Look, I'd taken a year out due to Covid in September 2020, and aside from working an unmotivating job, I'd only been keeping mentally stimulated by completing the Codeacademy full-stack web developer course that I said I didn't have the time for earlier. **Translation**: I hadn't needed to take notes on a educational course in ages.

I bought a laptop for university but still, during my first few weeks, handwrote every single note for every single lecture. In the same notebook. With no external labels or organisational system at all. Writing all this down and looking at it now, it's a miracle I academically did well this semester at all.
## OneNote
While I can't remember exactly how I found OneNote, it was probably through a mix of two factors:

- My university uses Microsoft's Office suite of products and OneNote has been used to share files in the past, particularly in my first and second years
- I kept seeing students whip out iPads and get all the benefits of handwritten notes, while being able to seamlessly combine the official course materials

I simply made one notebook, and different tabs (or whatever they call them) for each course. I'd make a note for each lecture, paste the slides in, and annotate them - just like the iPad students!

I then found it rather difficult to keep up with the lectures in mathematical-notation-heavy lectures, and so got a drawing tablet, which OneNote provided excellent support for. Finally, I could not only handwrite whatever I wanted, but duplicate it, move it around, and erase on the fly!

The honeymoon didn't last long. When revising, it took me ages to find the relevant topics. Additionally, inserting extra images in was a faff. Most of the problem, however, originated from me: many of my notes consisted solely of the lecture slides with little more than a few extra sentences sprinkled in. I was hardly engaging with my lectures; honestly, in the case of simple "`Insert PDF`" jobs, I wouldn't say I engaged with them at all. Something needed to change
## Disclaimer
It must be said that I am **not** criticising all the methods mentioned in this post. I know several people who still religiously use OneNote throughout their undergrad. I've seen final years using Microsoft Word for their lecture notes. **The best note-taking system is ultimately the one which works for you, and I'm not about to convince you otherwise**.  
## Briefly, Notion
I tried Notion for a bit. During the following summer, I experimented with changing my note-taking workflow in anticipation for the uni year ahead. 

I'm not about to sit here and pretend Notion is bad, because that would be a lie. It's a key tool for countless people who effectively use it for tasks beyond the complexity of mine.

I just didn't like it.

I think Notion subscribes too strongly to a "style-over-substance" mantra. You've got built in support for UnSplash banner photos on notes, but you can't cleanly export the notes as Markdown. You can add emoji icons to notes, but you must choose from one of 8 pre-defined hex codes if you want a block colour banner. You've also got constant pop-ups for features as you type, sluggish performance, and for all the praise it's databases get, you can't simply insert a link to a note as the value to a cell![^workaround]
# Obsidian
It was at this point I found Obsidian, and everything just worked. I had an app that kept my notes in plain text, local on my computer. I had an app with no thrills, tiling panes, extensions that let me add functionality from an [automated table of contents](https://github.com/johansatge/obsidian-automatic-table-of-contents) to a full [web browser](https://github.com/PKM-er/Obsidian-Surfing) within the app, or a complete re-write of the [PDF annotation](https://github.com/RyotaUshio/obsidian-pdf-plus) system.[^graph]
## What I wouldn't reccomend doing
### Bloat
It's very easy to get into an Obsidian rabbit hole in YouTube finding out what it *can* do. Due to the plugin system, Obsidian can be set up for tabletop RPGs, work, personal journaling, [Zettelkasten-ing](https://zettelkasten.de/overview/), and much more.

**It's entirely possible to install all the tools for this all at once. Don't do this**. I originally had Obsidian setup for personal journaling, a calendar/reminder/todo system, habit tracking, university, and gym routine all at one. 

Remember - Obsidian is a *markdown editor*. You are, ultimately, *just editing markdown files*. There's a common mantra in the Obsidian community to turn it into a "second brain" due to the fact you can enable all of this. That will genuinely work for some people; for me, in [the words of By Default](https://www.youtube.com/watch?v=XRpHIa-2XCE),

 > I just need to turn my text files, into slightly more organised text files.

I'll just say Obsidian was a much more productive app for me once I ditched the calendar etc, and used it solely to explore topics for uni.
### (Optional) Ignoring linking
This one's optional because I got by pretty well for quite some time under-utilising linking. I used to simply open a note for each lecture, and write down the stuff for that lecture. When I tried to link to topics in other lectures, I'd do so by referring to the heading/block of text it was located in.

## What I *would* reccomend doing
For each course, make a folder. You can optionally add subfolders for each week, but it's not necessary.

For each lecture, reading etc, open up a new note. This note is going to serve as a launchpad for your ideas. Type your high level ideas here. Whenever a new topic[^topic] is brought up, e.g. *Gradient Descent*, you would type (in your note) 

 > `![[Gradient Descent]]` 
 
The double square brackets make it so Obsidian recognises this as a note link, and the `!` means it will be *embedded* in the note.

Click into that note to create it, and start writing. You can embed a note in this note, or if a new topic arises jump back to the old one.

Whatever you do, **keep the title of the note atomic** - don't call it something like `Lecture 5 - Gradient Descent`. This is so you can link to it in other notes: for example, in a note titled `Neural Networks`, I could say

 > We then perform `[[Gradient Descent]]` on the weights
 
and when I'm looking back on that note, I can just hover over the link to see it's content.


This process can be quite intensive, so when starting out you may want to use my previously noted no-linking method to get Obsidian's more basic benefits. However, I highly suggest doing this when possible. A few more tips I wish I knew about:
- Obsidian has built-in $$ \LaTeX $$ support, which can be supercharged with the [Quick Latex](https://github.com/joeyuping/quick_latex_obsidian) plugin, allowing for custom macros which I usually regularly
- iPad note-takers rejoice! The [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin) plugin has excellent drawing tablet support. It has many other features for creating diagrams, but I literally only use this for drawings
- The built-in [templates](https://help.obsidian.md/Plugins/Templates) function is good enough for most people. Other more advanced templating extensions are available.
- Obsidian offer a paid syncing service. I pay for this (mainly as a way to say thanks but also because none of the other options I'm about to mention would work on my phone), but because Obsidian is just an editor for markdown files, it's easy to use a free [third party service](https://help.obsidian.md/Obsidian+Sync/Sync+limitations#Can+I+use+a+third-party+sync+with+Obsidian+Sync%3F) instead. I used the [Obsidian Git](https://github.com/Vinzent03/obsidian-git) plugin for this for quite some time, and it worked quite well - the only reason I switched was because it was a right arse to set up on mobile!


This is my current note-taking workflow with Obsidian and I highly recommend it to a specific kind of nerd.


---


[^skip]: The contents page is just to the left if you don't fancy all of that. The section "**What I *would* reccomend doing**" contains the crux of this article.
[^rb]: This section mainly exists as the "rock bottom" of note-taking, if I'm being honest.
[^workaround]: You *can*, technically. You can insert a type of page, which I called the same name as the note I intended to link to, and on that page you can add a text body which contains a link to the note. If this was confusing to read, then imagine the UX behind figuring it out!
[^graph]: "*But what about [the graph](https://help.obsidian.md/Plugins/Graph+view)?*" I hear seasoned Obsidian users cry out. I like the graph. It's cool. I don't find it useful for productivity (hence it's absence here) but I do sometimes open it if I'm bored.
[^topic]: It's up to you what constitutes a small factoid and what needs to be a topic/idea. I usually think "*How likely am I to refer to specifically this in the future?*"