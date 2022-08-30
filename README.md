# scroll_threejs
Three.js shown followed by mouse scroll (ilbuni reference was used)


----------
1. Installing Package
----------

npm i -D @babel/cli @babel/core @babel/preset-env babel-loader clean-webpack-plugin copy-webpack-plugin core-js cross-env html-webpack-plugin source-map-loader terser-webpack-plugin webpack webpack-cli webpack-dev-server

npm i three


----------
2. Start the engine
----------

npm start



----------
3. Build
----------

npm run build



(!)
If an error occurs while "npm start" or "npm run build", download Node.js in LTS version and try again.
To, see current version, copy and paste the following into the terminal.

----------
n lts
----------

(!)
ERROR in unable to locate 'route...'
If an above like error occurs, check if you have set CopyWebpackPlugin in webpack.config.js accordingly.
If CSS and Image folders are unecessary, please comment out the area.

