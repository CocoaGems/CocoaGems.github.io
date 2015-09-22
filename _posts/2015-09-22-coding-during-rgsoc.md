---
layout: post
title:  "Coding During RGSoC"
date: 2015-09-22
author: karla_sandoval
---

<p class ="intro"><span class="dropcap"></span>Ok So it is September in San Francisco and not quite Summer anymore. Which means that as of today we (RGSoC) teams have 8 days left until the end of the program. Here is a list of my shiniest and most loved newly acquired skills, revelations and commands:</p>

How to work on an Open Source Project without a read.me. The issue  I worked on this Summer <a href=”https://github.com/CocoaPods/Cork”>Cork</a>  did not contain a read.me. So, I used git-blame to track down the first person to contribute to the file. Git blame is the best because you can track each change that has been made to files  you are working on.

How to ask questions when I felt uncomfortable or when I felt like I should know something.
So the new technique goes something like this..open up Slack pick a coach and type out the question. Composing a question in a way that someone else can understand requires that you establish what kind of trouble you are having and it gets gets you many steps closer to that answer you are looking for, many times this technique worked so well that I was able to answer my own questions just by putting my question in the Slack UI and thinking about it without hitting send. In other words- it is difficult to ask for help and for others online to provide it if you can’t identify what you’re having trouble with. And What I found is that I didn’t alway know what my problems was, but by writing it down I was better able to understand what the challenge was.

How to automate your learning process: learn to schedule meetings with mentors, coaches, colleagues and managers naturally by scheduling one each and every single time after every session. The best resource available for learning aside of the web are definitely our coaches and mentors. I learned to schedule as many sessions with them. Some were in person, some were over screen hero and some of the meetings we scheduled were also with other RGSoC participating teams and or Github Summer of Code students in particular Mark Tareshawty. Google Calendar became my best friend. Adding meetup events that I wanted to attend and also scheduling a well thought out plan for the day made it so that transitioning from one activity to the next happened with as least cognitive exertion as necessary.

Some of the most interesting frameworks concepts my mentors and coaches introduced me to include writing tests in RSPeC, writing unit tests and how to reduce issues into sub-issues by creating issues on Github and or by using Trello. My mentors in particular Kyle Fuller and Samuel Giddins are especially to thank for- for walking me through RSPeC, Rubocop and rake.
(Testing is definitely a skill to develop since there are ways to write tests that pass but don’t necessarily check what you really want to proof).
How to create CHANGELOGS, extract code and determine what to keep and what to get rid of. Getting rid of code can feel really scary at times and it feels so wrong. But sometimes you just have to do it and in general less is more.


The best learning experience gained from working on RGSoC this Summer:
Learning how to learn.

Working on an Open Source project has taught me to reach out for help in places I would not have considered previously. Asking for help feels different now and hopefully the way I help others will also be more effective now. I look forward to being able to answer questions on Stack Overflow and questions on the Girl Develop It Channel as well as on Quora and Stack Exchange. Open Source means working with other people, collaboration and sharing. During Rails Girls Summer of Code we had many opportunities to ask many questions. I used the four Slack channels that we had when I got stuck or could no longer work on something on my own. The channels that we were a part of include the Rails Girls Summer of Code, the CocoaPods channel, the Github Summer of Code channel as well as the iOS channel. On occasion, when both coaches and or mentors were busy i  reached out to other students from the Github channel and to other CocoaPods mentors I had not met yet. Participating in this program has made me aware of  the multitude of resources and has improved my ability to ask for help.

Here is a list of the wonderful people that helped my team mate Emma and I on our RGSoC journey and on our projects and issues:

Mentors: Samuel Giddins, Boris Bugling, Orta Therox, Kyle Fuller
Coaches: Jake Boxer, Jesse Toth, Ross Mc Farland, Rob Rix, Rachel Meyers
A big thank you to all of you! Learning about software development, fundamentals, Git, algorithms,how to write tests, and agile has been a a great experience with you.


Here is the Project I worked on in a nutshell: CocoaPods Issue https://github.com/CocoaPods/CocoaPods/issues/3398  


Created a new Gem named Cork.rb by extracting CLAide/lib/command/banner.rb

CLAide becomes Cork minus the CocoaPod specific code.
 2.) Extracted Pod::User Interface Module

 3.) Where did TextWrapper.rb come from ??


To be a good programmer you have to be good at snooping, perusing, reading between the lines  and by that I mean doing bits of detective work every now and then. Digging deep and knowing how to search is a plus. When documentation is not present or poorly written you have to be able to learn how to piece and retrieve background information to either a method, code, a key word, a repo number or a git-blame that can help you better understand  how the code works, who worked on it before you and what they did.The summer was a full on learning experience - glad that we kept a RGSoC Team Apps journal- this summer has to be the best well spent three months of my life and best use of time.

Favorite Memories:

![Image of Githubs Pull Request UI](/assets/img/PullRequestCommit.PNG)

Releasing our first gem <a href="https://github.com/Karla-Isabel-Sandoval/cocoapods-labelCocoaPods-label">CocoaPods-label</a> with our coach Boris Buegling was the best. We worked on that project for quite a long time, it was a great experience to work with Boris since he is a CocoaPods and Ruby conoisseur.
Boris was very honest when he didn't know or remember something specific. While working on CocoaPods-label he would share his screen while Googling. This gave me a better idea of how to perform better searches but most importantly it reassured me that no-one knows everything. Regardless of how seasoned, experienced or smart anyone is-- developers use documentation frequently  to either double check or for reference. Making my first pull request and learning not to commit to Master was also a great milestone. And in case you are not a developer reading this--always, for the most part do the alternative- create a new branch and then start a pull request as seen below:


![Picture taken in Nashville, Tennessee on June 24, 2015 of Summer of Code Students](/assets/img/codeconf.JPG) From left to right: Emma Koszinowski, Karla Sandoval,
Chih-Wei Chang, Mark Tareshawty.
