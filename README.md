# Mini Space Museum

Small AR app for the AR activity. Point a phone at the Hiro marker and a little
space scene comes up on the marker.

## What is in the scene

- a platform (cylinder) the whole thing stands on
- a rocket loaded from `models/rocket.glb`
- a planet that spins slowly and changes colour when tapped
- a moon next to it
- a satellite made from boxes and a cylinder
- a text label that says SPACE EXPLORER

The rocket goes up and down, the planet rotates. Tap the planet to change its
colour and tap the rocket to make it bigger, tap again to put it back.

There is a bar at the top of the screen. It says "Looking for marker..." at the
start, turns green when the marker is found and red when it is lost.

## Files

```
index.html
models/rocket.glb
```

## Running it

It has to be on a server, the camera will not work if you just open the file.

```
python -m http.server 8000
```

Then go to http://localhost:8000. On a phone you need an HTTPS link, so use the
GitHub Pages link below instead of localhost.

## Marker

Hiro marker, print it or show it on another screen:
https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.jpg

## Live version

https://hirundineth.github.io/ar-activity/

## Credits

Rocket model: "Space rocket" by Hennadiy Kyseliov, from Poly Pizza
(https://poly.pizza/m/8GOlSAMYkeC), CC BY 4.0
(https://creativecommons.org/licenses/by/4.0/).

A-Frame 1.3.0 and AR.js 3.4.5 are MIT.
