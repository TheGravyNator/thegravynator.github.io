<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <head>
    <title>The Gauntlet; A Pokemon Challenge</title>
  </head>
  <body>
    <div class="sidebar">
        <a href="index.html">Home</a>
        <br>
        <a href="mira.html">Mira</a>
        <a href="sera.html">Sera</a>
        <a href="aqua.html">Aqua</a>
        <a href="mana.html">Mana</a>
        <a href="nova.html">Nova</a>
        <a href="hana.html">Hana</a>
        <br>
        <a href="changelog.html">Changelog</a>
    </div>
    <div class="main">
        <div class="header"><h1>The Gauntlet; A Pokemon Challenge</h1>
            <hr>
        </div>
        <div class="content">
            <p>The Gauntlet is a challenge within multiple Pokemon games, made up and executed by TheGravyNator. The essence of the challenge is to use pokemon from older generations (in my case Gen 3 and Gen 4 respectively), challenge every Elite Four in subsequent games (and challenge Red on Mt. Silver) while transferring them up to the modern Pokemon games. This results in a team of Pokemon that all bear a collection of Elite Four-related ribbons from all the games the Pokemon travelled through.</p>
            <br>
            <table class="team">
                <tr>
                    <th colspan="2">Check out the team:</th>
                </tr>
                <tr>
                    <td><a href="mira.html"></a></td>
                    <td>Mira The Dragonite</td>
                </tr>
                <tr>
                    <td><a href="sera.html"></a></td>
                    <td>Sera The Gardevoir</td>
                </tr>
                <tr>
                    <td><a href="aqua.html"></a></td>
                    <td>Aqua The Empoleon</td>
                </tr>
                <tr>
                    <td><a href="mana.html"></a></td>
                    <td>Mana The Espeon</td>
                </tr>
                <tr>
                    <td><a href="nova.html"></a></td>
                    <td>Nova The Weavile</td>
                </tr>
                <tr>
                    <td><a href="hana.html"></a></td>
                    <td>Hana The Roserade</td>
                </tr>
            </table>
        </div>
    </div>
  </body>
</template>

<style scoped>
.sidebar {
    height: 100%; /* Full-height: remove this if you want "auto" height */
    width: 200px; /* Set the width of the sidebar */
    position: fixed; /* Fixed Sidebar (stay in place on scroll) */
    z-index: 1; /* Stay on top */
    top: 0; /* Stay at the top */
    left: 0;
    background-color: black; /* Black */
    overflow-x: hidden; /* Disable horizontal scroll */
    padding-top: 20px;
    border-style: none solid none none;
    border-color: white;
}

.sidebar a {
    text-decoration: none;
    font-size: 25px;
    color: white;
    display: block;
    text-align: center;
}
  
  .sidebar a:hover {
    color: lightgrey;
  }

.main {
    margin-left: 200px; /* Same as the width of the sidebar */
    padding: 0px 10px;
}
  @media screen and (max-height: 450px) {
    .sidebar {padding-top: 15px;}
    .sidebar a {font-size: 18px;}
  }

  body {
    background-color: black;
}

h1 {
    color: white;
    display:flex;
    align-items: center;
    justify-content: center;
}

p {
    color: white;
}

#player {
    width: 200px;
    position: absolute;
    bottom: 20px;
}

table, th, td {
    color: white;
    text-align: center;
}

table {
    width: 100%;
}

.team {
    width: 25%;
    margin-left: auto;
    margin-right: auto;
}

img {
    padding: 10px;
}
</style>
