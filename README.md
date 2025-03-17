# P5.js Volcano Eruption Simulation

## Overview
This project is an interactive animation of a volcano erupting, created using P5.js. The simulation includes dynamic elements such as lava particles, smoke plumes, flowing lava, and a stylized night sky backdrop.

## Features
- Realistic volcano with glowing crater
- Animated lava particles shooting from the crater
- Dynamic smoke plumes that rise and expand
- Flowing lava that moves down the sides of the volcano
- Starry night sky backdrop
- Randomized particle behaviors for a natural look

## Demo
![ezgif-4f8857d38ba4a9](https://github.com/user-attachments/assets/24bd86e4-a303-4659-a3b1-5a2b09181220)

## Getting Started

### Prerequisites
- A modern web browser
- Basic understanding of HTML and JavaScript (for customization)

### Installation

#### Option 1: Using P5.js Web Editor
1. Go to [editor.p5js.org](https://editor.p5js.org/)
2. Create a new sketch
3. Replace the default code with the contents of `sketch.js`
4. Click the "Play" button to run the simulation

#### Option 2: Local Installation
1. Create a new directory for the project
2. Create an `index.html` file with the following content:
```html
<!DOCTYPE html>
<html>
<head>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
  <style>
    body { margin: 0; padding: 0; }
    canvas { display: block; }
  </style>
</head>
<body>
  <script src="sketch.js"></script>
</body>
</html>
```
3. Create a `sketch.js` file in the same directory and paste the volcano simulation code
4. Open `index.html` in your web browser

#### Option 3: Online Code Playground
1. Open an online code playground like CodePen, JSFiddle, or Replit
2. Import the P5.js library
3. Add the volcano simulation code
4. Run the code

## Customization

The simulation can be easily customized by modifying the following parameters:

### Particles (Lava Chunks)
- Adjust the number of particles by changing the loop in the `setup()` function
- Modify particle size, speed, and color in the `createParticle()` function

### Smoke
- Change smoke density by modifying the frequency of creation in the `draw()` function
- Adjust smoke expansion rate and opacity in the `createSmoke()` function

### Lava Flows
- Change the frequency of lava flows in the `draw()` function
- Modify lava flow width, speed, and length in the `createLavaFlow()` function

### Volcano
- Adjust the size and shape of the volcano in the `drawVolcano()` function
- Change the glow effect and crater appearance to your liking

## Project Structure
- `index.html`: Main HTML file that loads P5.js and the sketch
- `sketch.js`: Contains all the animation code

## How It Works
The animation works by creating and updating three main elements:
1. **Particles**: Simulated lava chunks that shoot up from the crater
2. **Smoke**: Expanding plumes that rise from the volcano
3. **Lava Flows**: Streams of lava that flow down the sides of the volcano

Each frame, the code updates the position and appearance of these elements, removes them when they expire, and adds new ones to maintain the eruption effect.

## Contributing
Feel free to fork this project and enhance it! Some ideas for improvement:
- Add user interaction (e.g., click to cause eruptions)
- Add sound effects
- Implement day/night cycle
- Add more background elements (trees, clouds, etc.)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Created using [P5.js](https://p5js.org/)
- Inspired by natural volcanic phenomena
