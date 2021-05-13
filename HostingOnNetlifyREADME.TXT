How to host the site on Netlify:

1.Start a new site on Netlify targeting your GitHub repo

2.In your build settings set:
Base directory:		public

Build command:		NODE_ENV=production npx tailwindcss-cli@latest build ./build/tailwind.css -o ./dist/tailwind.css

Publish directory:	(blank)

(Base directory and Publish directory may be interchangeable but this worked for me)