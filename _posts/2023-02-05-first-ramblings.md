---
title: "First Ramblings"
author: mathematicalconscience
date: 2023-02-05 15:38:00 +0100
categories: useless uninteresting
---

### 2023-02-05

This about the most complex workflow I have ever seen to turn a piece of markdown into a deployed website.
But at least it is now version controlled (which it would have been anyway, as I have almost everything that gets deployed somewhere in a git repo) and the publishing is automatic via a github workflow (which is nice I suppose).

After not having done any development in this environment for quite a bit, it was good to update my knowledge of some stuff (ssh keys, git workflows). A bit sad that this was mostly a tangent to a tangent to a tangent while I was _really_ working on some fast.ai stuff. 

Also, I have finally decided that I will work on liking VS Code. I think most of what I dislike is either configurable or just something that I will have to accept at some point. It is _not_ a decent mac app---but then, few apps are these days. It seems that even Apple itself has only produced software with crappy UX for the past 5 or so years, so who am I to blame MS that their cross-platform code editor does not behave exactly as I would like it to?

### Testing things

No idea how jekyll works or why there seems to be such a large gap between settin up a GitHub Page and getting an additional subpage to render.

Ok, it seems you are either just publishing a single markdown page _or_ you go all in using jekyll. I don't see any middle ground here.
My current mental model is that github pages is in essence a free (for private use) way to host a jekyll-based website. 

That's ok, I guess.

#### Objects

This is a page title object:
{{ page.title }}
It renders correctly, even if I do not include front matter in this markdown file.

