## My eslint configuration
Just copy and paste the code below for each technology

### React
```npm install --save-dev babel-eslint eslint eslint-config-prettier eslint-config-standard eslint-config-standard-react eslint-plugin-flowtype eslint-plugin-import eslint-plugin-node eslint-plugin-prettier eslint-plugin-promise eslint-plugin-react eslint-plugin-standard prettier && echo -e "{\n  \"root\": true,\n  \"extends\": [\n    \"standard\",\n    \"react-app\",\n    \"prettier\",\n    \"prettier/react\",\n    \"eslint:recommended\",\n    \"plugin:react/recommended\",\n    \"plugin:flowtype/recommended\"\n  ],\n  \"plugins\": [\n    \"react\",\n    \"prettier\",\n    \"flowtype\"\n  ],\n  \"parser\": \"babel-eslint\",\n  \"parserOptions\": {\n    \"ecmaVersion\": 2016,\n    \"sourceType\": \"module\",\n    \"ecmaFeatures\": {\n      \"jsx\": true\n    }\n  },\n  \"env\": {\n    \"browser\": true,\n    \"commonjs\": true,\n    \"node\": true,\n    \"es6\": true,\n    \"jest\": true,\n    \"mocha\": true\n  },\n  \"settings\": {\n    \"flowtype\": {\n      \"onlyFilesWithFlowAnnotation\": true\n    }\n  },\n  \"rules\": {\n    \"no-console\": 1,\n    \"prettier/prettier\": [\n      \"error\",\n      {\n        \"semi\": false\n      }\n    ]\n  }\n}" > .eslintrc```

### Vue
```npm install --save-dev babel-eslint eslint eslint-config-prettier eslint-config-standard eslint-friendly-formatter eslint-loader eslint-plugin-html eslint-plugin-import eslint-plugin-node eslint-plugin-prettier eslint-plugin-promise eslint-plugin-standard prettier && echo -e "module.exports = {\n  root: true,\n  parser: 'babel-eslint',\n  parserOptions: {\n    sourceType: 'module'\n  },\n  env: {\n    browser: true,\n  },\n  extends: ['standard', \"prettier\", \"eslint:recommended\"],\n  plugins: [\n    'html',\n    \"prettier\"\n  ],\n  rules: {\n    'generator-star-spacing': 'off',\n    'no-debugger': process.env.NODE_ENV === 'production' ? 'error' : 'off',\n    \"no-console\": 1,\n    \"prettier/prettier\": [\n      \"error\",\n      {\n        \"semi\": false\n      }\n    ]\n  }\n}\n" > .eslintrc.js```

### Node
```npm install --save-dev babel-eslint eslint eslint-config-prettier eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-prettier eslint-plugin-promise eslint-plugin-standard prettier && echo -e "{\n  \"root\": true,\n  \"extends\": [\n    \"standard\",\n    \"prettier\",\n    \"eslint:recommended\"\n  ],\n  \"plugins\": [\n    \"prettier\"\n  ],\n  \"parser\": \"babel-eslint\",\n  \"parserOptions\": {\n    \"ecmaVersion\": 2016,\n    \"sourceType\": \"module\"\n  },\n  \"env\": {\n    \"browser\": true,\n    \"commonjs\": true,\n    \"node\": true,\n    \"es6\": true,\n    \"mocha\": true\n  },\n  \"rules\": {\n    \"prettier/prettier\": [\n      \"error\",\n      {\n        \"semi\": false\n      }\n    ]\n  }\n}" > .eslintrc```
