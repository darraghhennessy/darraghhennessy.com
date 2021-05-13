How to host the site on Netlify:

1.Start a new site on Netlify targeting your GitHub repo


2.In your build settings set:

Build command:		npm run build
			(If you haven't already, go to the package.json file in your project and add to the "scripts" :
			"build": "npx tailwindcss-cli build css/tailwind.css -o public/build/tailwind.css")

Publish directory:	public/


3.On Netlify go to Set up Netlify DNS for your domain. This will give you a list of name servers that you will use. 

4.Now go to the website's registar (in my case this was namecheap.com) and replace your site's name servers with Netlify's ones.

 