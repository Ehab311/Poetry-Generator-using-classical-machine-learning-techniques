# Poetry Generation System

## Overview

This repository contains code for generating poetry using Markov chains and Bayesian networks. The system analyzes a collection of poetry texts, learns the patterns of word transitions, and then generates new poetry based on those patterns.

## Code Files

- `poetry_generation.py`: Python script containing the main code for generating poetry using Markov chains and Bayesian networks.
- `requirements.txt`: Text file listing all the dependencies required to run the code.

## Usage

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
    ```
    git clone <repository_url>
    ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using pip:
    ```
    cd poetry-generation
    pip install -r requirements.txt
    ```

3. **Run the Code**: Execute the `poetry_generation.py` script to generate poetry. Follow the prompts to specify the first word(s) of the poem and the desired length.

## Features

- **Markov Chain Poetry Generation**: The system uses a Markov chain to model the probabilities of word transitions in poetry texts. It then generates new poetry by sampling from these probabilities.
- **Bayesian Network Poetry Generation**: Additionally, the system employs a Bayesian network to capture more complex dependencies between words. It learns from the poetry corpus and generates new poems based on these learned dependencies.
- **Poet Style Generation**: The generated poems attempt to mimic the style of the poets in the training corpus by following specific line structures.
  
## Example

```bash
# Run the poetry generation system
python poetry_generation.py
