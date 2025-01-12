# Predator-Prey Simulation with Grass

A web-based interactive simulation of a predator-prey ecosystem built using Three.js. This simulation demonstrates the complex interactions between predators (wolves), prey (rabbits), and grass in a controlled environment.

## Features

- **3D Environment**: Beautiful 3D visualization with dynamic lighting and shadows
- **Interactive UI**: Adjustable simulation parameters through an intuitive user interface
- **Mobile Responsive**: Fully responsive design that works on both desktop and mobile devices
- **Real-time Statistics**: Track simulation metrics and view detailed statistics
- **Dynamic Ecosystem**: Complex interactions between three trophic levels:
  - Predators (Wolves)
  - Prey (Rabbits)
  - Grass (Vegetation)

## Simulation Rules

### Predators (Wolves)
- Hunt and consume prey to survive
- Die if they don't eat within their lifespan
- Reproduce after consuming prey
- Show visual indicators of hunger
- Slow down when hungry
- Create two offspring upon successful reproduction

### Prey (Rabbits)
- Consume grass to survive
- Escape from nearby predators
- Die if they don't eat within their lifespan
- Reproduce after eating sufficient grass
- Show visual indicators of hunger
- Get speed boost when escaping predators

### Grass
- Regrows periodically
- Limited to maximum density
- Serves as food source for prey
- Strategically placed across the environment

## Controls & Parameters

The simulation offers several adjustable parameters:

- **Number of Prey**: Initial rabbit population (1-100)
- **Number of Predators**: Initial wolf population (1-50)
- **Predator Lifespan**: Maximum survival time without food (5-60 seconds)
- **Predator Hunger Warning**: Time before hunger effects begin (3-30 seconds)
- **Prey Lifespan**: Maximum survival time without food (5-60 seconds)
- **Prey Hunger Warning**: Time before hunger effects begin (3-30 seconds)

## Technical Details

### Technologies Used
- **Three.js**: For 3D rendering and animations
- **HTML5/CSS3**: For UI and responsive design
- **JavaScript**: For simulation logic and ecosystem behavior

### Performance Optimizations
- Mobile-specific optimizations
- Frame rate management
- Efficient collision detection
- Memory management through object pooling
- Adaptive rendering quality

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Click "Start Simulation" to begin
4. Use the UI panel to adjust parameters
5. Click "Update" to apply changes

## Browser Compatibility

The simulation works best in modern browsers that support WebGL:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Mobile Support

The simulation is optimized for mobile devices with:
- Touch-friendly controls
- Responsive UI
- Performance optimizations
- Adaptive quality settings

## Statistics Tracking

The simulation tracks various metrics:
- Simulation duration
- Maximum predator population
- Maximum prey population
- Total grass consumed
- Total prey eaten

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a feature branch
3. Committing your changes
4. Opening a pull request

## License

This project is open source and available under the MIT License.
