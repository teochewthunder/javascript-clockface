# JavaScript Clockface
This is a very simple script. It uses a HTML/CSS backdrop, and only three parts of the DOM are movable - the **hour hand**, the **minute hand** and the **second hand**.

Upon initialization, the script gets the current time and determines, using some math, what rotation the hands should be at.

The JavaScript utilizes a timer function that activates every one second, or 1000 ms. Each time the timer function triggers its callback, the same procedure executed at initialization is repeated.

## Note
This doesn't work in IE. Somehow the minute hand refuses to budge, despite the fact that it renders correctly at initialization.
