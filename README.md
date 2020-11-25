# Project Name
> Ping Pong Score Keeper  

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Code Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
A score keeper created using HTML, CSS and JavaScript

## Screenshots
![Example screenshot](https://github.com/TarrMarr/pingPongScoreKeeper/blob/main/screenshot.JPG)

## Technologies
* HTML5
* CSS
* Bulma Library
* JavaScript

## Code Examples
Show examples of usage:
`function updateScores(player, opponent){
    if(!isGameOver){
        player.score += 1;
        if(player.score === winningScore){
            isGameOver = true;
            player.display.classList.add('winner');
            player.button.disabled = true;
            opponent.display.classList.add('loser');
            opponent.button.disabled = true;
        }
        player.display.textContent = player.score;
    }
};

function reset(){
    isGameOver = false;
    for(let p of[p1, p2]){
        p.score = 0;
        p.display.textContent = 0;
        p.display.classList.remove('winner', 'loser');
        p.button.disabled = false;
    }
};`

## Status
Project is: _finished_

## Inspiration
Created with help from Udemy's Web Developer Bootcamp with Colt Steele

## Contact
Created by TarrMarr(https://www.tarrynmarr.me) - feel free to contact me!
