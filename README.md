# xaos
Repo for auto-build of XaoS for docker.

XaoS has long been a fantastic interactive fractal zooming program, letting you explore fractals in real-time, with many options, color-cycling, etc. It runs in X-Windows (though I haven't figured that bit out in Docker, yet), but best of all, it also has an ASCII-art driver, and will run in a standard text terminal window!

Recommended: Make your terminal window as large as you can. Go fullscreen, if possible. It also looks better the smaller your fonts are. More "pixels" for your fractals...

To run:
- docker run -it patricknw/xaos

You'll start off with the classic Mandelbrot fractal. (Which is on key "1". Try other fractal formulae on numerical keys 2-0.)

Many keys do many functions:
- h for help (TAB to navigate, ESC to exit back out)
- +/- cycle colors by one step
- y cycles colors continuously (TRY THIS)
- a toggles autopilot navigation (TRY THIS)
- o toggles rotation (Cool, but sometimes loses its way when combined with autopilot)
- f changes fill-coloring mode
- i changes the plane
- q to quit

These toggles and controls work in combination with each other. (Try "a+y")

There is much more, but you'll need to look in the docs. (It also looks better in actual graphics mode. The ASCII art driver is more humorous than artistic. It is available on Windows/Mac/Linux/others, if you want to see it in its full glory.)

More info:
- https://en.wikipedia.org/wiki/XaoS
- http://matek.hu/xaos/doku.php
- https://github.com/xaos-project/XaoS

Quick example video (45 seconds):
- https://www.youtube.com/watch?v=9ltIvooYa1U
