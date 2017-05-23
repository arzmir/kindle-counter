# Kindle-Counter
Life counter apps for cell phone tend to draw a ton of battery, so I wanted to make one for my Kindle Paperwhite. First I researched if it was possible to make a native app, but Amazon don't like that. Then I figured I could use the browser and built one with Vue.js to make it responsive and so on, but Amazon don't like that. Tried to build one and get some power out of CSS3, but Amazon don't like that. Djeez..!

In the end. It's as simple as it can be. 

## What it has
* Supports 4 players
* Stepping of -5,-1, 1 or 5
* Reset button for 20/40 life
* Cheesy death graphics

## Browser Caveats
1. Have limited CSS3 support (these have been tested)
    * Transform
    * Using vw/vh sizes
    * Flexbox
2. Doesn't support template literals (backtick-strings)
3. Can't disable zooming (both pinch/double click)
4. Can have problems if you forget to mute console logging
