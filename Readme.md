To verify that it will run globally, you need:
1. Check if you have params in package.json:
```json
  "bin": {
    "ytdl-cli": "./index.js"
  } 
```
2. Run command: 
```shell
npm i -g 
```