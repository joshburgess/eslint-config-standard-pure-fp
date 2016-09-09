# eslint-config-standard-pure-fp

An ESLint configuration which builds on JS Standard Style with
additional rules that restrict JS to a pure, functional programming language.
A more rigid version of [eslint-config-standard-fp](https://github.com/joshburgess/eslint-config-standard-fp).
Based on [eslint-config-standard](https://github.com/feross/eslint-config-standard) + [eslint-config-cleanjs](https://github.com/bodil/eslint-config-cleanjs)

## Instructions

First, install the eslint config & required plugins.

```bash
npm i -D eslint-config-standard-pure-fp
npm i -D eslint-plugin-better
npm i -D eslint-plugin-fp
npm i -D eslint-plugin-import
npm i -D eslint-plugin-promise
npm i -D eslint-plugin-standard
```

Then, add this to your .eslintrc.json file:

```
{
  "extends": "standard-pure-fp"
}
```
