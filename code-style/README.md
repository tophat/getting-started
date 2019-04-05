# Top Hat Code Styles

When starting a new project, please use the appropriate linter configuration from this folder to ensure that code style remains consistent.

You can use the @tophat/eslint-config package available from NPM:

```
npm install @tophat/eslint-config # ... plus some other packages!
```

**Please see the [@tophat/eslint-config repo](https://github.com/tophat/eslint-config) for a list of all the packages needed to use linting with prettier, react, and jest.**

And modify your `.eslintrc.json`
```json
{
  "extends": [
      "@tophat",
      "@tophat/eslint-config/jest"
  ]
}
```
