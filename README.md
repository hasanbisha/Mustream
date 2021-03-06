# Mustream

A quick hack to stream music from the spotify library using your terminal.

## Description 
 This script will look up for the best available result given any keywords. </br>
 Ideally you should give the complete track info ( $artist - $song ) for more 
 accurate results. </br>
 No sign up or premium subscriptions are required, this is a small workaround 
 to Spotify API. </br>
 <img src="record.gif"> </img>
 
## Features:
Queue up any track/album/playlist from the spotify library.

## Usage :
* Type a song title or artist name for a quick search. </br>
* Add prefix `Album`/`Playlist` for respective results. </br>
* You can direcly input a playlist URL. </br>
* Spotify client must be running. (cf. below on how to hide it).

## Tricks & Notes :
* This script doesn't provide a client interface (pause,next,prev) </br>
I suggest you use SP (https://gist.github.com/wandernauta/6800547) for this
purpose.
* If you want to queue a single artist playlist, add the prefix `some` before to load </br>
a complete playlist, acronyms are accepted for popular bands: </br>
   - `play some PF` will queue up a Pink Floyd playlist</br>
   - `play some NMH` will queue up a Neutral milk hotel playlist </br>
* To hide the Spotify GUI you can try out these commands. (will work better on a WM) </br>
  - `xdotool search --name spotify windowunmap`
  - `wmctrl -r "spotify" -b toggle,hidden`
* Some songs may not play for you due to country restrictions.

## Installation :
* Download the script </br>
* Add it to your ~/.local/bin/ </br>
* Rename or change alias to `play` in your .bashrc/.zshrc
