# Building our new showcase on the web
Bryan | 2020-04-07 14:23:06 UTC | #1

As we discussed during [last month's meeting](https://www.theopenorganization.community/t/march-12-2020-meeting/115/4), the Open Organization community will soon have its own website independent of both Red Hat marketing organizations and Opensource.com. I'd love for the community to play a role in building and maintaining its new showcase on the web.

## Project overview

The Open Organization community will receive a new, public-facing presence on the web in the form of a refreshed website. We'll plan to launch the new website at the same time our [new community brand](https://community.redhat.com/brandguide/) is finalized and ready for unveiling. At the moment, we're targetting May for the joint culmination of these two projects.

Our initial website will be nothing more than a *minimum viable product* that gets us up, running, and out into the wider world. We can look to [other open source communities](https://community.redhat.com/brandguide/) for guidance and inspiration.

## Technical notes

For the folks who love the implementation details:

At the moment, we're planning to host the website with [GitHub Pages](https://pages.github.com/) using a repository inside our GitHub [community organization](https://github.com/open-organization-ambassadors). This has several benefits, not least of which is the fact that *the entire community* can collaborate on the website, propose timely changes to it, update it together, etc., in the same place we maintain all our other resources (that is to say, GitHub). This means we'll be using some [Jekyll](https://jekyllrb.com/) to maintain the site and make updating it as easy as possible for non-technical contributors. I encourage anyone with experience here to please reach out! In the meantime, the [Open Source Community Infrastructure team](https://osci.io/) in Red Hat's Open Source Program Office will be lending a significant hand helping me sweat the technical details that are way beyond my ken.

## Let's get started

So here's the fun part! Let's talk about what we'd like our new community showcase to look and feel like.

### Site vision

What materials should we be sure to include in the *initial version* the Open Organization community's new website?

Let's maintain a short list of necessities:

- A community mission/vision statement page
- A guide to [getting started as a community contributor](https://opensource.com/open-organization/start)
- A stylized version of the [Open Organization Definition](https://opensource.com/open-organization/resources/open-org-definition)(?)
- A [rundown of the book series](https://opensource.com/open-organization/resources/book-series)
- A link to places we're working and publishing ([Open Organization channel at Opensource.com](https://opensource.com/open-organization), etc.)

### Site design

We'll also need to determine how the site should look and feel. The Community Infrastructure team does *not* offer assistance with theming and site design (just activation and hosting), so we'll need to settle on a fairly standard template to get us up and running. I've been told [this collection of templates](https://jekyllthemes.io/) (and in particular [this set](https://jekyllthemes.io/github-pages-themes) is a great place to begin looking for design inspriation.

Let's maintain a short list of our favorite options:

- [Made](https://jekyllthemes.io/theme/made-portfolio-jekyll-theme)
- [Doks](https://jekyllthemes.io/theme/doks-documentation-jekyll-theme)
- [Alembic](https://jekyllthemes.io/theme/alembic)
- [Elbe](https://jekyllthemes.io/theme/elbe-multi-purpose-theme-powered-by-jekyll)

I'll update this space as new details emerge and the project evolves. In the meantime, I'd love to hear ambassadors' thoughts on site preferences.

-------------------------

laura | 2020-04-07 09:40:35 UTC | #2

I LIKE [THIS ONE](https://jekyllthemes.io/theme/elbe-multi-purpose-theme-powered-by-jekyll) BECAUSE IT'S CALLED ELBE LIKE MY RIVER AND ALSO HAS ROLLLER SKKKKAAATTTTEEESSS

Just kidding, I'm not sure what we should aim for in terms of design just yet. We should try to pick something super flexible so that as we figure out what belongs in this new home, we don't have to rebrand/redesign too much. 

Content: Given [the governance conversation,](https://www.theopenorganization.community/t/our-future-ambassador-group-governance-and-focus-project/121) would be cool to talk about how the new site might increase social credit/human connection* and whether or not some of our resources should be more designed (e.g. [our program description](https://github.com/open-organization-ambassadors/ambassador-program-description/blob/master/ambassador-program-description.md))

*Some of us field off the cuff kind of requests and outreach which leads me to believe that folks are looking for ways to get in touch with individual community members? Should the site try to be a welcoming committee that also points people places?

Finally, [I have some Jekyll experience](https://www.laurahilliger.com/techie/help-me-jekyll/), so let's see if I can be helpful!

-------------------------

Bryan | 2020-04-07 15:04:35 UTC | #3

Well, I do like that particular template, so will add it to the list nonetheless! (Can't promise roller skates in _our_ published fork of the template, however—but I promise to leave every possibility open).

I've added some time at [the April Ambassadors meeting](https://www.theopenorganization.community/t/april-09-2020-meeting/122) to discuss some website matters (and mostly to ensure everyone is aware that this discussion is happening!)

I do like that idea of foregrounding the site as a "welcoming committee" for curious potential contributors. Let's brainstorm a bit more about ways to underscore that vibe in our initial launch.

I am _so glad_ you have some Jekyll experience! I promise not to make you regret telling me that. I'm going to brush up on my own but will be bugging you a bit, I'm sure. Luckily, we'll have help from OSPO's community infrastructure team, too, as we get rolling.

-------------------------

jenkelchner | 2020-04-09 12:16:56 UTC | #4

My vote is for Elbe.  The others feel "not enough" for the future vision of Phase II of this group.  Phase II has potential to be more than a "blog" site and Elbe has room for that visually.  I haven't gone through all of Jekyll yet but working off of the curated list I only +1 Elbe.

-------------------------

Bryan | 2020-04-09 12:21:16 UTC | #5

I've been eagerly awaiting @jenkelchner vote for theme!

For anyone interested, there's [an interactive demo of Elba](http://elbe.blahlab.com/) that's helpful for understanding how it feels.

-------------------------

jenkelchner | 2020-04-09 15:11:25 UTC | #6

Not sure which thread to add this to so I'll put it here on web presence:

Can we please quickly make a decision on Twitter handles?  I realized when viewing Jim Whitehursts Twitter this week that his is listed as Author @openorgbook... which is 100% correct except that handle is the community stuffs....  

Do we have any thoughts on how to proceed with that? Or prior discussions on GitHub that are helpful to engage with?

-------------------------

Bryan | 2020-04-09 15:16:40 UTC | #7

Thanks so much for raising this, @jenkelchner. I've been thinking about it, too.

We've been carrying on the Twitter discussion in [this thread](https://www.theopenorganization.community/t/our-twitter-handle/91/12). But for folks lurking here, the quick update is:

- We tried to claim ``@openorganization`` and it's too long, according to Twitter's stringent requirements.
- Our second choice is ``@TheOpenOrg`` which is claimed but unused. I can talk to Red Hat's social media experts to learn more about "reclaiming" an unused account. But it might take some time.
- We could try for another, unclaimed, option. And then I would engage the social media team to help us "switch accounts," which seems like a pretty straightforward process.

-------------------------

Bryan | 2020-04-16 19:04:15 UTC | #8

Related to this, I've just opened a new GitHub issue about the possibility of "moving into" ``github.com/open-organization``, as a new acquaintance (and apparent fan of our work!) has offered to donate that organization and URL to our community. From my note on GitHub:

> This would mean moving resources from the `open-organization-ambassadors` collection of repositories to the `open-organization` collection of repositories, and operating that GitHub organization as our new community home. This would also be the repository from which we'd host and serve the new Open Organization project website. We'd then discontinue use of the `open-organization-ambassadors` repositories. All Open Organization Ambassadors would automatically regain member-level access to all project repositories when we'd made the move. I believe this move would be a positive and useful one for our community but did not want to undertake something this significant without at least observing a comments and discussion period. So let's please discuss!

I want to cross-post this development here, in case ambassadors had thoughts or feedback not necessarily meant for public consumption.

Eager to hear what folks think.

-------------------------

laura | 2020-05-29 13:32:33 UTC | #9

# Passing the Joneses on the freeway
![timeline|690x395](upload://ljbZqbmWIa0UeHFbwlxU5ebGRCt.jpeg) 
[interactive timeline](https://timelines.gitkraken.com/timeline/8e59ecb2865947c3b579cf61864c7da1) If you want to be a collaborator, let me know. There's no setting for fully editable by anyone, unfortunately.

Bryan and I had a chat recently, and I had a random idea about future things involving our website. While we were on the phone, I counted our [14 GitHub repos](https://github.com/open-organization), 11 of which are books or resources. Later I realize Github counts repos for me.

![repos|352x114, 50%](upload://kUdukMRNod1iXOtmDybG2yBkTwm.png) 

We release these books and then often make changes and release new versions. I thought, wouldn't it be cool if our website kept up with us with minimal effort from our side? What would that mean? What would it take?

# Tech
After several google attempts, [Git Submodules](https://help.github.com/en/github/working-with-github-pages/using-submodules-with-github-pages ) might be the right solution for the idea of pulling content from various repos into a jekyll-run Github Pages site. So if theopenorganization.org runs jekyll, we should be able to pull in a readme or multiple files from all the other repos.

Can the Community Infra Team help us with this? I would be happy to have a call with them. I'm nerdy enough to make an implementation plan with them. I suspect we'll need some consistencies between repos in the form of overviews / MD files....

# Site Map
So it would seem that we will all need to collaborate on content, but to do so we need an overview. I've started one:
![sitemap-oo|593x500](upload://pMfA5X2B1fo4hS2oFbQ0iSmhMMf.png) 

[this mindmap](https://mm.tt/1522721021?t=KsYDyrHW6k) is editable to anyone, help build it out!

-------------------------

Bryan | 2020-05-29 14:03:34 UTC | #10

I thought I had eradicated all photographic evidence of your beating me at the video game. Apparently I did not.

This is awesome, @laura. Thank you for your work here. Thanks especially for the site architecture mind map—always the hardest part for me (visualizing it all)! I think it's a great start and I'll hop over soon to see if I'm able to offer any helpful tweaks. 

> Can the Community Infra Team help us with this? I would be happy to have a call with them. I’m nerdy enough to make an implementation plan with them. I suspect we’ll need some consistencies between repos in the form of overviews / MD files…

So I am having a conversation about this today, as a matter of fact! The [Community Infra Team](https://osci.io/) has just welcomed a summer intern and I'm swooping in as quickly as I can to see if I might get some of this person's time dedicated to assisting with our site relaunch (I mean, it's a great summer project and portfolio piece, right?). If I can achieve that, we'll have a dedicated resource this summer as we build this out. :crossed_fingers: Incidentally, my team in the Open Source Program Office also welcomed a new intern this week—one dedicated to marketing. Wouldn't that skillset also be nice at a time when we're rebranding? Working on it.

I'm sure a site map like the one you've sketched here will be one of the first things a potential web architect will ask for, so I'm please to know we've already got something percolating.

I **really** like the notion of attempting to automate as much as we can from our repositories. I think the Infra folks might be able to help with this, too. I will specifically raise the question of Submodules and see what they say.

The scenario I'm currently noodling on is one where each of our repositories ultimately has its own maintainer (hence the addition of that community role to our recently updated [roles docs](https://github.com/open-organization/governance/wiki/Community-Roles)). The maintainer would be the repo's primary steward. At the moment, repos contain books, by and large. But perhaps the repos could also contain their own *web pages* for the book project, (which would feature download links, sample chapters, recorded interviews with an author or six, additional resources, etc.). The team working on that repo (led by its maintainer) would also work to help the community keep the repo's respective web page up to date. The Open Organization project's primary site <theopenorganization.org> would then link to all of these team-maintained pages, which would follow a standard template. Teams would therefore work at "level three" in @laura's site map.

Just kind of "typing aloud" here. I'm sure better models exist, so looking forward to exploring more.

-------------------------

Bryan | 2020-06-23 18:17:44 UTC | #11

After four months, I've finally finished my work with IT. Our domain at ``theopenorganization.org`` now points to [GitHub Pages](http://theopenorganization.org/). I've reached out to our team here and initiated talks about getting website construction back underway after the launch of the new logo and brand (soon!).

-------------------------

laura | 2020-06-24 11:47:46 UTC | #12

I added the minima theme and just threw some stuff in there to get it working. Pull request here:

https://github.com/open-organization/open-organization.github.io/pulls

-------------------------

Bryan | 2020-06-24 17:18:56 UTC | #13

Thank you so much for this!

I responded in your pull request but will reproduce some of my response here, in case others are interested in having the discussion I suggested there.

I would like to review the proposed site a little more deeply, though in the interim I believe a few components of what you've suggested here should be up for community discussion. Just a few things I see, for example:

- It looks like the proposed site includes some kind of "blog" functionality. Is that something we want? Something we're willing to maintain? And how do we do it?
- It looks like this site hooks into a discussion-facilitation instrument. Is this something we want to facilitate on the site? Something we have the capacity to maintain?
- It looks like this site contains a pre-baked community code of conduct. This is something I feel the entire community should have a chance to discuss, modify, and ratify before it's "live" somewhere.
- It looks like this site uses Google Analytics to track usage and metrics. Are we all okay with that? And how do we set it up if so? Who has access, etc.?

I am certainly not an expert in web design, of course, so maybe I am misunderstanding the code I'm reviewing (it would not surprise me!). Corrections welcome. 

In the meantime, if there's some even lighter-weight/lower-overhead template we can deploy, just to get some basics up and running, perhaps we could do that as we discuss the larger "infrastructural" issues. For example, in my settings for the repository I see a "Theme Chooser" that allows us to spin up something a little more basic. While perhaps none of the themes it offers are ideal, at least they seem to be more like a "baby step" on the road to a fuller-blown website like the one your PR proposes, and could serve us until we can spend the time discussing and building out specific functionality.

And I will be circling up with the community infra folks on our end, too, to see what kinds of advice they can offer.

-------------------------

Bryan | 2020-07-09 14:39:34 UTC | #14

Just a note here that @laura is organizing a website sprint (a "jam," as it were) for us to engage in some focused collaboration on this project. Please join! Details [in this thread](https://www.theopenorganization.community/t/website-jam/145/4).

-------------------------

Bryan | 2020-07-21 17:16:33 UTC | #15

To keep our thread updated: We're now working on the [version of the site](https://github.com/LauraHilliger/open-organization.github.io) that @laura forked. At the moment, design is less a concern than content is. We're working to build the pages we'd like to see live in our MVP release of the new site, whatever shape that may take.

-------------------------

HeidiHVL | 2020-08-26 14:34:00 UTC | #16

I was taking a look at the [new site](https://theopenorganization.org) and really like the clean design! I wanted to offer some thoughts on a few tiny things:
1. I feel like the "buttons" are hard to see. White on aqua can be tough on my old eyes that need progressives. :) 
2. When you click a button, there's no indication of what button you clicked / what page you are on. There's no title, or darker button or anything. 
3. Being not-well-versed in Github, I've always felt it was awkward to name something "community" and then be linked to Github and not a page about who is in the community. Perhaps it's my inexperienced expectations :) 
4. I would love for us to use our aqua/dark blue logo on the site instead of the white/aqua logo. 
5. Do we want a link to the ambassadors off the About page? If we don't link to it, the community members might get buried and be hard to find because its on the opensource site, which is linked by Articles or Books (and that's not intuitive for finding community members). Or maybe we want more detailed bios for members off our site? Since we have more control then we could indicate the ways we are willing to help (ie for those of us with special roles, we can highlight them; for those of us with special skills or interests, we can indicate them etc)

Thanks y'all. It's looking really nice! :) 
Heidi

-------------------------

Bryan | 2020-08-27 18:15:04 UTC | #17

Thanks so much for your great, specific feedback, @HeidiHVL. Super helpful (and appreciated!).

[quote="HeidiHVL, post:16, topic:123"]
> * I feel like the “buttons” are hard to see. White on aqua can be tough on my old eyes that need progressives. :slight_smile:

[/quote]

Great feedback to have. Accessibility is important. Let me review how our stylesheets are set up and contemplate some strategies for making the navigation more accessible. @laura and @jonasrosland might also have ideas (read: likely have ideas).  I've created [a GitHub issue for this suggestion](https://github.com/open-organization/open-organization.github.io/issues/2).

[quote="HeidiHVL, post:16, topic:123"]
> * When you click a button, there’s no indication of what button you clicked / what page you are on. There’s no title, or darker button or anything.

[/quote]

This is a basic usability oversight on my part and something I can (and should) easily fix. On it. Thanks for pointing this out. I'll [update this issue](https://github.com/open-organization/open-organization.github.io/issues/3) as I work.

[quote="HeidiHVL, post:16, topic:123"]
> * Being not-well-versed in Github, I’ve always felt it was awkward to name something “community” and then be linked to Github and not a page about who is in the community. Perhaps it’s my inexperienced expectations :slight_smile:

[/quote]

At the moment, the "Community" link points users to Discourse. I did that in the wake of ongoing [conversation about the future of Discourse](https://drive.google.com/open?id=1rBI5uoyOqxZx-0A5NZKQElGdkys2Wq9A-QYTuDuBJ4Q) and the possibility that we might have even greater reason to want to direct people to it. Maybe something like "Join" or "Contact" would be a better name for the button that takes visitors to Discourse? Then we reserve the button labeled "Community" for something else? Interested to hear what others might say about this.

[quote="HeidiHVL, post:16, topic:123"]
> * I would love for us to use our aqua/dark blue logo on the site instead of the white/aqua logo.

[/quote]

Happy to consider this! It _might_ require rethinking some overall site design decisions (not an issue!) as I think the standard logo (not the "inverted," all white one) would clash a bit with our turquoise header. But we can certainly play around with this and see what looks nicest. Others are also welcome to chime in.

[quote="HeidiHVL, post:16, topic:123"]
> * Do we want a link to the ambassadors off the About page? If we don’t link to it, the community members might get buried and be hard to find because its on the opensource site, which is linked by Articles or Books (and that’s not intuitive for finding community members). Or maybe we want more detailed bios for members off our site? Since we have more control then we could indicate the ways we are willing to help (ie for those of us with special roles, we can highlight them; for those of us with special skills or interests, we can indicate them etc)

[/quote]

This is definitely a conversation I'm up for having. I _think_ I would see something like this (adding a new page and/or section specifically dedicated to Ambassadors) as something for the first "major update" to the site _after_ [initial launch](https://github.com/open-organization/open-organization.github.io/projects/1) of "Version 1." We're going to want to take some time to plan how that page will look and function, etc. At the moment, "About" points to language from our governance documents, including our mission and vision, commitments, methods, etc. I did this to ensure that visitors were receiving details on the overall _project_, not just the (more select) group of ambassadors.

I am happy to discuss this further with anyone who's interested in influencing the direction of that page. [My work on a directory](https://github.com/open-organization/governance/pull/12) is meant to be a step in this direction. I would like to avoid the conflation of "the community" with "the ambassadors," as I think the Open Organization _community_ (as a whole) is broader than the ambassador group, and "joining the community" should mean something other than "becoming an ambassador." Otherwise, that's a high initial bar for "joining the community," I think!

-------------------------

laura | 2020-09-22 09:32:25 UTC | #18

Hey everyone! Apologies for dropping out for a bit, it's been busy and is staying busy. 
@Bryan I wasn't sure if I should be tinkering on the main repo, so instead I've just sent a PR trying to realign my repo and making some light style adjustments. Took me a while because when I get into Github I have to relearn everything all the time. 

(@jonasrosland fun fact: my local build works now and render.com is royally f'd :smiley:
 
Everyone is always welcome to file issues against the website for improvements here: https://github.com/open-organization/open-organization.github.io/issues
 
Hope everyone is well!!

![beavis|492x376](upload://bP7w7USzc7uj6IIJF13h9H4ogkG.gif)

-------------------------

Bryan | 2020-09-22 12:47:15 UTC | #19

[quote="laura, post:18, topic:123"]
> @Bryan I wasn’t sure if I should be tinkering on the main repo, so instead I’ve just sent a PR trying to realign my repo and making some light style adjustments. Took me a while because when I get into Github I have to relearn everything all the time.
>
> (@jonasrosland fun fact: my local build works now and [render.com](http://render.com) is royally f’d

[/quote]

You can totally push changes to the main/production repo if you want (I *think* I've now finally gotten those permissions sorted), but perhaps it's worth syncing up so we can swap notes, I can share how this thing is currently running (the bubblegum, the string, etc.), and we can establish some shared norms and processes.

Funner fact: I could never get render.com to work for me, so my own toolchain skirts it entirely. Maybe that's the reason it's, as you say, "royally f'd": all of my work ignored its existence.

In the meantime, I incorporated all your great style adjustments and added my own notes and tweaks. Your code for incorporating the book cover images was particularly elegant. I did not know something like that was possible. The more you know. :tm:

Thanks so much for helping with this!

-------------------------

jenkelchner | 2021-02-16 12:59:34 UTC | #20

Not sure if this is place to start the convo but... here I am!  @Bryan @laura  -- I was looking for an Ambassador page with our faces and info.  

I don't see it on our new website and the menu links on OpenSource no longer appear for me... but tech is weird lately.  You can still search and find the 2015 page with the old info.  But, access to our books, lists, and things are not readily available on that site any longer. 

Sooooo... question remains...do we have a posted page somewhere or is it currently in hiding mode whilst being worked on? 

thanks :)

-------------------------

Bryan | 2021-02-16 14:26:54 UTC | #21

Thanks for raising this, @jenkelchner.

At the moment, our canonical [community roster](https://github.com/open-organization/governance/wiki/Community-Roster) is in our [governance wiki](https://github.com/open-organization/governance/wiki) on GitHub. This is the home of the most recent ambassador bios. The plan is to eventually convert this into something more robust for the web at ``theopenorganization.org``, but we haven't gotten there yet (you can follow [this ticket in our backlog](https://github.com/open-organization/open-organization.github.io/issues/10) for updates if you'd like). The truth is that working with photos adds complexity to the task of spinning this up; sizing, formatting, placing, and uploading ~15 headshots is the blocker. But if text alone is sufficient for an MVP, perhaps we can do this more quickly.

As for other resources, these are still available at ``opensource.com`` until we finalize our individual [book and resource landing pages](https://github.com/open-organization/open-organization.github.io/issues/9). On the home page, hover over "Open Organization" in the navbar, then choose select a resource from the dropdown menu.

-------------------------

jenkelchner | 2021-02-17 13:08:13 UTC | #22

Thanks for the update. 

I'm good without photos at the moment; we could link to our Discourse profiles which we each keep current.  just a thought.

The dropdown wasn't working for me which is what got me here to this request :) @Bryan

-------------------------

Bryan | 2021-02-17 13:49:17 UTC | #23

Thanks for reporting this, @jenkelchner. I just checked and it seems to be working for me. Is it still inaccessible to you today? I can report to the Opensource.com team if so.

-------------------------

laura | 2021-02-17 17:25:49 UTC | #24

:wave: yeah, @Bryan I think we were going to have some infra/buildy support at some point? I spent nearly two hours today just trying to fix my local host so that I could work on building such a page. So of course I got nothing done on it (and am now partially bald).

-------------------------

Bryan | 2021-02-17 19:52:16 UTC | #25

Yikes! @laura, I'm sorry about all that lost time (and hair). :cry: I'd like to re-use (if possible) the Markdown'ed roster file already available on GitHub as the foundation of a roster for the web (less maintenance). So I will see if I can carve out some time to get this done.

Incidentally, @jenkelchner, I was able to isolate the dropdown menu bug you noted. Dropdowns appear to be broken on [our landing page](https://opensource.com/open-organization), but not the [site more generally](https://opensource.com). I will report this to the team. In the meantime, if you need the menus, you can get to them from anywhere but our landing page! Thanks for reporting this.

-------------------------

Bryan | 2021-03-06 15:08:29 UTC | #26

Sorry, everyone, that I did not get to this as soon as I said I would.

Please see ``theopenorganization.org/roster`` for our [live community roster](https://theopenorganization.org/roster/).

In a moment, I will be updating various parts of the site to link to the roster.

Special callout to @jenkelchner and @Jimmy who specifically needed this pronto.

-------------------------

