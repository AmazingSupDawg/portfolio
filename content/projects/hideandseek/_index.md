---
title: "hide & seek"
showDate: False
showReadingTime: False
showAuthor: False
---
### make the world your playground

This was an app I developed over the summer of 2025. It was heavily inspired by [Jet Lag: The Game](https://www.youtube.com/c/jetlagthegame).

### How it works
The seekers receive a randomized radius that the hider is somewhere within. This radius will shrink and randomly update every few minutes. The hider can see the precise locations of all hiders that updates a bit more frequently. The goal? Outmaneuver and outlast until the game is up. 

{{< button href="https://apps.apple.com/us/app/hide-seek-play-anywhere/id6745705866" target="_self" >}}
{{< icon "apple" >}} Download on the App Store
{{< /button >}}


### Developer Notes
This was a huge undertaking for me, and I learned a lot. This was the first time I needed to truly use a complicated navigation system and also manage multipeer state management. This was all done through GameKit and even features achievements!
For navigation, I utilized a true view router approach where all views were pushed and pulled from explicitly. This was a really fun project that I hope to return to :)