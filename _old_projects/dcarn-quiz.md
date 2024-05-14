---
layout: project
title: Quiz for Open House CCA booth
technologies:
  - Vue.js
  - TravisCI
image: dcarn-quiz.png
link: https://github.com/kaine119/dcarn17-quiz
year: 2017
---

This was a quick thing I came up with for my CCA's booth for D'Carn 2017, Dunman High's open house. It wasn't super relevant to our CCA &mdash; I didn't think so at the time either &mdash; and for a open house booth, it wasn't very fun either. But that's besides the point.

It's a hastily thrown together web thing written in Vue.js, using single file components. I think it was the first time I used them in a serious project, and I'm quite happy with how it turned out. I had set up a TravisCI build process for it too, so when you pushed to the source code repo on GitHub, it automatically ran the files through Webpack, took the build output, and threw it on the `gh-pages` branch, ready to be served to the outside world. The "push to `gh-pages`" step was a bit nasty; it made a new initial commit for every build, and force-pushed that new initial commit to GitHub. That's why, if you look at that branch, there's only one commit, despite the numerous Travis builds.