# eslint-config-standard-pure-fp

An ESLint configuration which builds on JS Standard Style with
additional rules that restrict JS to a pure, functional programming language.
A more rigid version of [eslint-config-standard-fp](https://github.com/joshburgess/eslint-config-standard-fp).
Based on [eslint-config-standard](https://github.com/feross/eslint-config-standard) + [eslint-config-cleanjs](https://github.com/bodil/eslint-config-cleanjs)

## Instructions

First, install the eslint config & required plugins.

```bash
yarn install --dev eslint-config-standard-pure-fp
yarn install --dev eslint-plugin-better
yarn install --dev eslint-plugin-fp
yarn install --dev eslint-plugin-import
yarn install --dev eslint-plugin-promise
yarn install --dev eslint-plugin-standard
```

Then, add this to your .eslintrc.json file:

```
{
  "extends": "standard-pure-fp"
}
```
