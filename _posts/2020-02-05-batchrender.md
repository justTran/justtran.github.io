---
layout: post
title:  "Batch Renderer: Queue multiple projects for rendering while you're away!"
date:   2019-12-25 12:47:03 -0400
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
                <p>This project idea formed because I used to run overnight renders using Sony Vegas 14.</p> 
                <p>Sometimes, I would have multiple projects to render. Instead of manually doing it, I wrote a small script to render all project files in a given directory and shut down your PC. This originally measures CPU utilization and makes a decision based on a certain utilization threshold. I may revisit this project in the future, as it manipulates cursor placement instead of active windows.</p> 
                <p>You can check it out <a href="https://github.com/justTran/batchrender">here!</a></p>
                <img src="/img/vegas.png" style='width:100%'>
            </section>
        </main>
    </body>
</html>
