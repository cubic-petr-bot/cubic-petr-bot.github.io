---
title: About Petr³
layout: default
nav_order: 1
description: 
permalink: /
---

# About Petr³
{: .fs-9 .fw-700 }

<div style="display: flex; justify-content: center">
  <img src="/assets/images/cubic-petr-avatar-circle.png" style="width: 250px; height: 250px">
</div>

This bot was originally developed for the Rubik's Cube Club @ UCI Discord server!
{: .fs-6 .fw-300 }

<div style="display: flex; justify-content: center; gap: 10px;">
  <a href="https://discord.gg/2HnwhfksGa">
    <img src="https://img.icons8.com/?size=100&id=M725CLW4L7wE&format=png&color=000000" style="width: 50px; height: 50px; border-radius: 50%; background-color: #fecc07; padding: 10px;">
  </a>
  <a href="https://www.instagram.com/anteatercubeclub">
    <img src="https://img.icons8.com/?size=100&id=Xy10Jcu1L2Su&format=png&color=000000" style="width: 50px; height: 50px; border-radius: 50%; background-color: #fecc07; padding: 10px;">
  </a>
  <a href = "https://www.worldcubeassociation.org">
    <img src = "https://dropinblog.net/34242096/files/featured/Parents_Guide_to_WCA_World_Cube_Association_Competitions/wca_.svg" style="width: 50px; height: 50px; border-radius: 50%; background-color: #fecc07; padding: 10px;">
  </a> 
</div>

The primary function of Petr³ is facilitate seemless integration between the World Cube Association (WCA) website and Discord servers by allowing users to link their Discord accounts with their unique IDs, receive catered notifications about local speedcubing competitions based on location preference, and share their profiles with others. 

Petr³ is written in Python using the [discord.py](https://discordpy.readthedocs.io/en/stable/) library among other libraries including: 
* [Aiohttp](https://docs.aiohttp.org/en/stable/) to make asynchronous requests to the World Cube Assocation website and other relevant APIs
* [Aiosqlite](https://github.com/omnilib/aiosqlite) to store and retrieve information from a sqlite3 database asynchronously 
* [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/) to parse through HTML efficiently
* [Geopy](https://geopy.readthedocs.io/en/stable/) to calculate distances between a user-specified headquarters and local speedcubing competitions

Among these libraries, several APIs are utilized to retrieve up-to-date global data: 
* [World Cube Association's API v0](https://www.worldcubeassociation.org/help/api) 
* [Unofficial World Association API](https://wca-rest-api.robiningelbrecht.be)

# Inviting Petr³
{: .fs-9 .fw-700 }

To invite Petr³ to your own Discord server, follow the steps below. 
1. Click on the following link: 
2. Select the server you want to invite Petr³ to...
3. Complete the CAPTCHA and enjoy!

Alternatively, you can directly add Petr³ by clicking on its Discord profile and clicking + Add App!
{: .fs-6. fw-300}