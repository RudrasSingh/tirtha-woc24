# Project Tirtha - Winter of Code 2024

## Brief Description

-This contribution was part of Winter of Code 2024 and I was working on this Project Tritha.
My part was that Tirtha was using Sign in with Google, which adds a Google-controlled
button to the Tirtha website, along with a handful of their scripts to allow
people to authenticate on Tirtha. However, those scripts send periodic logging
requests to google servers. The same is true for most other identity providers
(IdPs) like Google. Since we want the experience on the website to be
frictionless, we have to support the more popular IdPs, including Google, but we
can try and minimize the amount of logging they do.

## Issue & Pull Request

- [Link to Issue](https://github.com/smlab-niser/tirtha-public/issues/34)
- [Link to Pull Request](https://github.com/smlab-niser/tirtha-public/pull/44)

## Changes Made

- During the coding, I had to make some changes in the base python file which was handling the previous Sign in with Google. I used Authlib's Oauth provider to handle the sign in and storing the data in session.
  Also a new button was added in the homepage's contribution section.

## Challenges Faced

- Initially, the major challenge faced was in finding the best alternative for the sign in with google, I had searched over the internet for options and came accross very few them (reason being the popularity and ease of use of Google) and those were also sending a lot of tracking requests. At the end after looking over youtube and with the help of my mentor we finally used Authlib for Django as the final and best option.

## My Socials

- [Github](https://github.com/RudrasSingh)
- [LinkedIn](www.linkedin.com/in/atulsinghc)
- [Twitter](https://twitter.com/atul_singh001)
