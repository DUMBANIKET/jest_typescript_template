# Jest Typescript Template

## For vanilla js

Add the below in ```package.json``` and then run ```npm install``` or ```yarn install```

```
{
  "devDependencies": {
    "@babel/plugin-transform-runtime": "7.17.10",
    "@babel/preset-env": "7.17.10",
    "@babel/runtime": "7.17.9",
    "babel-jest": "28.0.3",
    "jest": "28.0.3"
  },
  "scripts": {
    "test": "jest"
  },
  "babel": {
    "presets": [
      "@babel/preset-env",
      {"targets": {"node": "current"}}
    ]
  }
}
```


### Or add this

```
npm add --dev babel-jest @babel/core @babel/preset-env
```

-------------------

# for Typescript

```yarn add --dev @babel/preset-typescript ```

```

{
  "devDependencies": {
    "@babel/plugin-transform-runtime": "7.17.10",
    "@babel/preset-env": "7.17.10",
    "@babel/runtime": "7.17.9",
    "babel-jest": "28.0.3",
    "jest": "28.0.3"
  },
  "scripts": {
    "test": "jest"
  },
  "babel": {
    "presets": [
      "@babel/preset-env",
      {"targets": {"node": "current"}},
      "@babel/preset-typescript"
    ]
  }
}
```



- babel.config.json

```
module.exports = {
  presets: [
    '@babel/preset-env',
    {targets: {node: 'current'}},
    '@babel/preset-typescript',
  ],
};
```


