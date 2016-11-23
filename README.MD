# memopad
React tutorial(Single-page infinite-scrolling public memo app implemented using React.js, Redux, Express.js and MongoDB) on docker image
Reference : https://www.inflearn.com

# Features
  -Docker container
  -Authentication (Sign Up / Sign In)
  -Memo Creation / Manipulation (edit, delete, star)
  -User Search

pull ubuntu
--name memo -p 30000:3000 -it ubuntu /bin/bash

Following technologies are used
git
nodejs
mongodb
es6
webpack webpack-dev-server
babel-cli : form es6 to es5
nodemon : when amended in dev-env, restart the server
cross-env : environmental variables
express : nodejs web framework
body-parser : for json
axios : http client
react-addons-update : immutablility helper (for redux)
react-router : client-side router
redux : modern react framework
style-loader
css-loader

port mapping 30000 to 3000
