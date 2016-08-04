# eslint-config-pixel

This package provides Pixelmatters base JS .eslintrc based on the Airbnb's JS .eslintrc.

##install

Our default export contains all of our ESLint rules, including ECMAScript 6+. It requires `eslint` and `eslint-plugin-import`.

  ```sh
    npm install --save-dev eslint-config-pixel eslint@^3.0.1 eslint-plugin-import@^1.10.3
  ```
## Usage

Add `"extends": "pixel"` to your .eslintrc
or
  ```json
  {
  "extends": "pixel",
  }
  ```
  to .eslintrc.json

### eslint-config-pixel/legacy

Lints ES5 and below. Requires `eslint` and `eslint-plugin-import`.

Add `"extends": "pixel/legacy"` to your .eslintrc
