# Starter FRONTEND Tailwind CSS v3 as a PostCSS plugin with JIT mode

## How to use

**Step 1:**<br>
`npm install`

**Step 2:**<br>
`npm run build`

Watches files as you make changes to your `index.html` within `public` folder

**Step 3:**<br>
`npm run prod`

**Windows Users:**<br>
`"build": "set TAILWIND_MODE=watch&postcss tailwind.css -o ./public/styles.css -w --verbose"`

**Mac Users:**<br>
`"build": "TAILWIND_MODE=watch postcss tailwind.css -o ./public/styles.css -w --verbose"`
