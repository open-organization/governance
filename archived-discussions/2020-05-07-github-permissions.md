# GitHub permissions
Initiated 2020-05-07

## Ben Cotton 
2020-05-07

Hey @Bryan, I went to push a WIP of a distributed work guide to a branch last night and GitHub said "no, you're not allowed". Is that intentional? i.e. do you want people to do all work in forks and then submit PRs?

If it is, I would like to advocate allowing regular contributors to commit directly to the main repo (perhaps with the `master` branch protected if you want to control how things get added). I have no problem with the idea of doing all content in branches and then merging via a PR, but I'd rather not have to fork a project that I'm a regular contributor to (I have opinions about the need to fork for drive-by contributions, too, but no real solutions for that so I'll just keep those to myself for now).

This is entirely a "I just don't want to have forks in my account if I don't need to" thing that has no real impact on me, but I thought I'd throw it out there anyway. :-)

## Bryan Behrenshausen
2020-05-07

*(Moving this to our governance forum as I'd like the results of our discussion to be cataloged there, since we might evolve this discussion into a broader one about repository permissions in general.)*

> Is that intentional? i.e. do you want people to do all work in forks and then submit PRs?

It is definitely not intentional. Truthfully, it's a result of my not really fully processing GitHub's recent changes to the ways repository permissions work combined with my relative ignorance about certain matters of GitHub etiquette and best practice. 

> I would like to advocate allowing regular contributors to commit directly to the main repo (perhaps with the `master` branch protected if you want to control how things get added). I have no problem with the idea of doing all content in branches and then merging via a PR, but I’d rather not have to fork a project that I’m a regular contributor to (I have opinions about the need to fork for drive-by contributions, too, but no real solutions for that so I’ll just keep those to myself for now).

I think I see what you're advocating here, and if I understand it as I believe I do, then I totally agree. I *think* that the solution, from the standpoint of GitHub workflow, is to create a "team" for each project, then give contributors on that team various levels of access to the repository. So if you're a regular contributor to the project, you get write access, etc. I will look into that now and see what I can do.

Does this sound like an acceptable precedent?

Eventually, I'd like all the repositories and projects in our organization to have "maintainers" (hence my advocating for [that new role](https://github.com/open-organization/governance/blob/master/community-roles.md) in our governance documentation. Maintainers, then, would be _de facto_ leaders of their respective projects, could set vision and development schedules for them, could organize their teams and permissions as they see fit, etc.

@laura and I are maintainers on the new guide, so I'll configure the team accordingly and also add the other writers to that "team." If that still doesn't solve the problem in a way you're comfortable with, then let's please continue the conversation.

## Ben Cotton
2020-05-07

> Does this sound like an acceptable precedent?

Yep, that sounds exactly what I was advocating for. I like the future direction you outline, too.