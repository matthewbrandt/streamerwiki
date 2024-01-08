---
sidebar_position: 1
tags: ["Viewer"]
---

# Video Player Settings
Options and settings for the video player.

## Stream Quality & Transcoding
Opening the stream settings allows you to adjust the quality of the stream *downwards* from the original broadcast, provided that the stream is currently being transcoded. Transcoding is only guaranteed for partnered Twitch streamers and is "luck of the draw" for other creators. Changing the [ingestion server](/docs/streaming_non_mobile/ingest-servers.md) can sometimes help with streams not receiving transcoding.

The transcoding options will vary dependong on the [source quality](/docs/streaming_non_mobile/video-settings.md), but generally the following options will be available:
- 1080p60
- 1080p
- 720p
- 480p
- 360p
- 160p

## Event Notifications
When Twitch chat is [collapsed](/docs/chat/chat-settings.md#collapse-chat), notifications for events such as hype trains, polls and predictions will appear as an overlay on the video player (desktop only). 

## Closed Captions
If the stream is sending closed captions to Twitch, you can turn them on or off in the settings menu. 
**N.B.** This function only works for native closed captions that are sent to Twitch using the appropriate technical means.

## Video Speed
On VODs you are able to adjust the playback speed:
- 0.25x
- 0.5x
- 0.75x
- 1x 
- 1.25x
- 1.5x
- 2x

## Popout Player
This option will pop out the video player into it's own window, pausing the broadcast in the video player. Closing that window will **not** automatically resume the broadcast in the video player.

## View Keyboard Shortcuts
This menu item will display an overlay with keyboard shortcuts for the video player.

## Notify Track Changes in Theatre Mode (Deprecated)
Activating this will show when the music track changes if the stream uses Twitch Soundtrack. As Twitch Soundtrack was [deprecated](https://help.twitch.tv/s/article/music-options-for-streamers) on July 17th, 2023 this toggle effectively does nothing.

## Audio Only
On the Twitch official mobile app, you can toggle the video broadcast to be audio-only. An overlay will appear over the video player when this is activated.

## Report Playback Issue
Twitch gives you the opportunity to report issues with the video player in this single-step form.

## Advanced Toggles
Under the advanced settings option you can find additional options.

### Low Latency
This activates the lowest latency possible from your device to the broadcaster.

### Mini Player
Activating this option enables a Picture-in-Picture version of the player to appear on the bottom left when navigating through browse and category pages.

### Video & Ad Stats
These two toggles activate a semi-transparent overlay on the video player with some detailed statistics about the broadcast and ads.

---
Anything **unclear** on this page? [Create an issue on Github](https://github.com/matthewbrandt/streamerwiki/issues/new)