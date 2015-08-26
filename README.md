# eslint-plugin-lw

ESlint plugin for that extra Laurel &amp; Wolf style.

## Install

```
npm install eslint-plugin-lw --save-dev
```

## Configuration

Add plugins section and specify **esLint-plugin-lw** as a plugin

```json
{
  "parser": "babel-eslint",
  "plugins": [
    "lw"
  ]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "lw/function-padding": 2
  }
}
```

### Rules

*  `lw/function-padding` - Enforce a padding of one line below any function declaration or expression


