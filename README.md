## Overview
Stream live TV channels using Ace Stream software.\
This is just a script that allows to load channels from a file and play them using a convenient CLI.
## Disclaimer
**Stream at your own risk and responsibility. It might not be entirely legal depending on your location.**
## Prerequisites
- *acestreamplayer.mpv & acestreamplayer.engine*\
Can be installed from the snap store on Linux systems:\
`sudo snap install acestreamplayer`
- *tmux*\
Used to run the channels in background. Install using your system's package manager, e.g.\
`sudo apt install tmux`
## Channels
The channels are included in the "channels" file.
It is just a sample for some sports channels that I watch. Feel free to have your own channels.\
*acestreamsearch.net* is your friend.
## Usage
- To list the channels: `ace list`
- To play a channel: `ace play <channel number>`