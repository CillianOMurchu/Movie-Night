<p align="center">
  <a href="https://chilliano.github.io/movie-night/">
    <img src="./src/assets/images/README/Movie-Night-Mobile.png" alt="Movie Night Cover Image">
  </a>
</p>

# Movies List Application

A quick exercise showcasing Angular features including Redux (@ngrx/store), filtering, testing, Angular Material, media query animations, theming, and styling. The UI delivers a fast-paced layered menu with smooth navigation between details and the main page.

## Technologies

- [Angular](https://angular.io/)
- [Redux](https://redux.js.org/)
- [Angular Material](https://material.angular.io/)
- [Lazysizes Image Lazy Loader](https://github.com/aFarkas/lazysizes)

## Installation

1. Ensure you have Node.js, npm, and Angular CLI installed:
   - [Node.js](https://nodejs.org/en/download/)
   - [npm](https://docs.npmjs.com/cli/install)
   - [Angular CLI](https://angular.io/cli)
2. Clone this repository
3. Run `npm install` to install dependencies
4. Run `npm run start` to launch the app

## Features

- Redux store setup with @ngrx/store and debugging with @ngrx/store-devtools
- Responsive design with Angular Material components for a mobile-friendly experience
- Optimized image loading using lazysizes for fast, jank-free visuals

## Future Enhancements

- Movie details page with ratings, reviews, and stylized visuals
- Movie favoriting with confirmation snackbars integrated with Redux
- Improved filtering UX including sticky genre filter and dynamic layout adjustments

## Known Issues

- Filter-by-genre button not sticky at top
- Absolute import path configuration pending
- Extract filter and movie details components for modularity
- Indicate filter match context (title, description) to users
- Reset search term on homepage navigation
- Proper usage of genre enums

