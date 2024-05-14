---
layout: project
title: SCCL Chinese Dictionary
technologies:
  - Google Cloud Vision
  - Flask
  - Vue + Vuex
  - PWA
image: sccl-dictionary.png
link: https://gitlab.com/kaine119/sccl-dictionary/-/tree/master
year: 2018
---

An application for a project that the Singapore Centre for Chinese Learning (SCCL) approached our CCA teacher with. I don't remember exactly how it panned out, but after a few rounds of meeting with the group from SCCL, we worked on the application for a while, then got distracted by schoolwork. If you're reading this - sorry!

The application is by now very much broken; the site isn't hosted anywhere, and I think the dictionary database SCCL provided was eventually taken down. Still, it was quite an involved project. It involved a mobile-optimised frontend application written in Vue and included Vuex for state management (I was just learning about it and eager to try it out, much to the detriment of, uh, maintainability after several years), and a Flask backend that consumed the Google Cloud Vision API to recognise Chinese characters from pictures of (presumably) primary school textbooks that the end user would upload. It was also one of my first experiences with implementing a spec provided by a third party (the SCCL group).

I initially put it up on Heroku, then when we realised we needed Cloud Vision we decided to try host it on Google Cloud (Google App Cloud? whatever it was called back then). Then, when hosting bills shot up for reasons I can't remember, we moved to AWS. If I remember correctly, that was around the point where we had to start crunching for schoolwork, and put this in the background until eventually we forgot about it.

If I could do it again, I would've left behind more comprehensive documentation for someone else to potentially pick up the project in the future, and communicated more clearly that we wouldn't have time to follow up on the project. 
