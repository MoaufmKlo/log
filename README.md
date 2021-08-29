<div align="center">
    <h1>logger</h1>
    <img alt="npm Version" src="https://img.shields.io/npm/v/@moaufmklo/logger?style=for-the-badge">
    <img alt="npm Downloads" src="https://img.shields.io/npm/dw/@moaufmklo/logger?style=for-the-badge">
    <br>
</div>

## Table of contents
- [Table of contents](#table-of-contents)
- [About](#about)
- [Installation](#installation)
- [Usage](#example-usage)
- [Links](#links)
- [Contributing](#contributing)

## About

Dependency-free [Node.js](https://nodejs.org/) module for simple, rotating, file-based logging

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install logger:

```bash
npm install @moaufmklo/logger
```

## Usage

```javascript
const Logger = require("@moaufmklo/logger");
const logger = new Logger({
    "logsPath": "./logs/"
});

logger.log("info", "An information log.");
logger.log("warn", "A warning log.");
logger.log("error", "An error log.");
```

## Links

- [npm](https://www.npmjs.com/package/@moaufmklo)
- [GitHub](https://github.com/MoaufmKlo/logger)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.