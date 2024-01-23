---
sidebar_position: 4
tags: ["Creator", "Viewer"]
---

# Advertisement
Details about advertisements (ads) on streams, as well as channel pages.

## Managing Ads as a Creator
### Ad Types
- Preroll: a video ad will play when a viewer opens a Twitch video player, of either a livestream or VOD. The ad(s) are unskippable and can last up to 3 minutes.
- Midroll: a video ad will play when a viewer is already watching a Twitch video player, of either a livestream or a VOD. The ad(s) are unskippable and can last up to 3 minutes. The timing of mid-roll ads varies wildly between livestreams and VODs.
- Display: image ad(s) will be shown on any Twitch browse page (like the homepage or category pages), channel page, video player or chat areas. They can be shown in lots of different types of formats. See [Advertisement Products](/docs/monetisation/advertisement#advertisement-products) for more details.

### Ad Scheduling & Formats
There are various settings creators can use (in the creator dashboard) to manage ads on their channel.

#### Ad Scheduler
A toggle is available that can turn on or off the Ad Scheduler, aka Ads Manager. 
More information about the Ad Scheduler can be found [on Twitch](https://help.twitch.tv/s/article/ads-manager).

- When the toggle is "on" the Ads Manager will run ads automatically according to the defined schedule.
- When the toggle is "off" Twitch will independently decide when to run ads for users on a livestream. This can result in different users receiving different ads at different times.

**N.B.: If you toggle the setting off and on again during a live stream, the current timer will be reset and the schedule will resume again, by playing ads according to the defined schedule.**

The Ads Manager (i.e. Ads Scheduler) allows the creator to determine how often and how long advertisements are run on the livestream, automatically. The following settings are possible:
- Ad Minutes per Hour: Total minutes of ads to show viewers every hour.
    - Range: 0.5-14 in 0.5 increments; 15, 15.5, 16, 16.5, 17, 18, 18.5, 19.5, 20, 21, 21.5, 22.5 
- Automatic Ad Length & Frequency: Allow Ads Manager to adjust ad schedule settings based on your ad minutes per hour and available ads. This overrides the "Ad Length / Frequency" and "Start Delay" options.
- Ad Length / Frequency: Based on the selected ad minutes per hour, how often ads will be run. *If the "Ad Minutes per Hour" is set to 19.5 or above, the option "3 mins / 8 mins" is set. If it is set to less than 1 minute, "0.5 / 60 minutes" is set.*
    - Range: Various durations of X mins / Y mins i.e. X minutes of ads every Y minutes
- Start Delay: This is how long Ads Manager will wait after the broadcast starts before starting to run scheduled midroll ads. This setting ignores whether preroll ads are disabled or not - for the given start delay, preroll ads will be served.
    - Range: 1 - 30 minutes
- Auto Snooze Ads: When enabled, will automatically [snooze](/docs/monetisation/advertisement#streamer-ads-manager) for more details.) upcoming ad breaks during "high-engagement moments" in the livestream. Twitch identifies these moments independently according to criteria that is unknown.
- Ad Notifcations: Creators can optionally activate various notifications for upcoming ad breaks (midrolls). 
    - Before ad starts: Off, 1, 3, 5, 10, 15, 20 minutes
    - Ad Notifications in chat (only visible to broadcaster): On/Off
    - Ad Notifications in chat for mods (only visible to mods): On/Off

#### Streamer Ads Manager
In order to monitor the currently running schedule, Twitch offers a panel (which can also be added to streaming software like OBS). It has 2 functions:
- Snooze: delays the upcoming ad and schedule by 5 minutes. Maximum 3 snoozes can be held at a time.
> *Fact Check Required: Snoozes are rewarded every 60 minutes of livestreaming*.
- Run Xm Ad: will immediately start an ad for the specified duration. The duration is taken from the Ads Scheduler "Ad Minutes per Hour" setting.

#### Preroll Ads
A toggle option is available to enable or disable prerolls. Depending on the other options set in the creator dashboard, the results of this toggle can be unexpected:
- If prerolls are **enabled**, viewers will be served prerolls independently and outside the creator's control, regardless of the setting of the Ads Manager
- If prerolls are **disabled** and the Ads Manager is **enabled**, viewers will be not be served prerolls, unless they are entering the stream during the Start Delay window (see above) or sufficient midrolls have not been run to disable prerolls
- If prerolls are **disabled** and the Ads Manager is **disabled**, viewers may be served prerolls anyway under certain circumstances, which are partially outside the creator's control (i.e. not running sufficent midrolls manually, without the scheduler)

Preroll Notifications: The creator can optionally see a message in Stream Manager when preroll ads are enabled or disabled (based on ads running on the livestream).

#### Stream Display Ads
The creator can toggle Stream Display Ads on or off. See [Advertisement Products](/docs/monetisation/advertisement#advertisement-products) for more details.

### Ad Revenue
The default Net Ad Revenue Share will be 30%. Through the Ads Incentive Program (AIP), however, creators can earn 55% for running at least 3 minutes of ads per hour. For the creator to be eligible, the Ads Scheduler needs to be turned **on**.

## Seeing Ads as a Viewer
Many factors will determine if a viewer will see an ad. These include, but are not limited to:
- the location of the viewer (Twitch homepage, browse page, channel page, VOD, livestream, etc.)
- the creator's settings for ads (Ads Scheduler, benefits for subscribers, etc.)
- the location, device and time of day

## Advertisement Products
The following ad types can be booked by working together with [Twitch Advertising](https://twitchadvertising.tv/ad-products/):

- Image and/or Animation
    - Display
        - Headliner: The headliner unit includes two ad units, one on the Twitch desktop homepage and the other on the Twitch mobile app default landing page. They consist of two graphics and a hex code as a main background colour on desktop and a single static image on mobile.
        - Medium Rectangle: Not expandable and can feature animated assets. Can appear in multiple places.
        - Stream Display Ads: Available in 3 formats (Mirror-C, Skyscraper and Lower-third). Can support animation as well but are not expandable. 
        - Super Leaderboard: Not expandable and animation is supported. Appears above certain content sections.
        - Channel Skins [Experiment]: Clickable branded graphics that appear in select sponsored streams that Twitch coordinates directly with creators and brands. Branded graphics appear in-stream, on channel pages, and above chat. 
- Video
    - Homepage Carousel: A livestream can be promoted on the homepage in one of the rotating carousel slots. This is also known colloquially as "frontpage", but this is slightly misleading the frontpage has many different types of formats.
    - Streamables: The viewer opts in to a full screen ad while on a Twitch Partnered mobile game. The viewer will watch 30sec of an unskippable live stream. They can then continue watching the stream on Twitch or continue on their original app.
    - Twitch Premium Video: Can be incorporated into Twitch live broadcasts across desktop, mobile, and tablet, and connected TV devices. Up to 60sec (with extra charge over 30sec), midroll only.
    - First Impression Takeover: Viewers are shown an ad as soon as they enter Twitch. Maximum 30sec and unskippable.

---
Anything **unclear** on this page? [Create an issue on Github](https://github.com/matthewbrandt/streamerwiki/issues/new)