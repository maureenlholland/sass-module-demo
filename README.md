# Sass Module Demo

## Homepage

Basic description of why Sass modules exist and how they're used. Common error descriptions.

## Sass pages

One uses old Sass `@import` and the other uses new Sass `@use` and `@forward`. 

## Parcel

`npm ci` to get the Parcel dep. Don't use `build` commands as it does a bunch of optimization that isn't helpful in this case.

Look in `/dist` for unmapped Sass files to inspect how the differently loaded stylesheets were compiled.

## Run

Just open the `index.html` file in your default browser. It's completely static.

To view the styled Sass files and poke around in dev tools, use: 
`npx parcel old-sass.html --no-cache`
`npx parcel new-sass.html --no-cache`