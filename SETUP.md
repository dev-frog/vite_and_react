# Vite Setup with eslint

```bash
yarn create vite

yarn add -D eslint

npx eslint --init
```

> eslint question
```text
✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ What format do you want your config file to be in? · JavaScript
The config that you've selected requires the following dependencies:

eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · yarn

```

## Airbnb eslint configuration

```bash
npx install-peerdeps --dev eslint-config-airbnb
```

## Prettier configuration

```bash
yarn add -D prettier eslint-config-prettier eslint-plugin-prettier
```

> .prettierrc.cjs

```javascript
.module.exports = {
  trailingComma: "es5",
  tabWidth: 4,
  semi: false,
  singleQuote: true,
};

```


## Testing using Vitest

```bash
yarn add -D vitest

# Testing library 
yarn add -D @testing-library/react
```