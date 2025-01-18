# Portfolio
### A new portfolio using React and Tailwindcss

---

***Initial SetUp of React***
1. Open fresh window of VS Code
2. Open base directory where I put my projects
3. Execute the following command to install the React using Vite 
 ```
  npm create vite@latest portfolioUsingReactTailwindcss
  framework: react
  variant: javascript
  ```
4. Set a port address inside the defineConfig of vite.config.js file
 ```
 server: {
     port: 3030
 }
 ```
5. Install the node_module using the `npm install`
6. Finally Run this Project `npm run dev`

---

***Boilerplate CleanUp***

1. Delete all the file except inside the src folder except
   - assets *(delete internal files)*
   - App.jsx *(clean internal code)*
   - index.css *(clean internal code)*
   - main.jsx

---

***Tailwindcss Setup***

- Google `tailwindcss setup using vite`
- Refers the sets mentioned in the official site of [tailwindcss](https://tailwindcss.com/docs/guides/vite)
- **Remember** *React doesn't work with `class` attribute we have to use `className` attribute to provide the classes of tailwindcss, even if we take code snippet from the official website, then also, we have to make changes accordingly.*
 
---

***Extensions***

- **console ninja:** It provides the inline output of `console.log()` at the runtime
- **ES7+ React/Redux/React-Native snippets:** It is useful for the code snipped, mainly for component snippets. Refer its documentation for shortcuts of the snippets.