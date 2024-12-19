# Advanced Prompt Engineering Workshop
- Seattle - 2024-12-13
- SF - 2024-12-19

Thanks for your interest in attending the Advanced Prompt Engineering Workshop. In order to get the most out of the workshop, please follow the instructions below to set up your development environment ahead of time.

## Setup Requirements

1. Install either VSCode or Cursor.
2. Install the BAML VSCode extension.
3. Clone this repository.
4. Ensure you have python >= 3.10 installed.
    - Install UV. See: https://docs.astral.sh/uv/getting-started/installation/
5. Ensure you have node >= 18.0.0 installed.
    - Install npm.

## Project specific dependencies

Install all python dependencies by running the following command in the `python` directory:

```sh
cd python
uv sync
```

Install all typescript dependencies by running the following command in the `typescript` directory:

```sh
cd typescript
npm install
```

Turn BAML code --> python and typescript code by running the following command in the `python` directory:

```sh
cd python
uv run baml-cli generate --from ../baml_src
```
