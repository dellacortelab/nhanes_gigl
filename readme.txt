# NHANES_GIGL

This repository contains the code for the paper "Development of a national database for dietary glycemic index and load for nutritional epidemiologic studies in the United States" by Karen A. Della Corte, Dennis Della Corte, Sean Titensor, Bo Yang, Simin Liu. The code is released under the MIT License.

## Tutorial

A tutorial explaining the process used in the paper is provided in a Google Colab format. You can find the tutorial here https://github.com/dellacortelab/nhanes_gigl/blob/main/tutorial/Dietary_GI_GL_Tutorial.ipynb.

## Alignment Code

The alignment code to generate initial GI database alignments with NHANES food groups is provided as an IPython notebook (`.ipynb`). You can find the code [here](link-to-alignment-code).

### Running the IPython Notebook

To run the IPython notebook, you need to provide an OpenAI API key to correctly invoke the embedding function. Please follow the instructions below to set up the environment:

1. Obtain an OpenAI API key from [OpenAI](https://openai.com).
2. Set the API key within ai_alignmnet.ipynb in the get_embedding function on line 7.

    ```
    openai_api_key = 'ADD OPENAI API Key here'
    ```

3. Install the required dependencies by running the following command:

    ```bash
    pip install -r requirements.txt
    ```
