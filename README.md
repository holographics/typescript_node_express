```
npm init
npm install typescript -s
sublime_text.exe package.json
npm run tsc -- --init
vim tsconfig.json
npm install express -s
vim app.ts
```
#### app.ts:
```
import express = require('express');
const app: express.Application = express();

app.get('/', function (req, res) {
  res.send('Hello World!');
});

app.listen(3000, function () {
  console.log('Example app listening on port 3000!');
});
```
```

tsc app.ts
node build/app.js
```
import express = require('express');
const app: express.Application = express();

app.get('/', function (req, res) {
  res.send('Hello World!');
});

app.listen(3000, function () {
  console.log('Example app listening on port 3000!');
});

### …or create a new repository on the command line
```
echo "# typescript_node_express" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:holographics/typescript_node_express.git
git push -u origin master
```
### …or push an existing repository from the command line
```
git remote add origin git@github.com:holographics/typescript_node_express.git
git push -u origin master
```
### …or import code from another repository
### You can initialize this repository with code from a Subversion, Mercurial, or TFS project. typescript_node_express
