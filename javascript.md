## Boilerplate
```js
(async () => {
})();
```

## Read / Write file
```js
# write
let data = JSON.stringify(json);
fs.writeFileSync("file.json", data);

# read
let data = fs.readFileSync("file.json");
let json = JSON.parse(data);

# pretty print
JSON.stringify(result, null, 2)
```

## List folders
```js
let folders = await fs.promises.readdir("path");
```
