# BMW Coding Challenge

# Code Documentation

This repository contains code that performs various operations on user prompts. The code is divided into several functions, each serving a specific purpose.

## Prerequisites

Make sure you have the following libraries installed:

- re
- nltk

This code contains functions for validating user prompts, extracting model type codes, identifying indices, evaluating boolean expressions, extracting dates, and generating a request body based on the user's input.

## Steps

1. Importing necessary libraries.
2. Function `validate_prompt(prompt)` to validate the user prompt on several conditions.
3. Function `extract_model_type_code(text)` to extract the model type code from the input text.
4. Function `get_first_last_idx(array, key)` to identify the first and last index of a given key in an array.
5. Function `eval_bool_exp(expression)` to evaluate a boolean expression and convert it into a standardized format.
6. Declaration of a dictionary for respective keys.
7. Function `generateBooleanExpression(input_text)` to generate the final boolean expression.
8. Function `extract_dates(prompt)` to extract year, month, and day from the input prompt and return it in the format "YYYY-MM-DD".
9. Function `build_request_body(prompt)` to generate the final request body by calling the necessary functions.
10. Collect the number of prompts from the user and the prompts themselves, and process each input prompt.

## Usage

1. Ensure that the required libraries are installed (such as nltk).
2. Import the code file into your project or environment.
3. Use the provided functions based on your requirements.
4. Call the `build_request_body(prompt)` function to generate the request body for a given prompt.
5. Provide a valid prompt and follow the instructions to get the desired output.

Please note that this code assumes the availability of necessary libraries and their correct installation. Make sure to review and customize the code as per your specific needs.
