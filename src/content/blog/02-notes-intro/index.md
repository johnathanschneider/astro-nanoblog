---
title: "The mystery at Clavius Base"
description: "Open the pod bay doors HAL"
date: "Nov 19 2026"
---

My first initiative is to research the field of digital handwritten notetaking. 

### Prologue

I am quite fond of writing my notes by hand - there is extensive literature documenting the delta of data density retained when learning orally, versus typewritten, versus handwritten, versus kinesthetically. In order to learn the brain needs to engage as many different functions as possible. Oral engagement activates only the ears, and the mouth. Typewritten engages the fingers but does so in a rather repetitive fashion and does so in a rather slow fashion - the mind can often think faster than one can type, so this is equivalent to riding a bike on training wheels. Unless you have a highly structured digital system, like a LaTeX framework you use to help sort your data into buckets, it is recommended to handwrite notes if possible. 

Kinesthetics obviously begin to engage more suborgans in the brain, requiring spatial cognition, extreme fine motor control. However, there's only so much kinesthetic demonstration you can get out of textbooks, class lectures, and highly theoretical applications like that of algorithmic analysis. For that you are probably best suited to engaging in lab software, like a MatLab circuit simulation demonstrating the response curves in an RLC circuit.

### Examination

Of course, when you begin to examine the options for handwritten notetaking, I find the resources to be quite limiting. Physical paper-drafted handwritten notes of course are so widely used it's almost not worth discussing the pro's and con's, in the digital era. Paper quality, journal binding quality, storage mechanisms, transferrability (or lack thereof), and the limited expressive space of a physical paper (unable to scale to the mind's size of a thought) - it is reliable but falls quite short of *perfection*. 

So, of course, the question turns to digital - as mentioned before, typewritten notes require too great a structure. Pardon me, but the sheer principle of having to know a LaTeX or Markdown file structure just to take notes is absurd. A third grader can reliably take notes and learn expediently - and I assure you a third grader does not know LaTeX or Markdown. The goal here should be to build a system that accommodates and intends to amplify the underlying intellectual wanderlust of a child - how flexible they are at learning for example new languages and new concepts -  but scaled to accommodate the diversity and intensity more mature subjects require.

Thus, we must examine the list of options for a digital handwritten notetaking application. I find virtually all of them insufficient as well. Let us query a few

- OneNote: Proprietary, and exclusive to Windows and Apple at that. Immediately disqualifying.
- Xournal++: Terrible UI (sorry) and exclusive to desktop operating systems. Also, it doesn't really scale or do the infinite canvas thing well. Disqualifying
- Saber: This one is available on all platforms. We're getting somewhere! However, it doesn't really do the infinite canvas thing. It feels quite limited.
- Butterfly: Now we're *really* getting somewhere. It has an infinite canvas mode, viewtracking, ruled lines, and is crossplatform. Unfortunately however, I found the performance of the rendering engine lackluster, and the UI poorly designed.
- Rnote: Excels at the infinite canvas mode, and has extremely snappy performance. Unfortunately, the UI is written in GTK and effectively no mobile OS binding exists. 

It goes without saying that there are many more proprietary options, typically exclusive to one use case or proprietary. I find those disqualifying for the obvious fact that the sheer concept of notetaking is not proprietary. I should have the capacity to take my notes anywhere on any platform.

### Research

I come to the conclusion that I find the space quite limited - and I must begin to research what makes a good note taking app, and how to improve upon the space.

The first and most immediate aspect of this topic is that there is no concrete protocol for taking notes. Each of the above referenced applications uses their own file format. They offer file conversions for eachother, but none follow a particular standard. I think this is rubbish; notes are ideas, intellectual products. They are not proprietary to a file format or the conversion function of a digital application, even if said application and file format are open source. A note file should follow a standardized rich protocol that governs all clients, such that users who prefer single page, versus canvas mode, can use a file smaller or larger, at their pleasure. The client app should be decoupled from the note, if you will. My research into the protocol will follow.