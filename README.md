# Mind Terminal

## Overview

Terminal large language model client implemented using Python

## Technology Stack

  * Use the [prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) to handle user input and interaction.
  * Interact with the backend large language model service using [openai-python](https://github.com/openai/openai-python)
  * Use the [rich](https://github.com/Textualize/rich) library to beautify terminal display.
  * Use [Pytest testing](https://github.com/pytest-dev/pytest) ensures the correctness of each module and function.

## Features

  * [x] Handle user input
  * [x] Interact with the backend large language model
  * [ ] write unitests for interact with LLM.
  * [ ] Beautify terminal display.

## Installation

Ensure you are using Python 3.11 or later (but less than 4.0).

``` shell
pip install mindterm --user
```

## Usage

``` shell
mt
```

## Testing

Tests for the app are included using [pytest](https://docs.pytest.org/). To run the tests, simply execute:

```bash
pytest
```

## Contributing

Contributions are welcome! If you have ideas for improvements, bug fixes, or additional features, feel free to open an issue or submit a pull request.

## License

rich-chat-room is open-source software released under the [MIT License](./LICENSE).
