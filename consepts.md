# introduction
Here i am making a music learning website by using basic nextJs(a fullstack framework to build frontend and backend ) and a new css liberary Aceternity Ui ,i have chosen this Above shadcn and others because there i can build anything by just drag and drop but this is a new liberary and this is little bit buggy as of now so if i will use this i will learn actually how to use open source projects and how to solve basic problems in them according pur needs
 here we use typescript,nextjs,aceternity 
 its based on mostly ui and nextjs familirity

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
      3. for courses page we will use 3dcads from library and import img from public folder
      3. while using spotlight and moving border from lib only use highlighted part 
      4. here we also need to add a tailwind plugin in tailwind.config.js to add global css of colors

 ## 4. featured card
      1. Here for whole data of cards i imported it from data 
      2. here main use of aceternity will be in  background-gradient 
      3. we are using typescript to make things good for security purpose so for that i decided to make whole card a custome datatype 
      4. so for that i use interface keyword and use this keyword along courses 

 ## 5. Sticky scroll revel
      1. here we will take this compo from aceternity ui library
      2. it willl be in ui whychooseus section
      3. 
 ## 6. Grid background and moving cards
      1. for this i used aceternity library's infinteMovingcards
      2. add basic source code in ui/infinite-moving-cardds with modifications and then make a seprate compo for testimonials to use and in last add it in page .tsx
      3. in background we want a grid but we know in telwind we dont have such property so for this from aceternity i used grid and dot compo. it come swith dark:bg-grid-white
      4. also we need to install mini-svd-data-uri dependency .it's important for tailwid.config so we need to add there also . here i ussed function seprately for scalable pirpose and then 
         added to plugins

  ## 7. card hover effect
      1. featured webinars page willl be designed here . we will takw it from hover effect from library

 ## 8. Contact our instructors- Animater ToolTip and wavybg
      1. in ui make animatedtooltip.jsx
      2. install wavy background from library in ui
      3. make instructors.jsx in compo and add in page.jsx
      4. images may not configured in nect js so try to solveit  go to in config and imsert domains

  ## 9. page footer and animated cards with pagging and routings 
     1. in ui add 3dcard efferts but in mobile devices it may not work properly its cons
     2. design footer.tsx here we will use grids
     3. now we will define routes for home,courses ,contact us 
     4. in src/app/courses  similarly for others 
     5. for contact us page we used matoor

   ## Note
      1. we can use shadcn diretly as alternative and easy like when we need a compo in aceternity we manully needs to add that in ui folder and then we use that but in shadcn it will directly 
        installed when we import and all are mobile optimized and scalable but less fancy
       2. daisy ui is also a tailwind compo library 
