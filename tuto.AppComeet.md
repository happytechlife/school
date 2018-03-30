1. Clone the project in your camputer
2. Open CMD , tape "npm install" (this action install all package that you need)
3. Then , tape "npm install -g webpack webpack-dev-server" (this action install webpack. Webpack enable at your camputer to have a port in local for work your project)
 4. Now, you install "webpack-dev-server --config=config/webpack.config.js --env.environment=alpha"
 5. Once the install is finish , you can see just above on the yellow line the port it has choose. 
 for exemple for me i see this message : " @ multi (webpack)-dev-server/client?http://localhost:8080 ./config/polyfills ./src/index.tsx " 
 here , it say me that i can work on the localhost:8080 
 6. Now you are ready to beggin the coding !!! 

 7. You need always to work on a branch for to not break your branch master 

 8. for that : Create a new branche 
 9. with the command git branch , git checkout , git status for verify if you are on a branch 
 10. If you are in your branch so you have to restart to install npm on the CMD "npm install" and "webpack-dev-server --config=config/webpack.config.js --env.environment=alpha" 
 11. you have to do this each time you create a new branch
 

