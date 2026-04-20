# Keir Charlton-Molloy: Computer Science ePortfolio

This repository contains my capstone ePortfolio for the Bachelor of Science in Computer Science. The live site is at [kcsnu.github.io](https://kcsnu.github.io/).

For this portfolio, I used one Android app I originally built in a mobile architecture and programming course, *Mere Metrics: Weight Tracker*, and improved it across the three main areas of computer science:

1. **Software engineering and design.** I refactored the app by moving away from heavy fragment logic and organizing things into clearer layers, so validation, data access, and UI work are not all mixed together. I also replaced the old manually built history table with a RecyclerView-based design.

2. **Algorithms and data structures.** I expanded the weight history feature into more of an analytics tool, adding normalized dates, filtered date ranges, rolling averages, percent progress toward the goal, and a projected goal date.

3. **Databases.** I migrated the persistence layer from a `SQLiteOpenHelper`-based design to Room with typed entities, DAOs, versioned migrations, and stronger data integrity constraints.

The original and enhanced code are in separate repositories so it is easier to compare the before-and-after versions:

- [mere-metrics-original](https://github.com/kcsnu/mere-metrics-original): the version before any enhancements
- [mere-metrics-enhanced](https://github.com/kcsnu/mere-metrics-enhanced): the updated version with all three enhancements applied

There is also a code review video on [YouTube](https://youtu.be/DHpIhU5hk0c) where I walk through the original app, point out the issues I found, and explain the enhancements I planned.

## About the site

The site is a simple static site I built myself using HTML and CSS. There is no build process or framework; GitHub Pages hosts the files directly from this repository.
