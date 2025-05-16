A simple web browser pong clone that uses JavaScript and HTML.

Still needs UI and scorekeeping work, but the basic functionality is there!

FIXMEs:
There is currently a problem with the way collision is being detected
- Sometimes the score will increase by multiple points for what is, visually, a single collision
- If the ball touches the top/bottom of the paddle, it passes through the paddle without bouncing. Though, interestingly, collision is still being detected multiple times. Probably an combination between collision issue and the way a "bounce" is coded.
