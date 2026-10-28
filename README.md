# Ant Colony Optimization for the Traveling Salesman Problem

An interactive, browser-based demonstration of **Ant Colony Optimization (ACO)**, a bio-inspired optimization technique, applied to the **Traveling Salesman Problem (TSP)**.

## Project overview

This project demonstrates how ideas inspired by real ant colonies can be used to search for short routes between a set of cities. Artificial ants construct tours using pheromone information and distance-based heuristics. Pheromone evaporation and reinforcement help the search balance exploration and exploitation.

The website is built as a single HTML file with embedded CSS and JavaScript. It runs directly in a modern web browser and does not require external libraries or a build step.

## Features

- Interactive city map: add cities, drag them to new positions, and double-click a city to remove it.
- ACO solver with configurable ant count, iteration count, alpha, beta, and evaporation rate.
- Animated ant tours and a highlighted best tour.
- Live statistics, including iteration count and best tour distance.
- Convergence graph showing how the best distance changes over iterations.
- Algorithm flowchart and transition-probability equation.
- Light/dark theme, fullscreen, screenshot, and presentation modes.
- Explanations of biomimicry, swarm intelligence, and example engineering applications.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add or reposition cities, adjust the parameters, and select **Solve ACO**.

No package installation or compilation is required.

## Deploy with GitHub Pages

1. Upload `index.html` and `README.md` to the root of your GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages** in the sidebar.
4. Under the build and deployment settings, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The published URL will be shown in the Pages settings.

The file must be named `index.html` and placed in the publishing folder for it to load as the site's home page.

## Controls

- **Click the canvas** or use **Add City** to add a city.
- **Drag a city** to move it.
- **Double-click a city** to remove it.
- Use **Random** to create a random set of cities.
- Select **Solve ACO** to run the optimization.
- Use **Pause**, **Resume**, and **Reset** to control the simulation.
- Adjust the sliders to change the algorithm's parameters.
- Keyboard shortcuts: `Space` to solve/pause/resume, `A` to add a city, and `R` to reset.

## Algorithm parameters

- **Alpha (α):** controls the influence of pheromone trails.
- **Beta (β):** controls the influence of distance-based heuristic visibility.
- **Evaporation rate (ρ):** controls how quickly pheromone trails fade.
- **Number of ants:** sets how many candidate tours are constructed per iteration.
- **Iterations:** sets the number of optimization iterations.

The algorithm is heuristic: it searches for a good tour but does not guarantee the globally shortest tour for every input.

## Project contents

```text
aco-tsp-optimizer/
├── index.html
├── README.md
├── LICENSE.txt
└── .gitignore
```

## Educational use

This project is intended as an educational demonstration of biomimicry, swarm intelligence, and combinatorial optimization. The antivirus section is an analogy only; the website does not perform real antivirus scanning.

## Credits

Project: Engineering Biology — Ant Colony Optimization for the Traveling Salesman Problem  
Author(s): Add your name(s) or team name here.
