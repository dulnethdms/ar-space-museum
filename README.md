# AR Space Project

This is a small augmented reality project created for our university AR activity. It uses A-Frame and AR.js to display a mini space scene when the camera detects a Hiro marker.

The scene includes a rocket, planet, moon and satellite, along with a few animations and interactive features.

## Scene Features

- A 3D rocket model.
- A rotating planet that changes colour when tapped.
- A moon next to the planet.
- A satellite made using basic 3D shapes.
- A platform for the space scene.
- A text label saying "SPACE EXPLORER".
- A rocket that moves up and down.
- A rocket that grows when tapped and returns to its original size when tapped again.

There is also a status message at the top of the screen to show whether the Hiro marker has been detected.

## Technologies Used

- HTML
- CSS
- JavaScript
- A-Frame 1.3.0
- AR.js 3.4.5

## Project Files

```text
ar-space-project/
│
├── index.html
├── models/
│   └── rocket.glb
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Make sure the `rocket.glb` file is inside the `models` folder.
3. Open the project folder in VS Code.
4. Run the project using Live Server or a local server.

You can also use Python:

```bash
python -m http.server 8000
```

Then open:

`http://localhost:8000`

For mobile testing, the project needs to be hosted using HTTPS so the browser can access the camera.

## Using the AR Project

1. Open the project on your phone.
2. Allow camera permission.
3. Show the Hiro marker to the camera.
4. Wait for the space scene to appear.
5. Tap the planet to change its colour.
6. Tap the rocket to make it bigger or return it to its original size.

## Hiro Marker

The project uses the default Hiro marker.

You can download or print it here:

https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.jpg

## Live Demo

[Open AR Space Project](https://hirundineth.github.io/ar-activity/)

## Credits

**Rocket model:** "Rocketship" by Gabriel Valdivia, from Poly Pizza.

https://poly.pizza/m/a5ChWS6uW0y

Licence: CC BY 4.0

https://creativecommons.org/licenses/by/4.0/

A-Frame and AR.js are used under their respective MIT licences.
