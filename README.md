// ==UserScript==
// @name         Campus funni
// @namespace    http://tampermonkey.net/
// @version      1.0
// @description  Campus funni packet gone wrong 3am
// @author       Lellex
// @match        campus.inkrement.no/Assignment2/Index/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    console.log(document.querySelector("h1").textContent = aNode.getAnswer()["key"]);
})();

let currentPage = location.href;

setInterval(function()
{
    if (currentPage != location.href)
    {
        currentPage = location.href;

        console.log(document.querySelector("h1").textContent = aNode.getAnswer()["key"]);
    }
}, 750);
