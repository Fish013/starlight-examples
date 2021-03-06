# source-map

**NOTE: Source mapping is currently in [beta release](https://github.com/paulcuth/starlight-examples/blob/master/source-map/package.json#L33) only**

An example that uses `grunt-starlight` to precompile a Lua script into a JavaScript file with associated source map.

See this example online at: http://paulcuth.me.uk/starlight/source-map-example

## Running locally

Navigate to the `source-map` directory in a terminal, then install dependencies and build: 

```
npm install
npm start
```

This will compile `/src/script/app.lua` to `/dist/script/app.lua.js` and `/dist/script/app.lua.js.map`, 
and then serve the result at http://127.0.0.1:8080. Follow instructions on page to step through your 
code in the browser.