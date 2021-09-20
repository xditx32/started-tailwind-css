# Install Tailwind CSS

## How to use

**Step 1:**<br>
`npm install`

**Step 2:**<br>
`npm run build`

Watches files as you make changes to your `index.html` within `public` folder

**Windows Users:**
`"build": "set TAILWIND_MODE=watch&postcss tailwind.css -o ./public/styles.css -w --verbose"`
**Mac Users:**
`"build": "TAILWIND_MODE=watch postcss tailwind.css -o ./public/styles.css -w --verbose"`
