# Establishing production process
laura | 2021-01-20 12:10:52 UTC | #1

I'm quite comfortable jumping around between platforms and finding what I need, but I think we can streamline a little to make it easier for us to be focused and together on the various things we want to do. 

Sometimes we discuss in Discourse, sometimes we ideate in Github. How can we be clear about what goes where and coordinate on the production of, say, a multimedia series or a particular topic?

Looking at our Github Organization, we have tons of repos. The majority are our books, and there seem to be TWO only that are relevant for everyone:

1) [Our Governance repo](https://github.com/open-organization/governance/issues) - this holds our mission and the like (check out [the wiki](https://github.com/open-organization/governance/wiki)!) as well as tickets about organizing ourselves. 
2) [Our Editorial repo](https://github.com/open-organization/editorial/issues) - this is where ALL our content ideas live, and we have a progress procedure documented as [project columns](https://github.com/open-organization/editorial/projects/1).

I filed a ticket asking @bryan to pin these two repos for us.

**The editorial board establishes the process as:**

* Have ideas (wishlist) - *perhaps ideation happens in Discourse instead, to reduce the number of "dead" tickets?*
* Draft (drafting)
* Get feedback (developmental editing)
* Revise (author revision)
* Get feedback (copy editing)
* Make it pretty (typesetting)
* Get feedback (final approvals)
* Schedule
* Publish

I think this process works for multimedia as well, but would like to reduce the number of columns for a more streamlined overview. Perhaps we combine Copy Editing and Typesetting, and Final approvals and Scheduling? 

We can just mark the type of content using issues and labels:

![image|690x111](upload://kMQLYQ0GnteB0ZbPJGsHmEnrRks.png) 

Then, when issues are triaged in the editorial board, we can filter by content type, if need be:
![image|690x206](upload://m1Zb9Xn997MrA4DIplgVmz5fIA2.png)

What do you all think about ideation and discussion in Discourse and actual production in Github?

-------------------------

Bryan | 2021-01-21 11:50:03 UTC | #2

Thanks so much for launching this discussion, @laura. It's the perfect step to follow yesterday's excellent [community strategy workshop](https://www.theopenorganization.community/t/a-2021-strategy-workshop/176).

I'll add some of my thoughts and context inline!

[quote="laura, post:1, topic:192"]
> I’m quite comfortable jumping around between platforms and finding what I need, but I think we can streamline a little to make it easier for us to be focused and together on the various things we want to do.
>
> Sometimes we discuss in Discourse, sometimes we ideate in Github. How can we be clear about what goes where and coordinate on the production of, say, a multimedia series or a particular topic?

[/quote]

[quote="laura, post:1, topic:192"]

> What do you all think about ideation and discussion in Discourse and actual production in Github?

[/quote]

In my mind, the distinction has always been something like this:

- **GitHub** is our project tracker, our ticketing system and accountability mechanism. It's "where the work happens." When I think of "the Open Organization *project*," I think of GitHub.
- **Discourse** is our community conversation hub, our idea factory and brainstorming space. It's "where the ideas grow." When I think of "the Open Organization *community*," I think of Discourse.

Not sure if that resonates with anyone but me, but there you have it.

[quote="laura, post:1, topic:192"]

> Looking at our Github Organization, we have tons of repos. The majority are our books, and there seem to be TWO only that are relevant for everyone:
> 
> 1. [Our Governance repo](https://github.com/open-organization/governance/issues) - this holds our mission and the like (check out [the wiki](https://github.com/open-organization/governance/wiki)!) as well as tickets about organizing ourselves.
> 2. [Our Editorial repo](https://github.com/open-organization/editorial/issues) - this is where ALL our content ideas live, and we have a progress procedure documented as [project columns](https://github.com/open-organization/editorial/projects/1).
>
> I filed a ticket asking @bryan to pin these two repos for us.

[/quote]

Pinned and done!

By virtue of becoming an ambassador, every Open Organization Ambassador has write access to the governance repository. This is currently not true of the editorial repository, but it certainly can be if we think that's something everyone would want. In my mind, the philosophy behind what we may call the "tons of repos" approach to GitHub is that each of these repos is its own discrete project-within-the-project that will (hopefully, ideally) amass its own working group. So the *Leaders Manual* eventually has its own maintainer and working group; the *Field Guide* has its own maintainer and working group—each with its own level of access for various participants. Again, not sure that resonates with anyone but me, which would not shock me. So I am always open to rethinking how we're organized.

[quote="laura, post:1, topic:192"]

> **The editorial board establishes the process as:**
>
> * Have ideas (wishlist) - *perhaps ideation happens in Discourse instead, to reduce the number of “dead” tickets?*
> * Draft (drafting)
> * Get feedback (developmental editing)
> * Revise (author revision)
> * Get feedback (copy editing)
> * Make it pretty (typesetting)
> * Get feedback (final approvals)
> * Schedule
> * Publish
>
> I think this process works for multimedia as well, but would like to reduce the number of columns for a more streamlined overview. Perhaps we combine Copy Editing and Typesetting, and Final approvals and Scheduling?

[/quote]

I am all for streamlining, but would need to retain, at least, the distinction between copy editing and typesetting, because different groups use those lanes for tracking work. Copy editors like the inimitable @trncb use the former; I use the latter. So merging them might create for us some ambiguity that leads to dropped work.

To make the process more inclusive of non-print media, I might suggest something like:

- Backlog: Materials for which we have an idea and basic direction but no activity
- Draft: Material is being drafted/created
- Initial review: Appropriate editor/channel lead is reviewing the first cut of the work
- Revision: Author is addressing feedback from appropriate editor/channel lead
- Final edits: Materials are revised and being polished (copy edited in the case of articles)
- Production: Materials are undergoing production process (typeset if print; adding bumpers or rendering if video)
- Receiving final approvals: Authors are reviewing work before launch
- Scheduled: Authors have approved work and we have a concrete date for publication
- Published: Material published and promotional work (social media, etc.) can begin

If this is a square-beg-round-role situation with regard to video, I'd welcome a discussion about creating a separate board for videos, one that outlines an editorial process better suited to that kind of material. But I must say I really like this:

[quote="laura, post:1, topic:192"]

> We can just mark the type of content using issues and labels:
>
> ![image](upload://kMQLYQ0GnteB0ZbPJGsHmEnrRks)
>
> Then, when issues are triaged in the editorial board, we can filter by content type, if need be:
>
> ![image](upload://m1Zb9Xn997MrA4DIplgVmz5fIA2)

[/quote]

The fewer boards, the better, in my view!

Thanks for your great work on this, @laura. I'm so excited to see more community members getting involved in the editorial process.

-------------------------

Bryan | 2021-01-29 16:02:26 UTC | #3

Okay. I [made this now](https://github.com/open-organization/editorial/wiki/Open-Organization-Community-Editorial-Process).

As with most things, I realized halfway through that @Laura Was Right :tm: and I pretty much adapted/adopted the editorial process she proposed.

I have updated [the editorial queue](https://github.com/open-organization/editorial/projects/1) to reflect the process changes now documented in [the wiki](https://github.com/open-organization/editorial/wiki/Open-Organization-Community-Editorial-Process).

Feedback very welcome!

-------------------------

