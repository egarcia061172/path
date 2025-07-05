# Path Utility 📁

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)

An ESM/Jest friendly path utility designed to simplify file path management in your Node.js projects. This library provides a set of tools for resolving, manipulating, and working with file paths in a straightforward manner.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)
- [Release Notes](#release-notes)

## Features

- **ESM Compatibility**: Fully compatible with ECMAScript Modules for modern JavaScript applications.
- **Jest Integration**: Designed to work seamlessly with Jest for testing.
- **Path Resolution**: Easily resolve relative and absolute paths.
- **Utilities**: A collection of handy functions to manipulate file paths.
- **Node.js Support**: Built specifically for Node.js environments.

## Installation

To install the Path utility, use npm or yarn:

```bash
npm install path
```

or

```bash
yarn add path
```

## Usage

Here’s a simple example of how to use the Path utility in your project:

```javascript
import { resolvePath } from 'path';

const fullPath = resolvePath('./myFolder/myFile.txt');
console.log(fullPath); // Outputs the absolute path
```

## API Reference

### `resolvePath(relativePath)`

- **Description**: Resolves a relative path to an absolute path.
- **Parameters**: 
  - `relativePath` (string): The relative path to resolve.
- **Returns**: A string representing the absolute path.

### `joinPaths(...paths)`

- **Description**: Joins multiple path segments into a single path.
- **Parameters**: 
  - `...paths` (string[]): The paths to join.
- **Returns**: A string representing the joined path.

### `normalizePath(path)`

- **Description**: Normalizes a given path, resolving any `..` or `.` segments.
- **Parameters**: 
  - `path` (string): The path to normalize.
- **Returns**: A string representing the normalized path.

## Contributing

We welcome contributions to the Path utility! If you have suggestions for improvements or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Open a pull request with a description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Release Notes

For the latest releases and updates, please check the [Releases](https://github.com/egarcia061172/path/releases) section. You can download the latest version and execute it to enjoy the new features and improvements.

![Path Utility](https://img.shields.io/badge/path-utility-orange.svg)

## Additional Resources

For more information, visit our [GitHub repository](https://github.com/egarcia061172/path/releases) to explore the documentation, examples, and more.

If you have any questions or need assistance, feel free to open an issue in the repository.

---

Thank you for checking out the Path utility! We hope it makes your file path management easier and more efficient. Happy coding!