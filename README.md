# Be: Minimal Test Assertions in Go 🐹

![GitHub Release](https://img.shields.io/badge/Release-v1.0.0-brightgreen) [![GitHub](https://img.shields.io/badge/GitHub-Visit%20Repo-blue)](https://github.com/Muzzcodes/be/releases)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

Be is a simple and efficient library for writing minimal test assertions in Go. It aims to provide developers with straightforward tools to ensure code correctness without unnecessary complexity. Whether you are a seasoned Go developer or just starting, Be makes testing easy and effective.

## Features

- **Lightweight**: No heavy dependencies, just pure Go.
- **Simple API**: Easy to understand and use.
- **Flexible**: Works seamlessly with any Go testing framework.
- **Clear Assertions**: Write assertions that are easy to read and maintain.
- **Minimalistic**: Focus on what matters without extra fluff.

## Installation

To install Be, use the following command:

```bash
go get github.com/Muzzcodes/be
```

After installation, you can start using Be in your Go projects. For detailed instructions, visit the [Releases section](https://github.com/Muzzcodes/be/releases) to download the latest version.

## Usage

Using Be is straightforward. Here’s a simple example to get you started:

```go
package main

import (
    "testing"
    "github.com/Muzzcodes/be"
)

func TestExample(t *testing.T) {
    result := 2 + 2
    be.AssertEqual(t, result, 4)
}
```

In this example, we use `be.AssertEqual` to check if the result of `2 + 2` equals `4`. If the assertion fails, Be will provide a clear error message.

## Examples

Here are some more examples to illustrate the capabilities of Be:

### AssertEqual

```go
be.AssertEqual(t, actualValue, expectedValue)
```

### AssertNotEqual

```go
be.AssertNotEqual(t, actualValue, unexpectedValue)
```

### AssertTrue

```go
be.AssertTrue(t, condition)
```

### AssertFalse

```go
be.AssertFalse(t, condition)
```

These assertions help you write clear and concise tests. Each assertion provides meaningful feedback when tests fail, making debugging easier.

## Contributing

We welcome contributions to Be! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request to the main repository.

Your contributions help improve Be for everyone.

## License

Be is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For questions or suggestions, please reach out via GitHub or open an issue in the repository. 

You can also check the [Releases section](https://github.com/Muzzcodes/be/releases) for the latest updates and download links.

--- 

![Go Logo](https://upload.wikimedia.org/wikipedia/commons/0/05/Go_Logo_Blue.svg)

## Topics

- **assert**: Essential for testing frameworks.
- **golang**: Written in Go for Go developers.
- **simple**: Focused on simplicity and usability.
- **testing**: Enhances the Go testing experience.

Explore the power of minimal test assertions in Go with Be!