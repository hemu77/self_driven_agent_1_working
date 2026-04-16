# Self Driven Agent 1 Working

This repository contains a notebook experiment that explores LLM-assisted data analysis inside a notebook workflow.

## Project Overview

The notebook installs analysis dependencies, configures an LLM client, and defines helper logic for asking analytical questions about a pandas DataFrame. The current repo is lightweight and centered around a single notebook rather than a larger application structure.

## Files

| File | Description |
| --- | --- |
| `test.ipynb` | Main notebook for the agent-style analysis experiment |

## Workflow Summary

Based on the notebook structure, the workflow includes:

1. Installing notebook dependencies such as `plotnine`, `litellm`, and `datasets`.
2. Importing pandas, plotting tools, and LLM-related libraries.
3. Configuring a logger and initializing an LLM client.
4. Defining helper functions that analyze a DataFrame and answer targeted analytical questions.

## Inputs / Environment

The notebook expects a Python notebook environment with the required packages installed. It also appears to rely on external model API configuration in order to run the LLM-assisted portions successfully.

## Outputs

This repository currently stores only the notebook. Any charts, answers, or analysis artifacts are produced interactively during notebook execution.

## Notes

- The repo is in an experimental state and does not yet include a packaged script, reproducible environment file, or exported results.
- A good next cleanup step would be separating secrets/configuration from notebook code and adding a requirements file for repeatable setup.
