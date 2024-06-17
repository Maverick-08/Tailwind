# PROJECT - 1

 This project demonstrates how to toggle between "light" and "dark" mode in React using Tailwind Css
## STEPS 

 1. Setup the initial template from this [site](https://tailwindcss.com/docs/guides/vite) here.

 2. Edit the tailwind.config file.
```
/** @type  {import('tailwindcss').Config} */

export  default {

	darkMode:  "class",

	content: [

			"./index.html",

			"./src/**/*.{js,ts,jsx,tsx}",

	],

	theme: {

			extend: {},

	},

	plugins: [],

}
```
3. Style your components in the following fashion :

	`` className=" <Add utility classes for light Mode> dark: <Add utility classes for dark Mode  "`` 
	#### Example :
	`` <p className="text-gray-500 dark:text-white-400">Random Text</p>``

4. Use useState() and useEffect() hooks for toggling between "light" and "dark" mode