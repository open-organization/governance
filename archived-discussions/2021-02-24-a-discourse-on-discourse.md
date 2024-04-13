# A Discourse on Discourse
laura | 2020-05-14 15:38:36 UTC | #1

> In a GitHub thread on governance, @bcotton suggests eliminating [our mailing list ](https://www.redhat.com/mailman/listinfo/openorg-list) and [centralizing all community and project communications on Discourse](https://github.com/semioticrobotic/governance/commit/babda60a1cd01e23392280d6703268f315966de0#commitcomment-38653382). Let’s discuss this.

Yes, let's discuss! We can start with a little temperature check:

[poll type=regular results=always chartType=pie]
* Keep the email list!
* Burn the email list down and let's use Discourse more better!
[/poll]

-------------------------

Bryan | 2020-05-15 11:38:31 UTC | #2

Oooo! We can do polls! Thanks, @laura!

-------------------------

Bryan | 2020-05-15 11:43:06 UTC | #3

I wonder, if @bcotton has a spare minute (ha!), would he mind just providing a little more context for this proposal in the thread, so folks understand his rationale a bit more thoroughly?

We'd had this conversation in a comment thread on GitHub, but I can't seem to retrieve that at the moment (sorry).

-------------------------

bcotton | 2020-05-15 17:07:25 UTC | #4

So my thinking here is that having multiple communication channels for the same type of communication results is bad. Why is it bad? Well you're either asking your community to pay attention to both mailing lists and Discourse, or you're segregating the discussion. In order to involve everyone, you have to run the discussion in two separate places in parallel.

For those who really love the mailing list experience, Discourse has a mailing list mode. I haven't used it personally, but I understand it to be a suitable-if-imperfect replacement.

-------------------------

Bryan | 2020-05-16 17:24:03 UTC | #5

> So my thinking here is that having multiple communication channels for the same type of communication results is bad. Why is it bad? Well you’re either asking your community to pay attention to both mailing lists and Discourse, or you’re segregating the discussion. In order to involve everyone, you have to run the discussion in two separate places in parallel.

I was thinking more about this in the shower this morning and trying to marshal my thoughts around it. I'll start by saying I'm in favor of the proposal. But I wanted to start sketching a list of benefits and drawbacks to keep the conversation going as others weigh in.

Note that ``openorg-list`` currently has 88 subscribers.

### Benefits

- Reduces the number of competing community conversation outlets
- Eliminates reliance on another piece of Red Hat infrastructure
- Opens a new channel for community conversation, contribution, and recruitment
- Begins architecture of a more robust community knowledge commons (conversations more easily searchable, etc.)

### Drawbacks

- Requires "moving" current list subscribers to a new place; some may not make the jump (and we lose potential interlocutors)
- Requires implementing new Discourse trust levels and opening forum membership to others besides ambassadors (but maybe not a drawback?)

> For those who really love the mailing list experience, Discourse has a mailing list mode. I haven't used it personally, but I understand it to be a suitable-if-imperfect replacement.

I use this mode. And I would say it's even better than "suitable-if-imperfect." YMMV.

-------------------------

jenkelchner | 2020-08-24 20:15:20 UTC | #6

A group of ambassadors continued this discussion via synchronous conversation during office hours today. Notes from that conversation are below.

## Notes from Open Office Hours

### Attendees
Ben Cotton, Ron McFarland, Ben Owens, Bryan Behrenshausen, Jen Kelchner

### Questions that frame our discussion
* What should we do with Discourse and email lists (``openorg-list@redhat.com``)? Combine them, eliminate one, channel community participants in a specific direction?
* What type of engagement do we want to invite? This question helps us determine what tool is best for our purpose.
* What kinds of participation do we want to encourage? This question helps us determine what kinds of behaviors we need to facilitate (i.e., 
* How would this platform be configured? Who would have access? These questions might help us decide which tools and platforms are most attractive to new users.

### Thinking about access
As for the "access" question, @Bryan has created color codes for various levels of access on Discourse: 
1. Public items (accessible without login) are turquoise
1. Non-public items (accessible only with login) are navy blue
1. Ambassador-specific items are purple

At the moment, there's no distinction between Level 2 and Level 3. You're either a passive observer of the public information, or you're an ambassador and have access to **everything** on Discourse. So the tool we choose should likely help us "tier" access to certain discussions or resources, create a contributor pipeline that creates a scaffolding for participation.

We have a pipeline problem—too few *new* contributors are joining the project and community. Expanding our use of a community conversation platform—whatever we choose—should help us address that challenge and grow our contributor pipeline.

### Thinking about engagement
How do we engage people? What kind of engagement do we want to see? People will need open contributors/knowledge more than ever with the emerging future.

#### Targets
* We'd like people to engage with the community and the topics the community care about
* Comments on articles and broader engagement: Convert *readers* into *participants* and *contributors*
* Make the new platform a resource for cultivating the community of authors and *potential* authors, make it a *contributor* community
* Increasing engagement to what end? What do we want to happen as a result of increased participation? More articles? More books? Better discussions? New media (podcasts, videos)? What does success look like?

#### Onboarding new contributors
* Flagging editorial wish-list items as "easy" to "advanced" to get more people involved (helps them find a task that suits their comfort level)
* Easier points of entry for new members (sometimes, engaging directly on GitHub is intimidating)

## Decisions that need making
* Do we keep Discourse? And do we eliminate the email list in favor of it?
* Do we move everything to Github and expand into other platforms that can allow for engagement (social platforms, like LinkedIn, Facebook, etc.)?
* What are other ideas for gaining contributors and community engagement?

*‒Bryan added his own notes and recollections, August 24 at 15:56*

-------------------------

bcotton | 2020-08-24 21:05:28 UTC | #7

My strong opinions, weakly held:

[quote="jenkelchner, post:6, topic:136"]
> * Do we keep Discourse? And do we eliminate the email list in favor of it?

[/quote]

I think so. Regardless of whether we want to focus on expanding our readership or expanding our contributors, having both doesn't add value.

[quote="jenkelchner, post:6, topic:136"]
* Do we move everything to Github and expand into other platforms that can allow for engagement (social platforms, like LinkedIn, Facebook, etc.)?
[/quote]

No. GitHub is not great for open discussion and it can be a barrier to entry. If we want to focus on building our reader base first, we should look how we make our content shareable, but I don't think GitHub is a part of that solution.

[quote="jenkelchner, post:6, topic:136"]
> * What are other ideas for gaining contributors and community engagement?

[/quote]

Putting out some content and promotion around submitting PRs to our content on GitHub as part of [Hacktoberfest](https://hacktoberfest.digitalocean.com/) is one opportunity to get people.

I like the idea of doing more podcast and video segments.

Having a reserved set of "easyfix" article ideas that have a low barrier to entry for new contributors can help them get started.

-------------------------

Jimmy | 2020-08-25 12:29:06 UTC | #8

I agree to move to Discourse. Email lists are not that great for information in this way. When you enter an email list there might been an archive, but with Discourse you can always read older stuff.

I'm not sure about GitHub as a platform at all recently but perhaps that's out of our hands.

Could we store notes from Office hours somewhere together? Here it's added into an ongoing/old discussion which took me some time to find if there was any notes from the meeting.

-------------------------

Bryan | 2020-08-25 14:29:16 UTC | #9

[quote="Jimmy, post:8, topic:136"]

> Could we store notes from Office hours somewhere together? Here it’s added into an ongoing/old discussion which took me some time to find if there was any notes from the meeting.

[/quote]

Sure, Jimmy. That's a great idea. Assuming no one minds the notes being publicly viewable, I can just add them to a thread in the [Meeting Notes forum](https://www.theopenorganization.community/c/meeting-notes/6) so they're archived more accessibly. No sweat.

**Update:** These are [now here](https://www.theopenorganization.community/t/august-24-2020-office-hours/150).

-------------------------

Bryan | 2020-08-25 14:43:57 UTC | #10

[quote="jenkelchner, post:6, topic:136"]

> * Do we keep Discourse? And do we eliminate the email list in favor of it?

[/quote]

I agree that having two communication platforms is confusing for participants and contributors—and, frankly, I welcome the possibility of only having to manage and maintain a single platform for community dialog. I personally like Discourse as a tool. It makes sense, is open, seems intuitive for new users, and streamlines many of the communication processes/practices our community takes for granted these days. Bonus: Switching to and opening up Discourse allows ambassadors to assist more significantly in managing and maintaining the community conversation platform. At the moment, I'm the only person with administrative access to ``openorg-list`` (hosted on Red Hat-sponsored infrastructure) and that's not ideal.

[quote="jenkelchner, post:6, topic:136"]
> * Do we move everything to Github and expand into other platforms that can allow for engagement (social platforms, like LinkedIn, Facebook, etc.)?

[/quote]

I see GitHub as a place where our "work happens in the open"—where the book series comes together and gets edited/maintained, where formal changes to governance structures and governing documents like the Open Organization Definition get proposed and ratified, where the editorial calendar gets managed and shared, etc. It's just not a great place for community engagement _outside_ "the work"—for curious readers to ask questions about their organizational cultures, for lengthier conversation about open principles and practices not directly tied to a formal "project" we've undertaken, for banter, and so on. I love what we've been able to accomplish with GitHub since we moved and enhanced our organization there. But I don't think it's a complete solution for everything we need. Someone could very well change my mind about this.

[quote="jenkelchner, post:6, topic:136"]
> * What are other ideas for gaining contributors and community engagement?

[/quote]

I support everything that's been discussed so far by @jenkelchner, @bcotton, and others: content in a different medium (audio or video), clearer "beginners" tags on article and chapter ideas, and so on. As I mentioned during office hours, one of my top goals, personally, is helping underscore the community's image as a _participatory_ place, somewhere people go not just to _consume_ but also to _create_ and _contribute_.

-------------------------

Bryan | 2020-09-11 18:54:13 UTC | #11

At [this month's meeting of the Open Organization Ambassadors](https://www.theopenorganization.community/t/september-10-2020-meeting/149/2), we decided to officially adopt @bcotton's proposal to implement Discourse as the community's primary communication tool and platform. The ``openorg-list`` mailing list will be deprecated, reserved for infrequent community announcements only.

I've made the necessary configurations to Discourse (I hope) and believe we're ready to welcome new members. I plan to announce the transition Monday, September 14 with the message drafted below.

Exciting times! Should anyone have feedback or concerns, please don't hesitate to raise either.

[details="Announcement Text"]
# Summary

The Open Organization community has opened a new platform for discussion, sharing, and collaboration at <theopenorganization.community>. This mailing list will be retired and reserved for infrequent announcements only. Please join us on the new platform to continue the conversation about the ways open principles are changing how we work, manage, and lead.

# An Important Announcement

Since 2015, the Open Organization community has facilitated a global discussion about the ways open principles can change how we work, manage, and lead.

Today—as that conversation continues, grows, and intensifies—we're taking steps to ensure our community grows with it.

This mailing list has been a place for informal discussion and collaboration since our project's inception. But email isn't always the most effective tool for facilitating robust and inclusive conversations.

So we're moving to a new platform—one built on the popular open source discussion tool Discourse—and we want members of this list to be among the first to join us there.

The Open Organization community's new home for discussion, sharing, and collaboration will be:

www.theopenorganization.community

Please swing by, ask a question, share an experience, build a resource—and continue the conversation.

Sincerely,

Bryan

---
theopenorganization.org
[/details]

-------------------------

Bryan | 2021-02-24 19:58:35 UTC | #12

Reviewing this thread, I realized I did not post an adequate summary of the outcomes from this work. Apologies for that! Let me offer it now.

Our community Discourse platform now permits three levels of access.

## Level 1: Public
Anyone can read material in a Level 1 forum without creating an account or logging in. Items like our meeting minutes and publication announcements get posted here.

## Level 2: Community access
Any project [contributor](https://github.com/open-organization/governance/wiki/Community-Roles#contributors) can read Level 2 items and post in a Level 2 forum if they've created an account. To minimize abuse and rogue posts, most of our discussions—concerning, e.g., editorial brainstorms, project and community governance issues, etc.—operate at Level 2.

## Level 3: Ambassador access
Only users with [ambassador](https://github.com/open-organization/governance/wiki/Community-Roles#ambassadors) designation can see, access, and respond to these items.

Because I am who I am, the levels are color-coded according to our brand palette:

- Turquoise (Level 1)
- Navy (Level 2)
- Purple (Level 3)

Logging this all here for our records and to invite further discussion down the road! Apologies, again, for forgetting to follow up.

-------------------------

