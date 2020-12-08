---
layout: post
title:  "Instagram Roasting: Get your pictures scored and posted to Instagram with a self-depricating caption!"
date:   2020-06-08 12:47:03 -0400
categories: projects
---
<html lang="en">
    <head>        
        <script src="https://code.jquery.com/jquery-1.10.2.js"></script>
        <link rel="stylesheet" href="/css/styles.css">
    </head>
    <body>
        <main role="main">
            <header role="banner">
                <section id="navi"></section>
                <script>
                    $(function(){
                      $("#navi").load("../../../../../nav.html");
                    });
                </script>
            </header>
            <section class="post">
            <p>This project idea formed while watching a <a href="https://www.youtube.com/watch?v=pctzpu_wJyE">Will Kwan</a> video on how an AI generated beautiful people. His first problem was to predict how popular a photo can be. </p>
            <p>He ended up finding a <a href="https://github.com/dingkeyan93/Intrinsic-Image-Popularity"> GitHub Repo</a> which included a model to predict the popularity of a photo given. Using this model, I thought it would be funny to upload the worst scoring photo to Instagram. </p>
            <p>This was written in Python. The main things I learned from this project are:</p>
            <ul>
                <li>Learning how Machine Learning models work</li>
                <li>Learning about the foundations for doing some machine learning algorithms</li>
                <li>Learning how to use Selenium more</li>
            </ul>
            <p>The project was originally intended to post the worst scoring photo and give a rather <em>vulgar</em> description.</p> 
            <p>However, I have since begun rethinking how to repurpose it, and possibly just use it for photography purposes.</p>
            <p><strong>Most likely using the model to find the best three photos in a directory and post their scores.</strong></p> 
            <p>You can check it out <a href="https://github.com/justTran/Instagram-Roast">here!</a></p>
            <img src='/img/iip.png' style='width:100%'>
            </section>
        </main>
    </body>
</html>
