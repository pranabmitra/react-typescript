# A simple react + typescript application

Install dependencies:

```sh
npm install react react-dom webpack webpack-cli webpack-dev-server typescript @types/react @types/react-dom ts-loader
```


package.json - specifying our modules

tsconfig.json - configuring typescript

webpack.config.js - to use webpack for compiling and running our code and npm modules in the browser

```sh
# development build
npm run dev
# Browse: http://localhost:8080/

# production build
npm run prod
# Serve the index file from the public folder
```