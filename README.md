# HSH Speedrun Mod
A modded version of the Flash game "Home Sheep Home" for speedrunners, which allows timing individual-level or full-game runs without an external timer.

### Is it accurate?
Depends on what you mean by accurate. The time is measured using in-game frames and then converted to seconds. So while it's always going to be consistent and timing will be frame-perfect, the in-game timer might not always show the same end time compared an external timer. This is because external timers don't account for load times or frame drops. And since Flash is not really the most stable platform for games, you're guaranteed to have some variances here and there.

### How much different is it from an external timer?
Version 1.2 and onwards uses delays between transitions to simulate a real timer as closely as possible, but it's impossible to eliminate all variation.

### Why should runners use this?

Unlike timing with LiveSplit, for example, runs will always begin and end on the same frame, and no matter how overwhelmingly bad or good your computer's performance is, the same run will always end up with the same time no matter what configuration it's recorded with.

Starting and ending runs is automated. It's easier to retry-spam runs without having to reset your timer, and inconsistencies coming from human error when starting or stopping the timer are completely eliminated.

Individual level timers and PBs seen on the level end screen have millisecond precision, so it's easier to monitor your improvement.

### Is this legal for runs uploaded to speedrun.com?

So far the moderator (ShevaDecai) hasn't responded to this question, but it's perfectly fine to use in practice. And I doubt you'd have any problems if you used this alongside an external timer for actual runs.

## Installation
Just go to [the releases page](https://github.com/p2r3/hsh-speedrunmod/releases), and download the latest version of the mod. Then open the .swf file in your Flash player.

Sadly, highscores are not maintained between releases.

## Usage
To start the timer, simply enter a level. The timer will stop once you've finished level 15.

To reset the timer, exit to the menu by pressing Esc or clicking on the menu button.
