### My own React eslint configuration

* Standard
* Prettier
* React recommended

```yarn add --dev eslint eslint-config-prettier eslint-config-standard eslint-config-standard-react eslint-plugin-import eslint-plugin-node eslint-plugin-prettier eslint-plugin-promise eslint-plugin-react eslint-plugin-standard prettier && echo -e "{\n  \"root\": true,\n  \"extends\": [\n    \"standard\",\n    \"react-app\",\n    \"prettier\",\n    \"prettier/react\",\n    \"eslint:recommended\",\n    \"plugin:react/recommended\"\n  ],\n  \"plugins\": [\n    \"react\",\n    \"prettier\"\n  ],\n  \"parser\": \"babel-eslint\",\n  \"parserOptions\": {\n    \"ecmaVersion\": 2016,\n    \"sourceType\": \"module\",\n    \"ecmaFeatures\": {\n      \"jsx\": true\n    }\n  },\n  \"env\": {\n    \"browser\": true,\n    \"commonjs\": true,\n    \"node\": true,\n    \"es6\": true\n  },\n  \"rules\": {\n    \"prettier/prettier\": [\n      \"error\",\n      {\n        \"semi\": false\n      }\n    ]\n  }\n}" > .eslintrc```
