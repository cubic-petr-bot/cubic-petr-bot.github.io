---
layout: default
title: Setup
parent: Commands
nav_order: 1
nav_exclude: false
---

## Setup
{: .fs-9 .fw-700 }

Setup is simple with Petr³. Most commands are available for use upon it joining your Discord server. However, some extra steps are required for the server to receive notifications. 
{: .fs-6 .fw-300 }

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/sethq</h2>
  <div style="background-color: #255799; color: white; padding: 5px 10px; border-radius: 15px; display: flex; justify-content: center; align-items: center; text-align: center; width: auto;">
    address
  </div>
  <div style="background-color: #255799; color: white; padding: 5px 10px; border-radius: 15px; display: flex; justify-content: center; align-items: center; text-align: center; width: auto;">
    radius: optional
  </div>
</div>

<i> Set a location to base the notifications on. Use a public address, not a private one! </i>

* address: Name of a public location/place e.g. University of California, Irvine
* radius: Maximum distance, in km, from the specified address for a competition to be detected

Administrator permissions required.

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/notifications</h2>
  <div style="background-color: #255799; color: white; padding: 5px 10px; border-radius: 15px; display: flex; justify-content: center; align-items: center; text-align: center; width: auto;">
    competitions_channel_id: optional
  </div>
</div>

<i> Set the notifications settings for this server! </i>

* competitions_channel_id: The <a href="https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID">channel ID</a> the bot will send competitions notifications in. If not specified, it will be the channel in which the command is invoked.

Administrator permissions required.

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/hq</h2>
</div>

<i> Display the details of the HQ for this server! </i>