# Top Hat Code Styles

When starting a new project, please use the appropriate linter configuration from this folder to ensure that code style remains consistent.

You can use the ling-config package available from NPM:

`npm install @tophat/lint-config`

And modify your `.eslintrc.json`
```json
{
  "extends": [
      "@tophat",
      "@tophat/eslint-config/jest"
  ]
}
```
