# A shared Prettier config

## Installation

To install this package run the following command in the terminal in the root directory of your application.

```
npm install --save-dev @rapidevelop/prettier-config
```

**OR**

```
yarn add --dev @rapidevelop/prettier-config
```

## Usage

Add a key in your **package.json** file.

```
"prettier": "@rapidevelop/prettier-config"
```

**OR**

Create a **.prettierrc** , **.prettierrc.yaml** , **.prettierrc.yml** or **.prettierrc.json** file and export a string.

```
"@rapidevelop/prettier-config"
```

**OR**

Create a **prettier.config.js** or **.prettierrc.js** file and export an object.

```
module.exports = {
  ...require("@rapidevelop/prettier-config"),
  // endOfLine: 'lf', // to overwrite the property
};
```
