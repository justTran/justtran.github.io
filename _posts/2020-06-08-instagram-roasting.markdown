---
layout: post
title:  "Instagram Roasting"
date:   2020-06-08 12:47:03 -0400
categories: projects
---

This project idea formed while wathcing a [Will Kwan][wk] video on how an AI generated beautiful people. His first problem was to predict how popular a photo can be. He eneded up finding a [GitHub Repo][iip] which included a model to predict the popularity of an photo you give it. Using this model, I thought it would be funny to upload the worst scoring photo to Instagram.

This was written in Python. The libraries used for all of this to function are:
- Selenium (For emulating a mobile device since Instagram changed their API and there's no Python packages avaliable for it at the time)
- [Intrinsic Image Popularity][iip]
- tkinter

Originally was inteded to post the worst scoring photo and give a rather vulgar description. However, I have since begun rethinking how to repurpose it, and possibly just use it for photography purposes. Most likely using the model to find the best three photos in a directory and post their scores. You can check it out [here!][repo]

![sample image](./img/iip.png)

[repo]: https://github.com/justTran/Instagram-Roast
[wk]: https://www.youtube.com/watch?v=pctzpu_wJyE
[iip]: https://github.com/dingkeyan93/Intrinsic-Image-Popularity
