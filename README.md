# eslint-configuration
All Configuration of Eslint

{
  "globals": {
    "Array": false,
    "ArrayBuffer": false,
    "Boolean": false,
    "constructor": false,
    "DataView": false,
    "Date": false,
    "decodeURI": false,
    "decodeURIComponent": false,
    "encodeURI": false,
    "encodeURIComponent": false,
    "Error": false,
    "escape": false,
    "eval": false,
    "EvalError": false,
    "Float32Array": false,
    "Float64Array": false,
    "Function": false,
    "hasOwnProperty": false,
    "Infinity": false,
    "Int16Array": false,
    "Int32Array": false,
    "Int8Array": false,
    "isFinite": false,
    "isNaN": false,
    "isPrototypeOf": false,
    "JSON": false,
    "Map": false,
    "Math": false,
    "NaN": false,
    "Number": false,
    "Object": false,
    "parseFloat": false,
    "parseInt": false,
    "Promise": false,
    "propertyIsEnumerable": false,
    "Proxy": false,
    "RangeError": false,
    "ReferenceError": false,
    "Reflect": false,
    "RegExp": false,
    "Set": false,
    "String": false,
    "Symbol": false,
    "SyntaxError": false,
    "System": false,
    "toLocaleString": false,
    "toString": false,
    "TypeError": false,
    "Uint16Array": false,
    "Uint32Array": false,
    "Uint8Array": false,
    "Uint8ClampedArray": false,
    "undefined": false,
    "unescape": false,
    "URIError": false,
    "valueOf": false,
    "WeakMap": false,
    "WeakSet": false
  },
  "env": {
    "es6": true
  },
  "rules": {
    "accessor-pairs": "off",
    "array-bracket-newline": "off",
    "array-bracket-spacing": [
      "warn",
      "never"
    ],
    "array-callback-return": "warn",
    "array-element-newline": "off",
    "arrow-body-style": [
      "error",
      "as-needed"
    ],
    "arrow-parens": [
      "warn",
      "always"
    ],
    "arrow-spacing": [
      "warn",
      {
        "before": true,
        "after": true
      }
    ],
    "block-scoped-var": "off",
    "block-spacing": [
      "warn",
      "never"
    ],
    "brace-style": [
      "warn",
      "1tbs"
    ],
    "callback-return": "off",
    "camelcase": "warn",
    "capitalized-comments": "off",
    "class-methods-use-this": "warn",
    "comma-dangle": "off",
    "comma-spacing": [
      "warn",
      {
        "before": false,
        "after": true
      }
    ],
    "comma-style": [
      "warn",
      "last"
    ],
    "complexity": "off",
    "computed-property-spacing": [
      "warn",
      "never"
    ],
    "consistent-return": "warn",
    "consistent-this": [
      "warn",
      "that"
    ],
    "constructor-super": "error",
    "curly": [
      "error",
      "all"
    ],
    "default-case": "error",
    "dot-location": "off",
    "dot-notation": [
      "error",
      {
        "allowKeywords": true,
        "allowPattern": "^[a-zA-Z]+(_[a-zA-Z]+)+$"
      }
    ],
    "eol-last": "warn",
    "eqeqeq": "error",
    "for-direction": "off",
    "func-call-spacing": [
      "warn",
      "never"
    ],
    "func-name-matching": "off",
    "func-names": "off",
    "func-style": "off",
    "generator-star-spacing": [
      "warn",
      {
        "before": true,
        "after": false
      }
    ],
    "global-require": "warn",
    "guard-for-in": "error",
    "handle-callback-err": "off",
    "id-blacklist": "off",
    "id-length": "off",
    "id-match": "off",
    "indent": [
      "warn",
      "tab",
      {
        "SwitchCase": 1
      }
    ],
    "indent-legacy": "off",
    "init-declarations": "off",
    "jsx-quotes": "off",
    "key-spacing": [
      "warn",
      {
        "beforeColon": false,
        "afterColon": true
      }
    ],
    "keyword-spacing": [
      "error",
      {
        "before": true,
        "after": true,
        "overrides": {}
      }
    ],
    "line-comment-position": "off",
    "linebreak-style": "off",
    "lines-around-comment": "off",
    "lines-around-directive": "off",
    "max-depth": [
      "warn",
      10
    ],
    "max-len": [
      "warn",
      2000
    ],
    "max-lines": "off",
    "max-nested-callbacks": [
      "warn",
      10
    ],
    "max-params": [
      "warn",
      10
    ],
    "max-statements": [
      "warn",
      150
    ],
    "max-statements-per-line": [
      "warn",
      {
        "max": 2
      }
    ],
    "multiline-ternary": "off",
    "new-cap": "warn",
    "new-parens": "warn",
    "newline-after-var": [
      "off",
      "always"
    ],
    "newline-before-return": "off",
    "newline-per-chained-call": "off",
    "no-alert": "off",
    "no-array-constructor": "warn",
    "no-await-in-loop": "error",
    "no-bitwise": "warn",
    "no-buffer-constructor": "off",
    "no-caller": "error",
    "no-case-declarations": "error",
    "no-catch-shadow": "error",
    "no-class-assign": "error",
    "no-compare-neg-zero": "error",
    "no-cond-assign": "error",
    "no-confusing-arrow": "error",
    "no-console": "off",
    "no-const-assign": "error",
    "no-constant-condition": "error",
    "no-continue": "warn",
    "no-control-regex": "error",
    "no-debugger": "warn",
    "no-delete-var": "error",
    "no-div-regex": "error",
    "no-dupe-args": "error",
    "no-dupe-class-members": "error",
    "no-dupe-keys": "error",
    "no-duplicate-case": "error",
    "no-duplicate-imports": "error",
    "no-else-return": "warn",
    "no-empty": "error",
    "no-empty-character-class": "error",
    "no-empty-function": "off",
    "no-empty-pattern": "warn",
    "no-eq-null": "error",
    "no-eval": "error",
    "no-ex-assign": "error",
    "no-extend-native": "error",
    "no-extra-bind": "error",
    "no-extra-boolean-cast": "warn",
    "no-extra-label": "warn",
    "no-extra-parens": "off",
    "no-extra-semi": "error",
    "no-fallthrough": "warn",
    "no-floating-decimal": "error",
    "no-func-assign": "error",
    "no-global-assign": "error",
    "no-implicit-coercion": [
      "warn",
      {
        "boolean": true,
        "number": true,
        "string": true
      }
    ],
    "no-implicit-globals": "off",
    "no-implied-eval": "error",
    "no-inline-comments": "off",
    "no-inner-declarations": "error",
    "no-invalid-regexp": "error",
    "no-invalid-this": "off",
    "no-irregular-whitespace": "error",
    "no-iterator": "error",
    "no-label-var": "error",
    "no-labels": [
      "error",
      {
        "allowLoop": false,
        "allowSwitch": false
      }
    ],
    "no-lone-blocks": "off",
    "no-lonely-if": "off",
    "no-loop-func": "error",
    "no-magic-numbers": "off",
    "no-mixed-operators": "off",
    "no-mixed-requires": "off",
    "no-mixed-spaces-and-tabs": "warn",
    "no-multi-assign": "warn",
    "no-multi-spaces": "warn",
    "no-multi-str": "error",
    "no-multiple-empty-lines": "off",
    "no-native-reassign": "error",
    "no-negated-condition": "off",
    "no-negated-in-lhs": "off",
    "no-nested-ternary": "warn",
    "no-new": "error",
    "no-new-func": "error",
    "no-new-object": "warn",
    "no-new-require": "warn",
    "no-new-symbol": "error",
    "no-new-wrappers": "error",
    "no-obj-calls": "error",
    "no-octal": "error",
    "no-octal-escape": "error",
    "no-param-reassign": "off",
    "no-path-concat": "warn",
    "no-plusplus": "off",
    "no-process-env": "error",
    "no-process-exit": "off",
    "no-proto": "error",
    "no-prototype-builtins": "off",
    "no-redeclare": "error",
    "no-regex-spaces": "error",
    "no-restricted-globals": [
      "error",
      "jQuery"
    ],
    "no-restricted-imports": "off",
    "no-restricted-modules": "off",
    "no-restricted-properties": [
      "error",
      {
        "object": "$",
        "property": "each",
        "message": "Use native es2015 forEach."
      },
      {
        "object": "$",
        "property": "camelCase"
      },
      {
        "object": "$",
        "property": "cookie"
      },
      {
        "object": "$",
        "property": "error"
      },
      {
        "object": "$",
        "property": "extend"
      },
      {
        "object": "$",
        "property": "globalEval"
      },
      {
        "object": "$",
        "property": "grep"
      },
      {
        "object": "$",
        "property": "inArray"
      },
      {
        "object": "$",
        "property": "isArray"
      },
      {
        "object": "$",
        "property": "isEmptyObject"
      },
      {
        "object": "$",
        "property": "isFunction"
      },
      {
        "object": "$",
        "property": "isNumeric"
      },
      {
        "object": "$",
        "property": "isPlainObject"
      },
      {
        "object": "$",
        "property": "makeArray"
      },
      {
        "object": "$",
        "property": "map",
        "message": "Use native es2015 map."
      },
      {
        "object": "$",
        "property": "merge"
      },
      {
        "object": "$",
        "property": "noop"
      },
      {
        "object": "$",
        "property": "now"
      },
      {
        "object": "$",
        "property": "parseJSON"
      },
      {
        "object": "$",
        "property": "parseXML"
      },
      {
        "object": "$",
        "property": "trim"
      },
      {
        "object": "$",
        "property": "type"
      },
      {
        "object": "$",
        "property": "proxy",
        "message": "Use native Function.bind."
      },
      {
        "object": "$",
        "property": "when"
      }
    ],
    "no-restricted-syntax": [
      "warn",
      "WithStatement"
    ],
    "no-return-assign": "error",
    "no-return-await": "off",
    "no-script-url": "error",
    "no-self-assign": "error",
    "no-self-compare": "error",
    "no-sequences": "error",
    "no-shadow": [
      "warn",
      {
        "builtinGlobals": false
      }
    ],
    "no-shadow-restricted-names": "error",
    "no-spaced-func": "off",
    "no-sparse-arrays": "error",
    "no-sync": "off",
    "no-tabs": "off",
    "no-template-curly-in-string": "error",
    "no-ternary": "off",
    "no-this-before-super": "error",
    "no-throw-literal": "error",
    "no-trailing-spaces": "warn",
    "no-undef": "error",
    "no-undef-init": "error",
    "no-undefined": "warn",
    "no-underscore-dangle": "off",
    "no-unexpected-multiline": "error",
    "no-unmodified-loop-condition": "warn",
    "no-unneeded-ternary": "warn",
    "no-unreachable": "error",
    "no-unsafe-finally": "error",
    "no-unsafe-negation": "error",
    "no-unused-expressions": "error",
    "no-unused-labels": "error",
    "no-unused-vars": [
      "warn",
      {
        "vars": "all",
        "args": "after-used"
      }
    ],
    "no-use-before-define": [
      "error",
      "nofunc"
    ],
    "no-useless-call": "error",
    "no-useless-computed-key": "warn",
    "no-useless-concat": "warn",
    "no-useless-constructor": "error",
    "no-useless-escape": "warn",
    "no-useless-rename": "warn",
    "no-useless-return": "warn",
    "no-var": "error",
    "no-void": "error",
    "no-warning-comments": "off",
    "no-whitespace-before-property": "off",
    "no-with": "error",
    "nonblock-statement-body-position": "off",
    "object-curly-newline": "off",
    "object-curly-spacing": [
      "warn",
      "never"
    ],
    "object-property-newline": "off",
    "object-shorthand": "off",
    "one-var": "off",
    "one-var-declaration-per-line": "off",
    "operator-assignment": "off",
    "operator-linebreak": [
      "warn",
      "after",
      {
        "overrides": {
          "?": "ignore",
          ":": "ignore"
        }
      }
    ],
    "padded-blocks": "off",
    "padding-line-between-statements": "off",
    "prefer-arrow-callback": "off",
    "prefer-const": "warn",
    "prefer-destructuring": "off",
    "prefer-numeric-literals": "off",
    "prefer-promise-reject-errors": "off",
    "prefer-reflect": "off",
    "prefer-rest-params": "off",
    "prefer-spread": "off",
    "prefer-template": "off",
    "quote-props": [
      "warn",
      "consistent"
    ],
    "quotes": [
      "warn",
      "single",
      "avoid-escape"
    ],
    "radix": "error",
    "require-await": "off",
    "require-jsdoc": "off",
    "require-yield": "error",
    "rest-spread-spacing": "off",
    "semi": [
      "warn",
      "always"
    ],
    "semi-spacing": [
      "warn",
      {
        "before": false,
        "after": true
      }
    ],
    "semi-style": "off",
    "sort-imports": "off",
    "sort-keys": "off",
    "sort-vars": "off",
    "space-before-blocks": "warn",
    "space-before-function-paren": [
      "warn",
      {
        "anonymous": "always",
        "named": "never"
      }
    ],
    "space-in-parens": "off",
    "space-infix-ops": "off",
    "space-unary-ops": "off",
    "spaced-comment": [
      "off",
      "always"
    ],
    "strict": [
      "error",
      "global"
    ],
    "switch-colon-spacing": "off",
    "symbol-description": "off",
    "template-curly-spacing": "error",
    "template-tag-spacing": "off",
    "unicode-bom": [
      "error",
      "never"
    ],
    "use-isnan": "error",
    "valid-jsdoc": [
      "warn",
      {
        "prefer": {
          "return": "returns",
          "argument": "param",
          "arg": "param",
          "constructor": "class",
          "virtual": "abstract"
        },
        "preferType": {
          "Boolean": "boolean",
          "Number": "number",
          "String": "string",
          "object": "Object",
          "array": "Array",
          "date": "Date"
        },
        "matchDescription": ".+",
        "requireParamDescription": true,
        "requireReturnDescription": true,
        "requireReturn": false,
        "requireReturnType": true
      }
    ],
    "valid-typeof": "error",
    "vars-on-top": "error",
    "wrap-iife": [
      "error",
      "outside"
    ],
    "wrap-regex": "off",
    "yield-star-spacing": "error",
    "yoda": [
      "error",
      "never",
      {
        "exceptRange": true
      }
    ]
  },
  "parserOptions": {
    "ecmaVersion": 8
  },
  "extends": [
    "eslint:recommended",
    "./eslintDefaults.json"
  ],
  "plugins": []
}

