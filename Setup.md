<!-- Here are the instructions and setup guide for using Tailwind CSS  -->

I'll be using Tailwind older version for this project , latest version will be used for some another project some other day !


npm install -D tailwindcss@3 for older version 
npx tailwindcss init for older versions 

Update tailwindcss.config.js to include this line : content :["*.html"]

create src/input.css to include :

@tailwind base;
@tailwind components;
@tailwind utilities;

include src/output.css file to your html .

Run the command : npx tailwindcss -i ./src/input.css -o ./src/output.css --watch 
or in script in package.json ke andar likhdo aur naam rakhdo build . then just use npm run build . 
 <!--watches input.css and utilities used in your html file --> otherwise saari utilities include ho jati browser me .
