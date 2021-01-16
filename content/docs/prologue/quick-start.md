---
title: Specifications
description: One page summary of how to start a new Doks project.
lead: One page summary of how to start a new Doks project.
date: '2020-11-16T13:59:39+01:00'
lastmod: '2020-11-16T13:59:39+01:00'
draft: false
images: []
menu:
  docs:
    parent: prologue
weight: 110
toc: true
---
## Specifications

Initial connections are normally p2p, with Lunar Chat we can ensure Hop 2 Hop, meaning that when you connect to a call, yo do not connect to that user but instead the server which hosts Lunar chat. Or in the case of purchasing a custom license, your own server instance, or even local server. L chat can be setup on a local network, or deployed to the cloud and accessible globally. Hop 2 hop ensures that, only the security of the server/host, and those maintaining it are in question regards to who may view calls and potential info. By enabling End to End encryption, even if the host server or local network were to be compromised, any information pertaining calls would be undecipherable

## Feature Outline

##### Two-Way Audio & Video

##### Audio Calls

##### Muting

##### Video Conferencing

##### Screenshare

##### Page embed\*, Youtube sharing\*, Session recording\*

##### Slideshow, and presentation media embed\*

##### Attendee Management - Set Password, enable lobby, pay gate\*, and  Set Usernames\*

##### Meeting Initiation, share and join management

##### Private Text Chat

##### Instant Messaging

#####

##### \*Available at additional cost to business users, included in certain customisation packages, see pricing.lchat.co.uk

## In-Depth Specifications

{{< btn-copy text="git clone https://github.com/h-enk/doks.git my-doks-site" >}}

```bash
git clone https://github.com/h-enk/doks.git my-doks-site
```

## Technical Limits

{{< btn-copy text="cd my-doks-site" >}}

```bash
cd my-doks-site
```

## Test Results - Performance

{{< btn-copy text="npm install" >}}

```bash
npm install
```

## Test Results - Security

{{< btn-copy text="npm run start" >}}

```bash
npm run start
```

## Comparison with zoom

Doks will start the Hugo development webserver accessible by default at `http://localhost:1313`. Saved changes will live reload in the browser.

## Other commands

Doks comes with commands for common tasks. \[Commands →]\({{< ref "commands" >}})
