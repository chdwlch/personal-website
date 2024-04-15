---
title: "Projects"
description: ""
draft: false
---

## [SATS.GG](https://sats.gg)

https://github.com/satsgg/sats.gg

#### A nostr live streaming client

Originally based on the LNURL stack, sats.gg is now fully integrated into nostr and features pubkey based authentication, a chat room, zaps, and more.

I am currently in the process of rebuilding my live streaming backend infrastructure in a way that can automatically scale up and cover infrastructure costs per user.

## [Streambrah](https://streambrah.com)

https://github.com/satsgg/streambrah

#### A nostr live streaming companion

Streambrah is tool integrated into OBS that provides widgets and an interface to assist in managing kind 30311 live event notes. Each tool is a nostr client running in a browser context inside OBS.

Widgets:

-- Zap alerts

- Displays alerts on stream when viewers send zaps

-- YouTube

- Plays viewer submitted YouTube videos on stream

-- Pokemon

- A viewer controlled Pokemon WASM emulator
- Game inputs are added via chat messages and ordered by the amount of sats attached

-- Wavman

- A nostr music player that can dynamically add the artist as a participant in the live stream

Stream Manager

- Manages and publishes kind 30311 notes
- Integrated with Owncast to retrieve viewer count

I am currently working on a desktop version that is designed to be similar to the Twitch.tv dashboard.

## [Nostr Plays Pokemon](https://sats.gg/pokemon)

#### An experimental crowd controlled live stream

Nostr Plays Pokemon is a nostr spin on the original [Twitch Plays Pokemon](https://en.wikipedia.org/wiki/Twitch_Plays_Pok%C3%A9mon). It is a demonstration of the tools available in Streambrah and is viewable on sats.gg. The stream has been running nonstop for over three months and has been played by dozens of unique players.

## Bolt12 Human Readable Identifiers

https://github.com/ATLBitLab/zeus

I am activly working on implementing the [Human Readable Payment Identifiers BIP](https://github.com/bitcoin/bips/pull/1551) into the Zeus wallet.

These changes feature bolt12 payment integration and payment identifier registration inside the Zeus app. I have additionally worked on the backend for [twelve.cash](https://twelve.cash) - an open source web application that allows users to register bitcoin payment identifiers into DNS text records.

Work is ongoing to implement DNSSEC signature validation in Zeus.

## Satbox.tv (inactive)

#### A crowd controlled video playing live stream

https://github.com/satsgg/satbox

Satbox.tv was originally a wrapper UI over a stream that I ran on Twitch.tv. Viewers could purchase _credits_ that allowed them to add, continue, or bump up videos in a queue. The credit system was based on the LSAT protocol (now [L402](https://docs.lightning.engineering/the-lightning-network/l402)) and enabled users to interact with the application in near real time.

I've recently converted Satbox into a YouTube widget that is available for anyone to use in Streambrah.
