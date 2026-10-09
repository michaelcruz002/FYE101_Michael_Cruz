# CSC383-A: Game Engines

[Home](index.md) | [About Me](about.md) | [All Courses](index.md#my-fall-2026-courses)

---

## About This Class

This page shows some of the work I've been doing in Game Engines. I like playing games, so I think it's interesting to see how code controls movement, graphics, and collisions.

## My Project: ArenaRoids

One of the projects I've worked on is called **ArenaRoids**. The code uses **JavaScript** and **Babylon.js**, a tool for building 3D scenes on the web.

The project creates a large sphere with smaller, colorful asteroid spheres moving around inside it. The asteroids can bounce off the arena wall and collide with each other.

### What My Project Includes

- A 3D scene, camera, and lighting.
- **40 asteroids** with random sizes and colors.
- Asteroids moving in different directions.
- Code that detects when asteroids touch the inside wall.
- Speed increases when an asteroid hits the arena boundary.
- Collision calculations between different asteroids.
- A camera that can be moved by looking around with the mouse.

### Part of My JavaScript Code

```javascript
const ASTEROID_COUNT = 40;
const BASE_SPEED = 0.15;
const SPEED_INC = 0.02;
const BIG_SPHERE_RADIUS = 50;

// Create the asteroids for the scene.
for (let i = 0; i < ASTEROID_COUNT; i++) {
    asteroids.push(new Asteroid());
}

// Check collisions and update positions before each frame.
scene.registerBeforeRender(() => {
    resolveAsteroidCollisions();
    asteroids.forEach(a => a.update());
});
```

*This is an excerpt from my project. The full code is in the HTML file below.*

## Try the Project

**[Open ArenaRoids in your browser](ArenaRoids.html)**

The project uses Babylon.js files loaded from the internet, so it needs an internet connection. Clicking inside the scene enables mouse-look on browsers that support pointer lock; press **Esc** to release the mouse.

## What I'm Learning

Working with this code has given me a better understanding of how a game engine uses objects, motion, collision detection, and a render loop. Instead of just playing a game, I am seeing how its pieces can be programmed.

## Course Image

<img src="images/csc383-game-engines.jpg" alt="3D Game Engines project preview" width="650">


---

[Back to the homepage](index.md)
