### Part 3: Document Your Observations

- the bundle.js does not include the extra non imported functions
  after switching to production mode

- i installed style-loader and css-loader
  then added {
  test: /\.css$/i,
  use: ["style-loader", "css-loader"],
  }
  to webpack.config.js

- I tested it live to see that the css (the page turned blue) and functions were on console.
