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

Initial connections are normally p2p, with Lunar Chat we can ensure Hop 2 Hop, meaning that when you connect to a call, yo do not connect to that user but instead the server which hosts Lunar chat. Or in the case of purchasing a custom license, your own server instance, or even local server. L chat can be setup on a local network, or deployed to the cloud and accessible globally. Hop 2 hop ensures that, only the security of the server/host, and those maintaining it are in question regards to who may view calls and potential info. By enabling End to End encryption, even if the host server or local network were to be compromised, any information pertaining calls would be undecipherable.

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
P2P mode is only used for 1-to-1 meetings. In this case, audio and video are encrypted using DTLS-SRTP all the way from the sender to the receiver, even if they traverse network components like TURN servers.
```

In the case of multiparty meetings, all audio and video traffic is still encrypted on the network (again, using DTLS-SRTP). Packets are decrypted while traversing Jitsi Videobridge; however, they are never stored in any persistent storage and only live in memory while being routed to othe participants in the meeting.

Comprehensive meetings features in every plan

Features	Description	Jitsi as a Service

Video Experiences

Audio sharing	Users can share system audio in a meeting from a device or browser tab	✓

Bandwidth controls	Users can monitor their connectivity quality and adjust their video bandidth	✓

Configure, enable and disable features	Configure, enable, and disable features to build the experience you want end users to have	✓

Controller mode	The ability for any participant (not just the host) to mute, control volume or remove other participants in meeting	✓

Dominant speaker indication	Indicates who is the dominant speaker at any given point in time	✓

Group chat	Send messages to every video meeting participant	✓

HD Audio	Opus Codec	✓

HD Video	Ability to support 720p video	✓

In-meeting connection indications	Show information about connections status, such as bitrate, packet loss, resolution, frame rate and estimated bandwidth	✓

Phone access to meetings	Call into meetings using 80+ dial in number options (11 toll-free) for 58 countries	✓

Private chat	Send private messages to individuals in a video meeting	✓

Push to talk mode	Mode in which all speakers stay muted unless they press the spacebar key to speak	✓

Raise your hand	Participants can discreetly indicate they have something to say without interrupting the current speaker	✓

Remote desktop control through electron integrations	Control the mouse and keyboard movements of another user remotely through electron integrations	✓

Screen sharing	Share your computer screen and choose which applications or monitors to display	✓

Smart layout	Dynamically control app layout and display based on audio activity. Automatically or manually switch between tile and stage view, automatically focus on any participant and manage screen sharing	✓

Your brand experience	Brand the experience with your company information. No 8x8 or Jitsi branding shown anywhere in the app	✓

YouTube Video Sharing	Users can share a YouTube video for everyone in the conference to see	✓

Meetings as a Service Platform

End-to-End Encryption for video meetings	True end to end encryption even with videobridge for desktop video meetings	✓

GDPR requirements for data processors	GDPR compliant for data processors	✓

Highly available massively scaled global infrastructure	Real-time automatic scaling of compute capacity to ensure the right capacity is always available	✓

HIPAA Compatible	8x8 is HIPAA compatible and can provide a BAA. It is incumbent upon users to operate the technology in a HIPAA compliant manner.	✓

Industry-leading Service Levels	99.99% Platform Uptime SLAs	✓

Localization of interfaces	Record the audio, video, and screen share from a meeting. Save it to reference later or to send to those who could not attend.	✓

Open and industry standard encryption	Encryption using DTLS-SRTP to secure video	✓

Secure passcodes	The ability to set a passcodes to provide an additional layer of security	✓

Webhooks	Configure, enable, and disable features to build the experience you want end users to have

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
The Most secure way to operate our service is too disable streaming and recording, this is done by default on public access Lchat.co.uk then selecting in the settings 'Enable End to End encryption'
```

## Comparison with zoom

Zoom currently offer no means of End to End encryption.

## Pricing

Free to the public (hopefully forever), Available from just £50pm for small business, £100pm for Larger business. These are just example figures, please see our pricing page to customise your service and receive a personalised quotation.
