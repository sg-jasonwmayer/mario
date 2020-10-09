<p align="center">
<div style="width:100%;height:0;padding-bottom:88%;position:relative;"><iframe src="https://giphy.com/embed/9m5a3Tdw8dWKs" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/mario-shrooms-9m5a3Tdw8dWKs">via GIPHY</a></p>
  <br>
</p>

# MarioJS

# Installation
## This project uses [Yarn](https://yarnpkg.com/lang/en/docs/install/)!
### please make sure you have yarn installed and run ``` yarn install ``` after cloning to pull down all dependencies.

---

# Running
### ``` yarn dev ```

#### Then you can navigate to `localhost:8888` or whatever port you specified!

---

## Yarn Scripts available: 
| name | what it does | 
| --- | --- |
| lint | runs eslint using a slightly modified airbnb eslint config |
| test | runs both the client and server tests via jest |
| test:coverage | same as above but passing the --coverage flag to jest |
| test:client | run the client or frontend tests |
| test:server | run the server or backend tests |
| presendCoverage | merges the client and server code coverages to one lcov |
| sendCoverage | sends merged coverage to codeclimate |
| webpack | runs the production webpack bundle |
| webpack:watch | runs the development webpack bundle which has watch enabled |
| server | runs the server for production via the node command with NODE_ENV set to 'prodution' |
| server:watch | runs the server for development with nodemon and NODE_ENV set to 'development' |
| styles | compiles the scss files to a single styles.css |
| styles:watch | same as styles but with the --watch flag passed to node-sass |
| build | builds the apps assets for production using webpack and node-sass |
| prod | runs the build command and starts the production server |
| dev | runs all the watchers in parallel for local development |
