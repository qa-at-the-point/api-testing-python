# API Testing in Python

A collection of recipes, examples, and tests around Web API Testing in Python

- [Examples](#examples)
- [Setup](#setup)
- [Run Tests](#run-tests)
- [Submit a Bug or Request](#submit-a-bug-or-request)

## Examples

Current examples, recipes, etc., that exist in this repo:

- [How to send a Bearer Token in the Authorization header](https://github.com/qa-at-the-point/api-testing-python/blob/main/auth/test_bearer_token_auth.py)
- [How to use data from one response in another request](https://github.com/qa-at-the-point/api-testing-python/blob/main/flows/test_use_data_from_response_in_another_request.py)

## Setup

- 🐍 **_Python v3.8_** or higher is required
- 📦 **_Poetry_** as the package manager
- 👨🏽‍💻 Microsoft's Python extension installed in VSCode

1. Clone the repo

   ```bash
   git clone https://github.com/qa-at-the-point/api-testing-python.git
   ```

2. Install packages with Poetry

   ```bash
   # Installs all packages from pyproject.toml file
   poetry install

   # Then copy the path of the virtual environment
   poetry env info --path
   ```

3. Configure VSCode to use the proper virtual environment

   - Open Command Palette (`CMD + SHIFT + P` or `CTRL + SHIFT + P`)
   - Find and click `Python: Select Interpreter`
   - Paste the virtual environment path if it's not listed

## Run Tests

Examples and Recipes should include the instructions and commands to run the tests.
However, the base command is always the same:

```bash
poetry run pytest
```

## Submit a Bug or Request

If you've found an bug or you have an idea or feature request, please create an issue on the [Issues Tab](https://github.com/qa-at-the-point/api-testing-python/issues)
