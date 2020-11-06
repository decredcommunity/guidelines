---
author: bee
published_utc: 2019-04-18
updated_utc: 2020-09-02
---

# Reddit moderator tips

Contents:

- [Tools](#tools)
- [Tips](#tips)

## Tools

Bookmark these links for quick access.

https://www.reddit.com/r/decred/about/modqueue/

Moderation queue shows posts and comments that were reported by users or automatically flagged by Reddit. Check it couple times a day.

https://www.reddit.com/r/decred/new/

This is simply all published posts newest first. Some spam bypasses all filters and gets published. Sorting by 'new' allows to quickly notice it on top.

https://www.reddit.com/r/decred/about/log/

Log of all mod activity. Only visible to mods. Check it to catch and undo any false positives by the AutoModerator, or simply see what other mods did while you were away.

Public viewers of mod activity:

- https://moddit.ffff00.news/r/decred
- https://modlogs.fyi/r/decred
- https://snew.notabug.io/r/decred/about/log/

Another public log of all mod activity.

https://snew.notabug.io/r/decred/new/

Renders r/decred like Reddit but also shows deleted posts in red. The app is mirrored at [politicbot.github.io](https://politicbot.github.io/r/decred/new/) and [r.go1dfish.me](https://r.go1dfish.me/r/decred/new). List of instances is [here](https://github.com/snew/snew/wiki/Snew-Instances).

https://www.reddit.com/r/decred/comments/

Shows all comments by all users for a given subreddit, sorted newest first. Useful to catch spam and abuse in comments that bypassed other filters.

https://www.reddit.com/r/decred/about/spam/

Content removed as spam.

https://www.reddit.com/report

Report scammers and spammers to Reddit via this link. If it doesn't work try https://old.reddit.com/report

https://www.reddit.com/r/decred/about/rules/

Rules of r/decred. When you take mod action, try to reference which rule was violated. If you see a useful change to the rules, discuss it with other mods.

https://www.reddit.com/message/moderator/unread/

Mod mail, old style.

https://mod.reddit.com/mail/all

Mod mail, new style.

There are aggregate versions of some of these pages that list data across all subreddits you moderate. To get them replace `r/decred` with `r/mod` in the URL, e.g. https://www.reddit.com/r/mod/about/modqueue/ or https://www.reddit.com/r/mod/about/log/ .

Many of the above listings are available as JSON feeds if you add `.json` at the end of the URL.

Finally, many of the above listings are available via direct private JSON and RSS links that work without cookies or other auth. You can enable them in [preferences](https://www.reddit.com/prefs) and get the links on the [RSS feeds](https://www.reddit.com/prefs/feeds/) tab. Use and share at your own risk.

### Short links

Reddit has direct links to posts and comments. Full links can be quite long, but it is possible to shorten them without relying on third party link shortening services (that may track users).

To shorten a link, learn to find post ID and comment ID in the full link. For example consider this direct link to a comment:

    https://www.reddit.com/r/decred/comments/jigugp/how_to_get_on_dcrdex/gad4lce/

here `jigugp` is a post ID and `gad4lce` is a comment ID. Knowing that, post's short link can be made using Reddit's own shortening service `redd.it`:

    https://redd.it/jigugp

or if you don't want to rely on that service:

    https://www.reddit.com/comments/jigugp

It is not possible to create short links to comments with the `redd.it` service, so the only way to shorten a comment link is to extend the previous link with the comment ID:

    https://www.reddit.com/comments/jigugp//gad4lce/

Two slashes (`//`) are necessary to retain link structure expected by Reddit. If that looks weird you can add something in between:

    https://www.reddit.com/comments/jigugp/_/gad4lce/

underscore (`_`) commonly means "this is just a placeholder character required by the syntax but unused otherwise", but anything else can reside between the slashes, like a hidden message:

    https://www.reddit.com/comments/jigugp/thankyou/gad4lce/

## Tips

Typical mod run:

- check modqueue for new things to process, keep the modqueue clean
- check new posts, remove spam that bypassed all filters
- check modlog for AutoModerator false positives
- check comments for spam

Avoid content removal as much as possible. Be ready to publicly comment on every case of removal.

When not sure if the submitter is spammer, check submissions and comments in his profile. Some heuristics that increase the "spammer score":

- if the user submits to a _very_ large and diverse set of subreddits
- if the user only submits posts but never comments (check comments tab)
- if the user does comment but all comments are short and useless (e.g. "Yeah!")
- if the post is cross-posted to a bunch of subreddits (check Duplicates tab on the post)

If you see an important or controversial discussion that has the risk of being deleted, save the `old.reddit.com` version of the page to [web.archive.org](https://web.archive.org) or [archive.today](https://archive.today) (there are browser extensions to do it quickly). We had few incidents when thoughtful discussion was delisted from r/decred by the submitter removing his post. The counter-measure after such "attention attack" is to submit the link to deleted thread to r/decred (known as "resurrection").

Add known users to friends by pressing `+friends` on their user page. This allows to quickly see their comments. Then you can also follow their content across all subreddits at https://www.reddit.com/r/friends/

If you see a new request in Reddit Moderator Mail (modmail) shown as a green shield icon in the top right, answer it or ask other mods or marketing people.

When in doubt, ask other mods.
