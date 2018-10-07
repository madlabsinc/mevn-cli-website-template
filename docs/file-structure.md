# File Structure

## File Hierarchy
Modules are the way of organising different domain-specific modules in the project. MEVN-CLI contains the following Modules.

```
├── Post
└── __Mevn-Cli__- // all the tests for this module goes here
    └── Lib // Sub components of this module
        ├── Commands
        │   └── routeslib.js
        │   └── configlib.js
        │   └── modelslib.js
        │   └── controllerlib.js
        │   └── files
        │
        ├── External // Sub components of this module
        │   └── figlet.js
        │
        ├── Run // Sub components of this module
        │   └── client.js
        │   └── server.js
        │
        ├── config.json
        ├── index.js
        ├── package-lock.json
        └── package.json
```