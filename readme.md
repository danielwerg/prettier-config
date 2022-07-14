# prettier-config

⚙️ Shared Prettier config

[tsconfig](https://github.com/danielwerg/tsconfig)
• [ESLint Config](https://github.com/danielwerg/eslint-config)

## 💾 Install

```sh
yarn add -D @danielwerg/prettier-config
```

```sh
yarn add -D prettier
```

### VSCode Prettier ESLint extension

[GitHub](https://github.com/idahogurl/vs-code-prettier-eslint)
• [Marketplace](https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint)
• [VSCode](vscode:extension/rvest.vs-code-prettier-eslint)
• [VSCodium](vscodium:extension/rvest.vs-code-prettier-eslint)

## 👀 Usage

Edit `package.json`:

```json
{
  "prettier": "@danielwerg/prettier-config"
}
```

---

Or if you want to put it in a separate file

`.prettierrc`

```json
"@danielwerg/prettier-config"
```

---

Or if you want to extend it

`.prettierrc.js`

```js
module.exports = {
  /** @type {import('prettier').Options} */ // optional IntelliSense support (neeeds `@types/prettier`)
  ...require('@danielwerg/prettier-config'),
  printWidth: 100
};
```
