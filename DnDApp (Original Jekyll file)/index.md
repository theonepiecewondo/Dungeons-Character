---
layout: default
title: "Dungeons & Characters"
---

<html lang="eng-US">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta charset="utf-8">
    <title>Dungeons & Characters</title>
    <link rel="stylesheet" href="/assets/css/styles.css">
    <link rel="stylesheet" href="/assets/css/main.css">
<!-- Font Awesome -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
<!-- Google Fonts -->
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap">
<!-- Bootstrap core CSS -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet">
<!-- Material Design Bootstrap -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.18.0/css/mdb.min.css" rel="stylesheet">
<!-- JQuery -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<!-- Bootstrap tooltips -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.4/umd/popper.min.js"></script>
<!-- Bootstrap core JavaScript -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/js/bootstrap.min.js"></script>
<!-- MDB core JavaScript -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.18.0/js/mdb.min.js"></script>

</head>
<body>
    <main>
      <section class="header d-flex justify-content-center flex-column p-relative">
        <div>
            <img class="o-cover h-100 w-100" src="/assets/img/header.png" alt="header"/>
            <article class="container z-1 d-flex p-absolute p-center flex-column">
                <h1 class="text-white text-center animated bounceInDown">Dungeons and Characters</h1>
                <p class="text-white text-center align-self-center animated bounceInUp" style=" font-size: 25px; max-width: 660px">One of the most perfect and beautifully designed Character sheet organizer for Dungeons and Dragons 5<sup>th</sup> edition</p>
                <div class=" text-white align-self-center justify-content-center d-flex flex-row">
                    <img class="animated fadeInLeft" style="margin: 2.5%;width:300px" src="/assets/img/google-play-badge.png">
                    <img class="animated fadeInRight" style="margin:6%;width:88%"  src="/assets/img/apple_store.svg">
                </div>
          </article>
        </div>
      </section>
      <section class="main-body">
        <article class="main-page w-100 h-100">
        <p class="wow jello text-white text-center mx-auto pt-5" style="font-size: 60px; max-width: 600px; font-weight: 500;"> Characters Screen</p>
            <div class="d-flex flex-row justify-content-center">
                <p class="wow flipInX text-white align-self-center m-5" style="font-size: 30px; max-width: 400px;">The main screen holds an unlimited amount of characters, that allows for scrolling down the list. Swiping on a character from left to right allows you do delete a character.</p>
                <img class="wow fadeInRight m-5" style=" border-radius: 25px;width: 20%; height: 20%" src="/assets/img/main.png">
            </div>
        </article>
        <article class="new-character bg-primary w-100 h-100 p-5" style="">
            <p class="wow jello text-white text-center mx-auto pt-5" style="font-size: 60px; max-width: 600px; font-weight: 500;"> Create A Character</p>
            <div class="d-flex flex-row justify-content-center">
                <img class="wow fadeInLeft m-5" style=" border-radius: 25px;width: 20%; height: 20%" src="/assets/img/new-character.png">
                <img class="wow fadeInRight m-5" style=" border-radius: 25px;width: 20%; height: 20%" src="/assets/img/new-character2.png">
            </div>
        <p class="wow flipInX text-white mx-auto mt-5" style="font-size: 30px; max-width: 60%;">The character creation screen allows for users to input data about their character and have the information saved. After creation the page takes you back to the main screen showing all your characters, where you can then proceed to see your characters stats.</p>
        </article>
        <article class="stats bg-secondary w-100 h-100 p-5" style="">
            <p class="wow jello text-white text-center mx-auto pt-5" style="font-size: 60px; max-width: 600px; font-weight: 500;"> Character Stats</p>
            <div class="d-flex flex-row justify-content-center">
                <img class="wow fadeInLeft m-5" style=" border-radius: 25px;width: 20%; height: 20%" src="/assets/img/stats1.png">
                <img class="wow fadeInRight m-5" style=" border-radius: 25px;width: 20%; height: 20%" src="/assets/img/stats2.png">
            </div>
        <p class="wow slideInUp text-white mx-auto" style="font-size: 30px; max-width: 60%;">The main beef of the app. The stats page is nicely designed to allow user to edit there stats in real time, without navigating to another page to edit the information. The content updates immedietly on the screen. Everything is modible on this screen, when it comes to the numbers. The circle buttons can be tapped to provide the proficiency bonus to your skills. The skills can also be updated with your own custom number inputs.</p>
        </article>
      </section>
    </main>
    <script>
        $( document ).ready(function() {
            new WOW().init();
        }); 
    </script>
   
  </body>
</html>
