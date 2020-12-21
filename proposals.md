---
author: bee
published_utc: 2020-09-27
updated_utc: 2020-12-21
---

# Proposal Guidelines

This document collects recommendations for making and executing successful proposals in Decred's [Politeia](https://proposals.decred.org/) proposal system based on experience with past proposals.

## Learn and prepare

- [ ] read [Proposal Guidelines](https://docs.decred.org/governance/politeia/proposal-guidelines/)
- [ ] study [existing proposals](https://proposals.decred.org/)
  - note which were approved and rejected
  - look at voter turnouts and Yes votes percentages
  - [this](https://blockcommons.red/publication/politeia-at-2/) research report has useful statistics on which proposals are more likely to pass
- [ ] field survey
  - ask for general sentiment about your idea in #proposals chat via [Matrix or Discord](https://decred.org/community/) or [on Reddit](https://www.reddit.com/r/decred/)
- [ ] educate the community
  - a complex or highly specialized proposal that has not been previously voted or discussed by the community will likely cause a lot of questions
  - unlike a regular company where you would talk to a small group of appointed experts in a relevant field and the management, on Politeia people of all kinds of backgrounds are the decision makers, i.e. the ones who approve or reject proposals
  - it is possible that many voters will not be familiar with the domain of your proposal
  - consider starting with an educational campaign
  - one option is to host a Q&A session similar to Reddit AMA ("ask me anything")
- [ ] plan your finances
  - payments are made **in DCR** at an average DCR/USD rate of the month when the work was performed
  - since DCR is volatile and invoices are paid on 2-4th week of the next month, in most extreme cases this has resulted in up to +/- 50% difference between billed and received USD equivalents
  - read [this](https://docs.decred.org/contributing/contributor-compensation/) for more details

### Red flags

Some combination of these factors will likely raise questions or red flags for many community members:

- no prior participation in Decred community
- no prior contributions to Decred ecosystem
- known low quality of past work
- big budget requested
- for developers, no demonstrable contribution to open source
- lack of facts to support the proposal and your capacity to deliver
- unclear speech and thought (including buzzwords)

[Decredex](https://proposals.decred.org/proposals/e78bc28) proposal rejected in 2018 demonstrates many of the above issues: an entity unknown to Decred community, requesting a million dollars to build a software product, while not presenting any proofs of capacity (such as past contributions to open source).

## Draft

Write proposal draft in the Markdown format:

- [ ] post it as [gist](https://gist.github.com/) (simplest)
  - [gist help](https://help.github.com/en/articles/about-gists)
- [ ] alternatively, you can host it in the [proposals](https://github.com/decredcommunity/proposals/pulls) repository
  - compared to gists, this adds multi-user review and editing and makes the draft discoverable
- [ ] write a clean Markdown document
  - nice formatting minimizes distractions
  - bookmark this excellent Markdown [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  - check for typos with a spell checker

Add important information and avoid common mistakes:

- [ ] develop an actionable plan
  - Politeia is not for voting on mere _ideas_
- [ ] build a team
  - "I have a proposal but no time, someone else will need to do the work" will likely not work
  - negotiate with each person who will execute the proposal
  - if your proposal is approved, it does not automatically force all mentioned people to do what the proposal says
  - avoid the mistake of _assuming_ that person X will do task Y, only discover that it didn't happen when it's too late
  - obtain the commitment to deliver from each person you list in the proposal
  - ideally, each member would come to comment in the proposal to express their commitment
- [ ] include a continuity plan
  - have a "Plan B" to avoid situations like [this](https://proposals.decred.org/proposals/c830ea5/comments/56) or [this](https://proposals.decred.org/proposals/063e382), when proposal owners stopped delivering without proper continuity arrangements
  - see [this](https://proposals.decred.org/proposals/2170df6) or [this](https://proposals.decred.org/proposals/32cba00) example
- [ ] pick a clear proposal title
  - summarize the proposal in one succinct line
  - avoid hypey, vague or alarming titles
  - as a bad example, title "A practical marketing opportunity - Massively boost the use case for DCR" [here](https://proposals.decred.org/proposals/2dcbc3e) was criticized for being manipulative and not saying anything about about the proposal
- [ ] address non-expert audience
  - people of all kinds of backgrounds will read your proposal, including those unfamiliar with your field, and those not fluent in English
  - a good way to help more people understand your proposal is to address general and expert audiences in separate sections, as shown by [this](https://proposals.decred.org/proposals/0a1ff84) proposal
- [ ] state how assets produced by the proposal will be "transferred" to Decred's ownership
  - where will they be uploaded and who will maintain them after the proposal is finished?
- [ ] restrictions on deliverables
  - specify any license or other restrictions on deliverables
- [ ] plan the budget
  - the main figure stakeholders will care about is the total USD spend limit, make sure this number is clearly visible
  - for convenience it helps to also present monthly USD spend limit
  - if expected (average) and maximum monthly/total spend may vary significantly, add both numbers as done [here](https://proposals.decred.org/proposals/32cba00)
  - talk to each member, get their monthly USD estimates (expected and maximum)
  - a common practice is when "any unspent funds will remain in the Treasury", state this if it fits your proposal
  - you may include estimates of labor hours and hourly rates that produced the total USD budget. Some proposals show this to be more transparent and provide an extra sanity check, while some omit hours to not go into too much detail and/or protect individual contractor's privacy. In general this is not required and it is more practical to think and communicate the proposal in terms of USD, and mention hours only for context and sanity checks (e.g. to let people ask questions like "why do you need 100 hours to update this page?"). What matters in the end is the work delivered and funds spent.
  - account for any raise you plan to award your team throughout the duration
  - include a bit of extra funds for unforeseen expenses
- [ ] break down where the money goes
  - any non-trivial amount of money needs a breakdown of how it will be allocated
  - good itemization boosts confidence, allows to discuss and adjust the plan
  - see good examples [here](https://proposals.decred.org/proposals/c830ea5), [here](https://proposals.decred.org/proposals/1dc1571) or [here](https://proposals.decred.org/proposals/350f64b)
  - big chunks of funds without a breakdown will raise questions
  - not so good example [here](https://proposals.decred.org/proposals/bc20f98), where a $78K item was lacking due decomposition
- [ ] plan for coordination overhead
  - whether you're going to bill for it or not, include the time/effort for communication/coordination/management/reporting in your estimates
  - esp. if >1 people are executing your proposal
  - as a proposal owner, you will likely spend quite some time writing up the proposal, answering questions, and coordinating other people. If you wish to be compensated for this work, include it in the budget and mention it in the proposal.
  - as a real life example, it took me more than 10 hours to prepare the [moderation](https://proposals.decred.org/proposals/32cba00) proposal and reply to comments
- [ ] the proposal must be priced in USD but the payments will be in DCR
  - in rare cases pricing in DCR could have strong benefits (e.g. prize pools), clarify this with Politeia moderators
- [ ] state an explicit start and end date of the billable work
  - e.g. "work will be performed for 6 months between August 1, 2020 and January 31, 2021"
  - even if start date is in the past, for [example](https://proposals.decred.org/proposals/c093b8a) "the proposal also covers the work performed in September and October 2020"
  - some proposals do not state this explicitly and it becomes hard to tell for when they are allowed to bill
- [ ] state proposal end condition: when term ends, when money runs out, or other
- [ ] list all risks that you already know
  - examples [here](https://proposals.decred.org/proposals/0a1ff84) or [here](https://proposals.decred.org/proposals/32cba00)
- [ ] for RFPs (Request for Proposals), include a deadline for submissions and any rules they must adhere to
- [ ] include any other important info
  - who you are and links to verify your background
  - milestones, reporting schedule, etc
  - any useful info generated and clarified during draft discussion outside Politeia
  - remember: your proposal is kind of a _contract_ with Decred stakeholders. Having a clear contract to reference will help to resolve any possible disputes around deliverables or billing.

Share and iterate the draft:

- [ ] share the draft in #proposals chat room via [Matrix or Discord](https://decred.org/community/) or [on Reddit](https://www.reddit.com/r/decred/) for first round of feedback from community members
- [ ] never assume that a lot of people read chats
  - I estimate is that ~100 people or less actively follow #proposals chat, as of Sep 2020

## Publish, promote, engage, update

- [ ] prefer public places
  - avoid hard-lobbying your proposal in private. Private chats and small groups are ok for collaboration/iteration "churn", but promoting the proposal "behind the scenes" will leave a bad taste and people will likely learn about it. In contrast, facing and addressing any criticism in public will boost your credibility.
- [ ] submit the proposal to Politeia
  - download the so-called Proposal Bundle that contains a cryptographic proof of submission
  - it may take up to a few days for the proposal to get verified and published
  - if it doesn't show up, ask in #proposals chat
  - if attempts to contact admins fail and you suspect unfair censorship, follow the [docs](https://docs.decred.org/governance/politeia/politeia-censorship/) and use Proposal Bundle to prove the submission
- [ ] promote pre-vote
  - submit proposal link to [r/decred](https://www.reddit.com/r/decred/)
  - post in #proposals room if it wasn't already posted by Politeia moderators
  - post in relevant chat rooms (e.g. #marketing or #dev)
  - post proposal summary and link in your Twitter account
  - alternatively, you may use a "generic" auto-tweet by @pi\_crumbs like [this](https://twitter.com/pi_crumbs/status/1301311766266294273) (not automated yet)
  - ask in #media or #proposals to retweet. Retweets by @decredproject are subject to sanity rules like no giveaways or retweeting competitions, spelling errors, abuse of CAPS, punctuation, or emojis.
  - find a good balance between being annoying and too shy
  - remember: if _you_ don't promote your proposal, it may happen that _nobody_ will!
- [ ] actively engage with commenters
  - answer questions and clarify misunderstandings
  - make sure you don't miss email notifications from Politeia
- [ ] update the proposal
  - as you discover common questions or points of confusion, edit the proposal to address them
  - imagine that most voters will only read the final revision before casting a vote, and that they will _not_ read the comments. Comments take time to read and are not shown in Decrediton (the main GUI wallet).
  - again, treat the proposal document as a _contract_ with Decred DAO
- [ ] summarize significant changes in the proposal itself
  - there is a feature to view text diff between proposal revisions, but not everyone knows how to use it
  - when the changes are big or there are many of them, it takes time to read the diffs
  - noting major changes at the end of the proposal makes them visible and saves time for the stakeholders, whose time and attention is a scarce resource
  - those interested in detailed changes can always check the diffs
  - see examples [here](https://proposals.decred.org/proposals/063e382) and [here](https://proposals.decred.org/proposals/32cba00)
- [ ] give it some time for discussion
  - I recommend [2 weeks](https://github.com/decredcommunity/issues/issues/117) to let everyone digest the proposal and post feedback
  - even longer for proposals with bigger budget or impact
- [ ] authorize the vote
  - it may take up to a few days for the vote to start as admins try to group proposal votes together to increase engagement
  - you can no longer edit the proposal once the vote starts
  - new comments and questions can still appear, keep an eye on them and respond quickly
  - the vote runs for 7 days
- [ ] promote again when the vote starts
  - e.g. tweet about it and ask in #media for a retweet

## If the proposal was abandoned

- [ ] do not delete the text
  - rather, add a note about abandoning at the top or bottom
  - even abandoned proposals are worth studying and learning from
  - you cannot delete data from Politeia anyway, all versions are stored forever. Clearing the proposal just makes it harder to access.
  - not trying to hide anything improves your credibility for possible future proposals
  - bad examples [here](https://proposals.decred.org/proposals/4f81031) and [here](https://proposals.decred.org/proposals/772d083)
  - good example [here](https://proposals.decred.org/proposals/6b7ba5b)

## If the vote failed

- [ ] talk to people and try to understand why it failed
- [ ] look at vote counts
  - if it's like 95% No then the idea is really bad and needs to be reconsidered or abandoned
  - but if it's like 40% Yes it's actually a good result that means thousands of tickets (worth millions of USD) supported the idea and it could pass after adjustment, at another time, or under different circumstances
- [ ] consider adjusting the proposal and trying again

## If the vote passed

- [ ] tweet about the success and next steps
- [ ] survey people who voted No
  - if approval was lower than ~70% Yes, it means that thousands of tickets (worth millions of USD) voted against your proposal
  - survey what the remaining ~30% think
  - a good example [here](https://www.reddit.com/r/decred/comments/gzw6hl/what_are_the_thoughts_of_the_394/)
- [ ] convince people who voted No
  - do your best to take the No voters into account (unless it goes against the majority of Yes voters, obviously) and demonstrate good work to win more support for your future projects
  - good examples are Monde PR [phase 2](https://proposals.decred.org/proposals/c81926b) (90% Yes) vs [phase 1](https://proposals.decred.org/proposals/bdd02d8) (72%) and Bug Bounty Program [phase 3](https://proposals.decred.org/proposals/2170df6) (98%) vs [phase 2](https://proposals.decred.org/proposals/073694e) (93%) vs [phase 1](https://proposals.decred.org/proposals/d33a266) (90%)
  - try to beat them in your next proposals!
- [ ] keep the community updated on how the work is progressing
  - Politeia currently [lacks](https://github.com/decred/politeia/issues/591) progress and financial reporting features, but there are other ways to post updates
  - figure out the contents and schedule of reports, discuss this with your proposal team
  - post progress updates periodically, e.g. once a month
  - long tedious reports are often not necessary, but a few words every couple weeks is so much better than silence
  - good examples are Ditto's [biweekly](https://github.com/decredcommunity/proposals/tree/master/pr-ditto/updates) updates, Monde PR's monthly updates posted in chats and Decred Journal, or Spanish team's [monthly](https://github.com/decredcommunity/proposals/tree/master/proposals/3c02b67/updates) reports
  - I recommend submitting reports to the [proposals](https://github.com/decredcommunity/proposals) repository to collect them in one place
- [ ] learn how payouts work
  - submit monthly invoices before ~10th for work performed in previous month
  - ensure that your proposal team members submit in time, too
  - if you submit too late you may miss the pay day and will have to wait till next month
  - learn how CMS and invoices work, don't hesitate to ask
- [ ] do not disappear
  - if you just go silent, this may fuel all kinds of speculation, negatively affect your reputation and damage support of your future proposals
  - if unforeseen events happen and you're suddenly short on time, try to at least "show up" once in a while
  - find people you trust and delegate/transfer your duties, including oversight and funding decisions
  - stay in touch with people who depend on you
  - post short status updates in public places
  - bad news is better than no news, i.e. even "I'm ok but unable to deliver for at least 4 months" is infinitely better than everybody guessing what to expect
  - set up notifications for important keywords
- [ ] plan the next proposal
  - if you plan to "renew your contract" and continue working via another proposal, plan it in advance to avoid interruption of funding for your work
  - submit next proposal in advance so that the discussion and voting will finish by the start of the next billing work period
  - for example, if your 6-month proposal bills for work between Jan 1 - Jul 31, and you want the next one to start Aug 1, then start drafting around Jul 1 and submit before Jul 7 so that 2-week discussion and 1-week voting will fit

## Miscellaneous

- Some proposal authors refer to themselves as "author" or by name in the proposal. I think using "I" is more direct and feels better.
- Unlike Reddit, on Politeia your comments are not automatically upvoted by you. This leads to a slight skew of comment score in favor of those who upvote their comments. With a bit of extra clicks you can avoid this tiny disadvantage. Support [this](https://github.com/decred/politeiagui/issues/845) issue if you want to see it fixed.

## Further reading

- [Writing Proposals on Politeia](https://medium.com/@decreddragon/writing-proposals-on-politeia-pi-e345621652a2) by The Decred Drive
- [Did you know Decred has Governance](https://www.youtube.com/watch?v=1BNW60RE0rQ) by Decred Society - quick video intro to Politeia starts around 5 min mark
- [Politeia Digest](https://blockcommons.red/politeia-digest/) by @richardred provides a compressed overview of what is happening on Politeia

## About

This document evolved from a 2019 [comment](https://github.com/decred/dcrdocs/issues/848#issuecomment-471795670) when discussing [Proposal Guidelines](https://docs.decred.org/governance/politeia/proposal-guidelines/) page of the main documentation website. When the list got bigger I moved it to a separate document in my personal [notes](https://github.com/xaur/notes) repo. Over the year it has grown to a point where it can help more people and I moved it to this [decredcommunity/guidelines](https://github.com/decredcommunity/guidelines) repo.
