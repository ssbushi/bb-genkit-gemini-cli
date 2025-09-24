# Genkit Gemini CLI Extension

This package provides a standalone `gemini-cli` extension for [Genkit](https://firebase.google.com/docs/genkit).

This extension provides `gemini-cli` with instructions and guidelines when interacting with Genkit applications. It also installs the Genkit tools MCP server configuration.

## Installation

To use this extension, you need to have `gemini-cli` and `genkit` installed.

⚠️ Important

This extension relies on `genkit` CLI installed through [NPM](https://www.npmjs.com/package/genkit-cli?activeTab=readme).

1.  Install the extension:
    ```shell
    gemini extensions install genkit
    ```
2.  Configure `gemini-cli` to use the extension by updating your configuration file.

## Usage

Once installed and configured, Gemini CLI will have a better understanding of Genkit and can use Genkit tool to improve your app.

For example, you can create a new flow:

```shell
> Write a flow that tests an input string for profanity.
```

Or build and improve your existing Genkit app:

```shell
> Write an evaluator with a sample dataset for my `profanityCheckerFlow`
```

## Development

This repository contains the source code for the Genkit Gemini CLI extension.

See [CONTRIBUTING.md](docs/contributing.md) for more information about contributing to this project.

Every file containing source code must include copyright and license
information.

Apache header:

    Copyright 2024 Google LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
