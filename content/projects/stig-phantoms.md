---
title: "STIG Phantoms"
date: 2021-06-22T22:38:17-07:00
draft: true
author: "Ryan Zimmerman"
tags: ["personal-project"]
showToc: false
description: "Website for Special Tactics Instructional Group"
cover:
    image: "/stig-phantoms.png"
    alt: "STIG Phantoms screenshot"
disableShare: true
---
[GitHub](https://github.com/zimmerry/stig-phantoms)

The website for the Special Tactics Instructional Group at Oregon State University
was built using Hugo, with the Airspace theme. 

It uses GitHub Actions to automatically build and deploy the site to my web server 
whenever a commit is pushed to the main branch, and it automatically builds and deploys
to a staging site when a commit is pushed to a pull request or any branch other than
main. 
