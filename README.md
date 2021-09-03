# Install husky

npx husky install

```bash
npm i husky -D
npx husky install
```

# Usage

package.json

```json
 "scripts": {
    "prepare": "husky install",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

Execute "test" before commit

```bash
npx husky add .husky/pre-commit "npm test"
```


