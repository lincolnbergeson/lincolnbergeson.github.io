---
layout: page
title: Preventing Collapse
permalink: /preventing-collapse/
---

Preventing the Collapse of Civilization
===

Speaker: Jonathaon Blow
Video URL: https://www.youtube.com/watch?v=pW-SOdj4Kkk

0:00 - 18:54: Introduction

Blow argues (along with Elon Musk) that technology's natural state is decline, not progress. Several examples of important, ground-breaking technologies from previous eras that are now lost: the Byzantine flamethrower, the Lycurgus Cup, the Pyramids. He also leans heavily on the US-Soviet space race as an example of what progress can look like - going from nothing to a man on the moon in 12 years. The point is to challenge the notion that only the late modern era is truly competent and that not all previous eras are ignorant barbarians.

It's a convincing argument but notable that of these prior inventions only the Byzantine flamethrower is genuinely lost. The rest of them we were pretty much able to figure out how they did it using modern scientific techniques. Blow cautions that those same techniques that fuel our progress today could eventually be lost, and in fact, if we aren't careful then they definitely will be lost.

"Generational transfer takes energy." True, and I notice this in my field today. Only a handful of people in the world (I estimate a few thousand?) understand how the Linux kernel works, and even fewer could implement it themselves if it were taken away. Yet we rely on Linux so heavily today. It explains why big companies that rely on it the most and that have the resources to do so (Facebook, Google) employ developers solely to work on the Linux kernel. The obvious solution to generational transfer is books, but only a fraction of human knowledge actually gets written down. Plus, a lot of books contain only time-sensitive information that would be useless to future generations, such as instruction manuals for outdated products, etc.

19:50: Blow attributes all software improvements to hardware.

21:36: Feels like he's sort of poo-pooing massive advances in machine learning as "a small piece of the program" and "really simple math". I disagree. To me (and many others) that piece of the software is total black magic.

22:15: He says that loading a bitmap onto a screen and clicking a button are massively more complex than a machine learning algorithm. By the number of jobs created by each function I think he is probably right - there are a great many more programmers who work on UI, graphics, and apps than there are programmers who work on machine learning. But I still feel like he's exaggerating to make a point here.

28:03: We are not surprised by software failing and having bugs all the time. This is actually true, once every three days or so hh_server (a language server I use for work) gets in a bad state and saving a Hack file in Vim causes the whole editor to freeze for 5 seconds. If I knew more about Vim and Vimscript in particular, I could dig in and figure out what the heck is going on, but at a surface level it's just broken. Blow walks through a million bugs in a bunch of different pieces of software. Maybe his life is worse because he uses Windows - the same stuff happens on Macs, sure, but less often in my experience. I'd be willing to be that most of these weird software bugs are due to supporting either a) legacy code, b) legacy platforms, or c) legacy behavior. Android apps are buggier than iOS apps, for example, because an Android phone can have any random piece of hardware attached to it, and iPhones are more or less homogenous. So our standards lowering is at least partly a function of our platforms broadening.

29:00: We don't use "five 9s" anymore as a metric for reliability. My first thought is, that can't be true, many places still do this. AWS S3 claims [11 9's of reliability](https://blog.cloudsecurityalliance.org/2010/05/24/amazon-aws-11-9s-of-reliability/). I tried to find others but actually Google and Netflix are [not as optimistic](https://greenm3.typepad.com/green_m3_blog/2011/01/google-amazon-and-netflix-comment-on-uptime-99999.html) about their reliability numbers. Interesting, he may have a point here.

29:36: I'm really starting to think his perception of software quality and reliability is deeply tainted by using primarily Windows. What he's saying has the ring of familiarity but I haven't had to reboot my Macbook Pro more than maybe once every year.

31:32: Software startups "corrupted" the words "tech company"? Really? Come on.

32:12: I really enjoy Gary Bernhardt's take on higher level languages in his satirical talk [The Birth & Death of JavaScript](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript). It's much more interesting and sophisticated than Blow's take, which is basically that higher level languages abstract too much from what's going on in the machine and are overall bad. Bernhardt on the other hand is totally honest about JavaScript's flaws, both in language and in ecosystem, but he recognizes the massive positive impact that it has had on the industry.

34:37: This part really grinds my gears. I was expecting to be annoyed by this after Blow's [recent tweet](https://twitter.com/Jonathan_Blow/status/1154483536088276992?s=20) but every time I think about it I get a little more upset. His argument is deeply and willfully ignorant. To be fair, Twitter is a pretty good example of a [dysfunctional web startup](https://www.vanityfair.com/news/2018/02/how-twitter-lost-the-internet-war). But Facebook isn't, Amazon isn't, Apple isn't, Google isn't. Think what you will of these companies, but there's a good reason they're collectively worth trillions of dollars. He's cherry picking examples here.

Plus, Blow of all people should be smart enough to realize that what he's measuring isn't "productivity". What he's measuring is really just "the changes in functionality that Blow happens to notice". Here's a small list of the changes he might be missing by relying on this metric:

- Increased uptime
- Expanding products into new countries
- Developing internal tools
- Building and improving infrastructure
- Launching experimental prototypes to small groups

By my estimation as a Facebook employee, those five things I listed account for at least 75% of engineering efforts across the company.

Plus... PLUS ... the example of Facebook irks me in particular because Facebook is an absurdly productive company. Think about Instagram, WhatsApp, Oculus, Messenger, Messenger for Kids, Marketplace, Workplace, Events, Groups, Charitable Donations, Watch, Live, Ads Manager, Business Manager, Portal, Open Compute, FNA... there's a hundred other projects I could name, and many many more that I can't. To say what Blow is saying is to argue that [$537,000,000,000 in shareholder value](https://www.google.com/search?tbm=fin&q=NASDAQ:+FB&stick=H4sIAAAAAAAAAONgecRoyi3w8sc9YSmdSWtOXmNU4-IKzsgvd80rySypFJLgYoOy-KR4uLj0c_UNiqosM0pyeBaxcvk5Brs4BlopuDkBAKarQhxHAAAA&biw=1680&bih=916#scso=_DrpNXcukBoaU0wK646_wDA6:0) is essentially misplaced (not to mention the hundreds of billions in other companies Blow criticizes besides FB).

Since Blow's point is that higher level languages are essentially the cause of this supposed productivity loss, I'll also add that Facebook a) writes all web code in an in-house high level language, b) maintains a custom, internal-only IDE based on Nuclide, c) develops a custom JavaScript type-checker, d) maintains a world-class front-end framework, and e) employs thousands of developers to work on developer infrastructure alone. This all falls under the category of "complex abstractions that increase developer productivity" and it pays off in a major way.

I could keep going on this rant but I think you get the idea.

36:17: Blow uses the example of Ken Thompson writing Unix in three weeks to prove his point. Look, I'll grant that Ken Thompson is a once-in-a-generation genius. But the Unix that Ken created would not be usable by modern standards. No internet, no web browser, the simplest possible text editor you can imagine, no games, no server technology ... it's really not an apples to apples comparison.

38:20: Decided to stop watching.
