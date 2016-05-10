---
layout: post
title:  "Learn All The Things"
date:   2016-05-10
categories: goals
---

A common question in this tech universe is "What do you want to learn?" -- and that's awesome, because I love learning, especially if it's something I'm interested in. My typical problem though is I'm interested in _a lot_ of areas and I want to learn as much as I can get my hands on. Because of information overload, it can be difficult to focus. I hope in writing my interests down, I can work through them. 

I don't expect to work through this entire list any time soon. Of course, this list is not exhaustive and I realize in learning some of these things, interest will likely spark in other areas as well.

## The Past
Most of my previous experience has revolved around the front-end. I've been interested in code and what it can do since I first discovered view source back in single digits. I remember when CSS and div layers started to become _the thing to use_ as we phased out frames and table layouts. I was content searching line-by-line for comma splice errors (I hadn't discovered the wonders of IDEs with line numbers yet). I liked playing with PHP and loved integrating it with b2 to make various blogs about whatever I was interested in (or share my teenage angst). When Wordpress became the new blogging software and b2 was no longer supported, I lost interest.

I thought I wanted to do computer science in college but I was so overwhelmed by the introductory Java course. Besides altering some JavaScript and PHP code here and there, my only programming experience had been in a high school Visual Basic class. It was intimidating being one of the few not-dudes in an extremely large class (hundreds!), especially when most of the class clearly already had Java experience. I didn't feel comfortable asking for help. I also worried that a computer science career would just put me in some corporate basement in a lonely cubicle where I never got to interact with humans. (I'm so glad I was wrong about that!)

So I took a little break from most things computers (with the large exception of video games, of course) to persue another field (Speech-Language Pathology). But that didn't work out. And so I fell back on the only other field I've ever felt like I belonged to. 

In my free time, I played around with web servers and became aquainted with nginx and configuring it that way. I dabbled in beginner tutorials for Python and Ruby and got my feet (okay toes) wet by installing [Ghost](https://ghost.org/) on my own--I had some great tutorials on how to do it but unfortunately they have been misplaced. 

I got my first job as a web developer for a local non-profit arts organization, the [Pittsburgh Cultural Trust](http://trustarts.org/). They hired me for Rails and JavaScript development, willing to have me learn on the job which was an awesome opportunity. I worked on a very small team with just one senior developer and our project manager. We were not very test driven (in fact, I was given the impression they were a waste of time at first), DevOps was not at all a philosophy we utilized, but it was still great exposure to Ruby and programming. 

The three biggest things I worked on were:
* A very large Rails application that essentially was a ticketing program for [Pittsburgh's Cultural District](https://culturaldistrict.org) which integrated tightly with [Tessitura](http://www.tessituranetwork.com/)'s API (which, at the time, was transitioning from SOAP to REST so I got exposed to both of those API types) and Radiant CMS. I mostly worked on bug fixes and adding small features.
* Forking and updating the no-longer-supported-but-we-still-needed-it Radiant CMS (which ran on Rails 2 and Prototype) to a Rails 3/jQuery variant we called [TrustyCMS](https://github.com/pgharts/trusty-cms). This was my first open source project and my first experience with [Travis CI](https://travis-ci.org).
* Building my [first Rails 4 application](https://github.com/sinthetix/era) (outside of tutorials) that parses and organizes Tessitura API errors. Tessitura sent the errors via email, which was difficult to track in any meaningful way, hence the creation of the application. It updated in near-real-time using the [Sync gem](https://github.com/chrismccord/render_sync).

Shortly after my contract ended with the Pittsburgh Cultural Trust, I was hired by [Travis CI](https://travis-ci.com) as a remote, customer support engineer. This really excited me at first because Travis CI supports so many different languages and projects to it was good exposure to a lot of different areas. Travis has a very different feel than my previous job. It felt more like it was in the tech community. After years of always having to wear khakis to work, I could wear whatever I wanted! 😜 (It's the little things in life.) The list of technologies Travis utilizes is exponentially larger and significantly more distributed than what I had worked on before. There was a lot more cross-team interaction which really excites me as a person who just loves to know a bit of everything!

Trying to resolve customer issues got me really comfortable with StackOverflow and Github's search--it's really awesome to be able to look through examples of code to find similar solutions. It's basically view source on a whole different scale. 😉

When customers reported outages to our support queue, I'd often get to work together with the infrastructure team (just two people at the time!) and I became really fascinated by alerting, logging, metrics, etc--even though I knew absolutely nothing about it. My first "tech" job didn't expose me to much of this so I didn't really know how interesting I would find it. **I'd really like to dig into this more to see if that's the direction I'd like to go in, as well as utilize/improve my existing Ruby skills.**

## The Future
I'm ready to go past the basics. I'm ready to improve things (I do love squashing bugs!). I'm ready to build things. I've been thinking a lot about what I'd like to learn and what I need to learn. Since I'm mostly self-taught and making this list myself, undeniably there are things that I will need to better understand that I haven't thought of yet. 

I've been collecting a plethora of learning materials and so I'm going to integrate them into the goals in hopes that maybe if anyone reads this and shares similar goals (I have many to choose from!), there is something they can use to learn, too.

### Ruby and General Software Development
**Software Craftsmanship:** While I was interviewing for jobs before I was hired at Travis, I was asked by an interviewer about my familiarity with [software design principles and patterns](http://www.oodesign.com/). I answered truthfully--I don't have much familiarity and, to this day, I still don't. When I asked my more experienced developer friends, they recommended two books to help me: _[Eloquent Ruby](http://smile.amazon.com/Eloquent-Ruby-Addison-Wesley-Professional/dp/0321584104)_ and _[Practical Object-Oriented Design in Ruby](http://www.poodr.com/)_. I believe, before I get much further into programming, I need to finish both of these books (and I have both already!).

**Asking Better Questions:** One of the problems I struggled with in my first developer position was knowing just _what_ questions to ask. If there wasn't an error message on my screen, how was I supposed to know what to look for? I'd be stuck and I wouldn't have the language to communicate what I was stuck on or what I needed. I was often told by our senior developer to go to Google first, but Google is great at finding answers but not necessarily providing structure or guidance and it certainly can't read your mind to know what questions you need to ask (yet...).

**Just plain Ruby:** I've always done Ruby in the context of Rails, which has a lot of additional magic. ✨ I'd really like to use Just Ruby™.

**Rails:** The framework gets a lot of grief but I'll admit that I do love it! ❤️ I'd really like to continue to learn and master Rails. I have a copy of [Easy Active Record for Rails Developers](http://easyactiverecord.com/) that I'd love to finish, too.

### Testing
I've come to really love testing and I'd like to thank [Carol Nichols](http://carol-nichols.com/) for the original introduction. Trusty CMS was my first, albeit brief, introduction but it's [what made me realize just how useful good tests can be.](https://github.com/pgharts/trusty-cms/issues/132).

During my brief programming experiments during Travis's Project Friday, I rekindled my love for RSpec and started to get really excited about it. I found [Better Specs](http://betterspecs.org/) to be a truly great resource I kept coming back to. I've been meaning to watch [this screencast](http://www.rubyinside.com/screencast-coding-conways-game-of-life-in-ruby-the-tdd-way-with-rspec-5564.html) which is [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in Ruby and tested with RSpec. I thought it'd be a nice way to see RSpec in action besides what I've already done with it, as well as introduce me to Conway's Game of Life which everyone is always talking about in regards to learning new languages.

In my personal library, I also have [Rails 4 Test Prescriptions](https://pragprog.com/book/nrtest2/rails-4-test-prescriptions) and [BDD In Action: Behavior Driven Development for the Whole Software Lifecycle](http://smile.amazon.com/BDD-Action-Behavior-driven-development-lifecycle/dp/161729165X) waiting for me to read.

RSpec seems like something everyone uses but it doesn't seem like something people have a definitive go-to for learning the ins and outs so I'm all ears (or eyes).

### APIs
The world if APIs intimidates and excites me. I've done some really minor API integration in various projects but I'm still a novice at best (with my BFF [cURL](https://curl.haxx.se/docs/manpage.html)).

### Go
Having a background in linguistics, a strong love for languages, and an interest in all things operations/infrastructure makes Go a safe bet (plus we use Go at Travis as well). I'm actually pretty impressed with how many free learning resources there are for Go online:
* [A Tour of Go](https://tour.golang.org)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://www.golangbootcamp.com/)
* [Go By Example](https://gobyexample.com/)
* [Go Tutorial](http://www.tutorialspoint.com/go/index.htm)
* [Learning Go](https://www.miek.nl/go/)
* [Network Programming in Go](https://jan.newmarch.name/go/)
* [webapp-with-golang-anti-textbook](https://www.gitbook.com/book/thewhitetulip/webapp-with-golang-anti-textbook/details)

### Docker
Docker is one of those 🔥hot🔥 items. It is [one of our common infrastructures](https://docs.travis-ci.com/user/workers/container-based-infrastructure/) for builds to run on at Travis. It has many great uses but it remains mostly a mystery to me. My [coworker](http://www.solarce.org/) recommended a great 
[beginner friendly docker guide](https://medium.freecodecamp.com/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b#.ws5nhpcxu) that has been high on my list of things to go through and I have [The Docker Book](https://www.dockerbook.com/) and [Docker Up & Running](http://shop.oreilly.com/product/0636920036142.do) as well. I have access to a great [Docker tutorial from Velocity NYC 2015](http://conferences.oreilly.com/velocity/devops-web-performance-ny-2015/public/schedule/detail/43972) as well.

On the subject of Docker, and this is probably something I'd learn way further into the future, but I'd really like to learn more about [Kubernetes](http://kubernetes.io/). I mean, I have already made a super important [pull request](https://github.com/kubernetes/kubernetes/pull/5813) that even got merged. 😂 (And hey, [this pull request](https://github.com/kubernetes/kubernetes/pull/25433) today too!)

### Operations
This is another one of those categories where I know I want to (and need to) learn about so many things but not quite sure _what_ or _how_. It's an area that, while it's interesting to me, doesn't seem as 🔥hot🔥 as general programming is to others. One cool free resource is [Ops School](http://www.opsschool.org/) and I've gone through a good amount of that site. I also have [this book](http://smile.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057) I'd like to finish.

We use a lot of [Hashicorp](https://www.hashicorp.com/) products that I can't even begin to fathom how to learn. Since they are important to our infrastructure, I figured I should though. :)

Saving the best thing (to me) for last, is **monitoring, metrics, and alerting** -- I'm not really sure how people learn more about this either (besides just diving in) but it really excites me so I hope I get to do more with it in the upcoming months at Travis. 〽️ I'd really love to improve our logging and alerting. And staring at pretty charts is always a plus. 😁

So much to learn. Much excite!!

![Pagemaster movie gif](http://i.giphy.com/F2tW52JBfnG6c.gif)
