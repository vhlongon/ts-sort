## To create a barebone ts project
* run `npm init -y`
* run `tsc --init`
* config `tsconfig.json` for stuff like in a output folders
* install `nodemon` and `concurrently`
* create a script to compile ts, `"start:build": "tsc -w"`
* create a script to run ts output and watch for changes `"start:run": "nodemon build/index.js"` 
* create a script to run them both `"dev": "concurrently npm:start:*"`