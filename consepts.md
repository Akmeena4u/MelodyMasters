# introduction
Here i am making a music learning website by using basic nextJs(a fullstack framework to build frontend and backend ) and a new css liberary Aceternity Ui ,i have chosen this Above shadcn and others because there i can build anything by just drag and drop but this is a new liberary and this is little bit buggy as of now so if i will use this i will learn actually how to use open source projects and how to solve basic problems in them according pur needs

# steps 
## 1. setup
      1. install - npx create-next-app@latest
      2. to  run this project check script and type --like -  npm run dev
      3. our whole app code will be inside src 's app folder and other required folders . in app there will be layout.tsx (Layout components are typically used to structure the overall layout of 
         a page,) and page.tsx (naming will be same inside)
      4. 

## 2. Navbar
      1. To make navbar i will use Aceternity 's navbar componet
      2. firstly check preview and make folder according names giving in  library 
      3. now use main code , here we modify accoring our project 
      4. "use client" pragma with next/dynamic, it informs Next.js that the specified module should be dynamically loaded on the client side, allowing you to split your code

 ## 3. Hero section
      1. Here will be a tagline and its description along with a button to explore courses
      2. Here main use of aceternity will come in two places - while spotlight effect and moving border around button
      3. while using spotlight and moving border from lib only use highlighted part 
      4. here we also need to add a tailwind plugin in tailwind.config.js to add global css of colors

 ## 4. featured card
      1. Here for whole data of cards i imported it from data 
      2. here main use of aceternity will be in  background-gradient 
      3. we are using typescript to make things good for security purpose so for that i decided to make whole card a custome datatype 
      4. so for that i use interface keyword and use this keyword along courses 
