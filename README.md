# eslint-config-standard-fp

An ESLint configuration which builds on JS Standard Style with
additional rules that restrict JS to a more functional programming oriented
subset of the language.

## Instructions

First, install the eslint config & required plugins.

```bash
npm i -D eslint-config-standard-fp eslint-plugin-fp eslint-plugin-promise eslint-plugin-standard
```

Then, add this to your .eslintrc.json file:

```
{
  "extends": "standard-fp"
}
```
