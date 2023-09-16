# LMS Frontend

### Setup instruction

1. clone the project

'''
   git clone https://github.com/kamareaalam/lms-frontend.git
'''

2. Move into the directory

'''
   cd lms-frontend
'''
3. install dependencies

'''
   npm i
'''


4. run the server

'''
   npm run dev
'''



### Setup instruction for tailwind

[Tail wind official instruction doc](https://tailwindcss.com/docs/instruction)

1. Install tailwind

'''
   npm install -D tailwind
'''

2. Create tailwind Config file

'''
   npx tailwindcss init
'''

3. Add file extensions to tailwind Config file in the contents property
'''
   "./src/**/*.{html,js,jsx,ts,tsx}"
'''


4. Add the tailwind directives at the top of the 'index.css' file

'''
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
'''
