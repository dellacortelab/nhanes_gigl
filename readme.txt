# NHANES_GIGL

This repository contains the code for the NHANES_GIGL project. The code is released under the MIT License.

## Tutorial

A tutorial explaining the process used in the paper is provided in a Google Colab format. You can find the tutorial [here](link-to-tutorial).

## Alignment Code

The alignment code to generate initial GI database alignments with NHANES food groups is provided as an IPython notebook (`.ipynb`). You can find the code [here](link-to-alignment-code).

### Running the IPython Notebook

To run the IPython notebook, you need to provide an OpenAI API key to correctly invoke the embedding function. Please follow the instructions below to set up the environment:

1. Obtain an OpenAI API key from [OpenAI](https://openai.com).
2. Set the API key as an environment variable in your local development environment. You can do this by running the following command in your terminal:

    ```bash
    export OPENAI_API_KEY=your-api-key
    ```

3. Install the required dependencies by running the following command:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the IPython notebook and follow the instructions provided in the notebook to run the code.

Please note that the OpenAI API key is required to access the embedding function and should be kept confidential.

## License

This project is licensed under the terms of the MIT License. See the license file for more details.