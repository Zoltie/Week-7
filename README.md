# Project 7 - WordPress Pentesting
Week 7 Wordpress pentesting
Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

1. Cross Site Scripting in comment
  - [ ] Summary: When commenting on a post or page, you are allowed to insert html tags. You are also allowed to insert <script> tags as well as javascript and the page will run the javascript. This means that an attacker can use the document.cookie command and send the information to his own database, compromising the Wordpress accounts of anyone who loads the page with the infected comment.
    - Vulnerability types: Reflective Cross Site Scripting
    - Tested in version: Wordpress 4.2
    - Fixed in version: Wordpress 4.6
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Add a comment on one of the 
  - [ ] Affected source code:
