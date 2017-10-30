// ==UserScript==
// @name         Initium Maze Guide 2.0
// @namespace    http://tampermonkey.net/
// @version      2.0
// @description  Makes mazes in initium easy to use.
// @author       @evanosity
// @match        https://www.playinitium.com/main.jsp#
// @include      *playinitium.com/*
// @grant        none
// ==/UserScript==
function makeGuide(){
    //Tunnel Climb guide - made by MGO
    $('a[onclick="doGoto(event, 5696774480068608)"]').text('A <-> B');
    $('a[onclick="doGoto(event, 6536345828720640)"]').text('B <-> J');
    $('a[onclick="doGoto(event, 5833594958249984)"]').text('C <-> J');
    $('a[onclick="doGoto(event, 5381765237571584)"]').text('B <-> C');
    $('a[onclick="doGoto(event, 5117769267806208)"]').text('B <-> F');
    $('a[onclick="doGoto(event, 6259724433489920)"]').text('G <-> F');
    $('a[onclick="doGoto(event, 5717070482243584)"]').text('C <-> G');
    $('a[onclick="doGoto(event, 4908753375723520)"]').text('D <-> K');
    $('a[onclick="doGoto(event, 4704814671855616)"]').text('D <-> E');
    $('a[onclick="doGoto(event, 6726182041026560)"]').text('C <-> E');
    $('a[onclick="doGoto(event, 6382356621426688)"]').text('E <-> F');
    $('a[onclick="doGoto(event, 6392315039973376)"]').text('F <-> I');
    $('a[onclick="doGoto(event, 4985939407405056)"]').text('E <-> I');
    $('a[onclick="doGoto(event, 6615196730654720)"]').text('H <-> I');
    $('a[onclick="doGoto(event, 5671617816428544)"]').text('G <-> H');
    $('a[onclick="doGoto(event, 6631864156553216)"]').text('A <-> H');

    //Kujir/Lizardfolk guide
    $('a[onclick="doGoto(event, 5362167264051200)"]').text('Lizardfolk 1 <-> Kujir 5');
    $('a[onclick="doGoto(event, 6451902136975360)"]').text('Lizardfolk 1 <-> Lizardfolk 3');
    $('a[onclick="doGoto(event, 5066577749737472)"]').text('Lizardfolk 1 <-> Lizardfolk 2');
    $('a[onclick="doGoto(event, 6650262248751104)"]').text('Lizardfolk 2 <-> Kujir 5');
    $('a[onclick="doGoto(event, 4939908963631104)"]').text('Kujir 5 <-> Kujir 6');
    $('a[onclick="doGoto(event, 4586126132117504)"]').text('Kujir 4 <-> Kujir 5');
    $('a[onclick="doGoto(event, 5189636481613824)"]').text('Kujir 3 <-> Kujir 4');
    $('a[onclick="doGoto(event, 6197183330123776)"]').text('Kujir 3 <-> Kujir 2');
    $('a[onclick="doGoto(event, 6488021335539712)"]').text('Kujir 2 <-> Kujir 4');
    $('a[onclick="doGoto(event, 4662656677969920)"]').text('Kujir 2 <-> Kujir 1');
    $('a[onclick="doGoto(event, 4810025327394816)"]').text('Kujir 3 <-> Kujir 1');

    //Xaruk Forest Guide
    $('a[onclick="doGoto(event, 5141295400222720)"]').text('Forest 1 <-> Forest 2');
    $('a[onclick="doGoto(event, 6368227970252800)"]').text('Forest 2 <-> Forest 3');
    $('a[onclick="doGoto(event, 4522699816960000)"]').text('Forest 3 --> Forest 4');
    $('a[onclick="doGoto(event, 6714772976566272)"]').text('Forest 4 <-> Forest 5');
    $('a[onclick="doGoto(event, 5360502947708928)"]').text('Forest 4 --> Forest 6');
    $('a[onclick="doGoto(event, 5926266507362304)"]').text('Forest 6 --> Forest 2');
    $('a[onclick="doGoto(event, 6086377854992384)"]').text('Forest 6 --> Forest 7');
    $('a[onclick="doGoto(event, 5382690413215744)"]').text('Forest 7 --> Forest 4');
    $('a[onclick="doGoto(event, 4817053689315328)"]').text('Forest 7 --> Forest 2');

    //Eastern Desert Guide

    $('a[onclick="doGoto(event, 4773917299310592)"]').text('HP Desert <-> Desert 1');
    $('a[onclick="doGoto(event, 6368780121800704)"]').text('HP Desert <-> Desert 2');
    $('a[onclick="doGoto(event, 4907575339384832)"]').text('HP Desert <-> Desert 2');
    $('a[onclick="doGoto(event, 4810476732022784)"]').text('HP Desert <-> Desert 2');
    $('a[onclick="doGoto(event, 6422790677725184)"]').text('HP Desert <-> Desert 3');
    $('a[onclick="doGoto(event, 6558175831523328)"]').text('Desert 1 <-> Desert 3');
    $('a[onclick="doGoto(event, 4872389088247808)"]').text('Desert 1 <-> Desert 1A');
    $('a[onclick="doGoto(event, 4669739243667456)"]').text('Desert 2 <-> Desert 3');
    $('a[onclick="doGoto(event, 6122954313170944)"]').text('Desert 1 <-> Desert 2');



    //Strange Empty Room Guide
}
$(document).ready(function() {
    $('body').append('<input type="button" value="Reset Maze Paths" id="mazereset-button">');
    $("#mazereset-button").css("position", "fixed").css("top", 110).css("left", 0).css("zIndex", 10000000000);
    document.getElementById("mazereset-button").addEventListener("click", makeGuide);
    //setInterval(main,700);
});
