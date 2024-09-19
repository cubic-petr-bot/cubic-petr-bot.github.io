---
layout: default
title: Discord to WCA
parent: Commands
nav_order: 3
nav_exclude: false
---

## Discord to WCA
{: .fs-9 .fw-700 }

Petr³ can link any WCA ID to each user and remember it globally across all Discord servers. 
{: .fs-6 .fw-300 }

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/link</h2>
  <div style="background-color: #255799; color: white; padding: 5px 10px; border-radius: 15px; display: flex; justify-content: center; align-items: center; text-align: center; width: auto;">
    query
  </div>
</div>

<i> Starts the linking process for the invoking Discord user.</i>

* query: The search query i.e. Peter Anteater, 2024PETE01

DMs must be open as Petr³ will generate and send a verification code directly, unique and private to each user.

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/verify</h2>
  <div style="background-color: #255799; color: white; padding: 5px 10px; border-radius: 15px; display: flex; justify-content: center; align-items: center; text-align: center; width: auto;">
    code
  </div>
</div>

<i> Verifies a link from a provided verification code.</i>

* code: The verification code provided by Petr³.

<div style="display: flex; align-items: center; gap: 10px;">
  <h2 style="margin: 0;">/unlink</h2>
</div>

<i> Unlinks the corresponding WCA ID of the invoking Discord user.</i>
