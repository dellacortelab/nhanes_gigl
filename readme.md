# NHANES_GIGL

This repository contains the code for the paper "Development of a national database for dietary glycemic index and load for nutritional epidemiologic studies in the United States" by Karen A. Della Corte, Dennis Della Corte, Sean Titensor, Bo Yang, Simin Liu. The code is released under the MIT License.

## Tutorial

A tutorial explaining the process used in the paper is provided in a Google Colab format. You can find the tutorial [here](https://github.com/dellacortelab/nhanes_gigl/blob/main/tutorial/Dietary_GI_GL_Tutorial.ipynb).

## Alignment Code

The alignment code to generate initial GI database alignments with NHANES food groups is provided as an IPython notebook (`.ipynb`). You can find the code [here](https://github.com/dellacortelab/nhanes_gigl/blob/main/src/ai_alignment.ipynb).

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

## Data Sharing Policy
This repository contains code related to our GI/GL database research, but does not include the full national glycemic index (GI) and glycemic load (GL) database itself. The GI/GL database is maintained and updated by the lead authors at Brigham Young University. We will share the database for non-commercial research usage with qualified investigators through collaborative efforts under the following process:

1. Interested researchers should submit a proposal to the project PIs (karen_dellacorte@byu.edu, dennis.dellacorte@byu.edu) specifying the proposed analysis and which components of the GI/GL database will be utilized.
2. A signed data use agreement must be provided covering all analysts who will access the data.
3. Formal data requests can then be made to the project team, who will securely transfer the files.
4. Annual status updates on data usage are required.

Please contact the PIs if you have any other questions about accessing this data.
