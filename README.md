# Florence2 ONNX Runtime Example

Welcome to the Florence2 ONNX Runtime Example repository! This project demonstrates how to use Florence2 with ONNX Runtime in a C++ environment.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Model Download](#model-download)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository provides a basic example of integrating Florence2, a deep learning model, with ONNX Runtime in C++. The example showcases how to load and run inference using pre-trained Florence2 models.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Bazel](https://bazel.build/)
- A C++ compiler (GCC, Clang, MSVC, etc.)

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/d61h6k4/florence2.cpp.git
   cd florence2.cpp
   ```

2. **Install Dependencies**

### Model Download

Download the Florence2 models from the following link and place them in the appropriate directory within the project:

- [Florence2 Models](https://huggingface.co/onnx-community/Florence-2-base-ft/tree/main/onnx)

## Usage

To run the example, use the following command:

```sh
bazel run //florence2:example
```

This command will build and execute the C++ example that loads the Florence2 model and performs inference using ONNX Runtime.

## Contributing

We welcome contributions to enhance this example! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for using Florence2 with ONNX Runtime! If you have any questions or need further assistance, please feel free to open an issue in the repository.

Happy coding!
