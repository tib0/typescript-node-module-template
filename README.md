# INTRODUCTION
Sample node module boilerplate by Tib0


# WARNING
Warning triggered when using eslint in version 9.1.1 due to unmet dependency

> "eslint": "^9.1.1" cause WARN  Issues with peer dependencies found
```txt
.
├─┬ @typescript-eslint/eslint-plugin 7.7.1
│ ├── ✕ unmet peer eslint@^8.56.0: found 9.1.1
│ └─┬ @typescript-eslint/type-utils 7.7.1
│   ├── ✕ unmet peer eslint@^8.56.0: found 9.1.1
│   └─┬ @typescript-eslint/utils 7.7.1
│     └── ✕ unmet peer eslint@^8.56.0: found 9.1.1
└─┬ @typescript-eslint/parser 7.7.1
  └── ✕ unmet peer eslint@^8.56.0: found 9.1.1
```