Really, nothing to see here. Toying with some ideas discussed in 
[this reddit thread](https://www.reddit.com/r/haskell/comments/83qcak/haskell_needs_better_libraries_a_proposal/) and it's 
possible a GitHub organization is a satisfactory forum for what I'm trying to build. Problem is, I'm not quite sure what I'm 
trying to build yet. So, really, nothing to see here. Just me talking to myself. La la la. Please have a look around the issue
tracker wherein I talk to myself some more.

---

Update 3/15

Messy README draft & miscellaneous thoughts

---

Goals (of this readme):

- Purpose of this repo?

- Why none of these forums suffice (maybe this doesn't need to be said): Reddit, Twitter, IRC, Slack, Discourse (if we had one)

- What is out of scope? How is this enforced? (If at all?)

- Why wouldn't I use project's own issue tracker?

- What _is_ an issue supposed to be?
  - Explicit API improvement proposal
  - Snippet that seems indicative of an API wart (but no concrete proposal)
  - What else?

Rules I really want to enforce (but am open to discussion):

1. No meta comments
  - GitHub issues are linear and comments cannot be deleted or collapsed. Meta comments (including the meta comment "meta comments are disallowed") should therefore be disallowed to keep discussion as on-track as possible. We need to find the right place to make meta-comments, though (unfortunately GitHub doesn't have private messaging).

2. No thumbs-down emoji. I'm open to being convinced on this one, I guess, but every time I've seen someone use this emoji it seems totally toxic, unprofessional, and unnecessary. If you have a disagreement, just say so in a comment. Receiving a drive-by thumbs-down also feels really bad.
  - Thumbs-up, on the other hand, seems OK. It's a lightweight way of expressing agreement without spamming the thread. (Yet there still exists the problematic tendency to view, of two contradictory comments, the one with fewer thumbs-up emojis as being objectively wrong somehow. Maybe more thinking required here...)
  
I think that's where I stop with rules/guidelines, I'm not totally sure. I don't want to be captain policeman of the internet or anything.

Some open questions:

- How "big" should an issue be?
  - My first instinct is to just have no rule or guidelines here. If someone wants to open an issue to discuss _all_ of library X, they can do so. Or, if someone wants to only discuss one tiny helper function tucked in some obscure module, that's fine too.
  - Issue duplication seems like it would easily resolve itself, so again, no need for guidelines here. For example, if I open an issue to discuss the design of `flabby-bits`, and someone in the comment section informs me there's already a discussion underway, I would likely just close my issue.

- Issue closing is interesting. If a proposal is made and actually implemented later in a library, success! Clearly the issue can be closed. But what about:
  - It becomes known that the proposed API rejiggering will _not_ be accepted into the library proper (because the author says so). What becomes of the issue then? If closed, it will fade away. That the author has vetoed some changes is still relevant information to the future direction of the library.
  
Another random thought:

Ed Kmett made an A++ comment on the original reddit thread about the pain he has endured due to abstract, unexposed types. This repo seems like a good place to host broader community guidelines that are (more or less) not up for debate (at least not nearly to the degree that subjective taste in API is). But is it that place? Why or why not?

And another random thought:

This is just issues, but GitHub gives us

- A wiki
- A project board
- A git repo

Should we use these? (First instinct: wiki & project board seem like shit features to take advantage of, but the file system is interesting. Bunch of static markdown files are easily clicked through in the GitHub UI.)

And another random thought:

It would be _awesome_ to have a convenient way of generating haddocks for a library's API under discussion. Unfortunately I have no idea how that might work in a lightweight and automated fashion.
