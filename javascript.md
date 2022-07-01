## Boilerplate
```js
(async () => {
})();
```

## Read / Write file
```js
let data = JSON.stringify(json);
fs.writeFileSync("file.json", data);

let data = fs.readFileSync("file.json");
let json = JSON.parse(data);
```

## List folders
```js
let folders = await fs.promises.readdir("path");
```
