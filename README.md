# CodeCompletion Plugin

This plugin enables code completion using the llama.cpp server and provides basic functionality for triggering code completion and receiving suggestions.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [License](#license)
- [Todo](#Todo)

## Description

**CodeCompletion** is a plugin designed to facilitate code completion using the llama.cpp server. It integrates with llama.cpp server API.

## Features

- Integration with llama.cpp server API for code completion.
- Support for configuring API key, model selection, and other parameters.
- Basic functionality for triggering code completion and receiving suggestions.
- Support for generating multiple suggestions.

## Installation

To install the **CodeCompletion** plugin, follow these steps:

1. Clone the repository into your plugins directory:

```bash
git clone https://github.com/pedro-design/lite-xl-CodeCompletion-plugin.git
```

2. Restart the editor.

## Configuration

The plugin can be configured via the settings GUI. The following configuration options are available:

- `api_key`: Your API key for accessing the llama.cpp server (if used).
- `model`: The name of the model to use.
- `n_predict`: Number of tokens to generate.
- `temperature`: Sampling temperature.
- `mirostat`: Use mirostat (0 for no, 1 and 2 for its versions).
- `suggestions_tks`: Tokens to generate per suggestion.
- `suggestions_to_sample`: Number of suggestions to generate.
- `stop`: Stop word for the model.
- `end_point`: API endpoint URL.

## Usage

To trigger code completion, use the following keybindings:

- `Alt + C`: Trigger code completion.
- `Alt + S`: Toggle suggestions.

Alternatively, you can access these functionalities through the command palette or change the keybindings in the config of lite-xl.

## Todo
integrate more APIs like OpenAI or Claude

## Disclaimer

This plugin is designed to enable code completion using the server file from llama.cpp. It provides basic functionality for triggering code completion and offers a basic suggestion system. Please note that it calls the API one by one without batching at the moment.

## License

This plugin is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
