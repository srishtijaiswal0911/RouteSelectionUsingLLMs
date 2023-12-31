# The Commuter’s Triangle: A Comparative Analysis - Most Optimal Route Selection using LLMs

## Description
This study examines how Language Model Algorithms (LLMs) and human decision-making differ when it comes to route selection optimization. It evaluates factors such as traffic, weather, safety, and amenities; it also evaluates the acceptability, accuracy, and reliability of user preferences and AI-generated route choices. Offering thorough, contextually appropriate advice, the study tackles ideal paths, LLM understanding, and the relative usefulness of models. To improve the precision of suggestions, a variety of datasets are utilized to compare LLM-driven paths to human selections. Initial results show that GPT 3 is more accurate and preferred by users than LLAMA 2 and PALM 2. Contextual awareness designates GPT 3 as the preferred option. Future research aims to improve suggestion accuracy and support a wide range of user requirements.

## Project Images

### Routes from Google API
![Routes from Google API](https://github.com/srishtijaiswal0911/RouteLLM_images/blob/main/GivenRoutes.png?raw=true)
This image displays the three routes fetched from the Google API from Los Angeles to New York. These routes were used as input along with the weather conditions, safety scores, traffic conditions and amenities (like restaurants and gas stations) for each point along the route in the form of a data frame for our Language Model Algorithms (LLMs) to determine the most optimal route based on their analysis.

### GPT 3.5 Output
![GPT 3 Output](https://github.com/srishtijaiswal0911/RouteLLM_images/blob/main/LLM_Gpt_Prompt.jpeg?raw=true)
The output provided by GPT 3, suggesting the most favorable route among the three based on its contextual analysis.

### LLAMA 2 Output
![LLAMA 2 Output](https://github.com/srishtijaiswal0911/RouteLLM_images/blob/main/LLM_LlamaPrompt.jpeg?raw=true)
The output generated by LLAMA 2, showcasing its recommended route among the three options after processing the provided data.

### PALM 2 Output
![PALM 2 Output](https://github.com/srishtijaiswal0911/RouteLLM_images/blob/main/LLM_PalmPrompt.png?raw=true)
The output representation of PALM 2, indicating its suggestion for the optimal route among the given choices leveraging its decision-making process.


## Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab (or any other tool)

### Steps
1. Clone the repository to your local machine.
2. Ensure Python 3.x is installed.
3. Open Jupyter Notebook or Colab.
4. Load the necessary datasets.
5. Navigate to the following files:

    - `LLM_GPT.py`
    - `LLM_LLAMA.py`
    - `LLM_PALM.py`
    - `RoutePlanner_DataFrame_PrepFile.py`
    - `Metrics_weather.py`
    - `Metrics_SafetyScore_Final.py`

6. Run each Python.

7. Once executed, you can download the Dataframefrom the DataPrep File.

8. Then load the Data Frame into the LLMs and explore the outcomes by giving different prompts to see how the LLMs work.

## Features
Highlight the main features or functionalities of the project.

## Project Contributors
- Srishti Jaiswal
- Rashi Pandey

## Project Demo Link
- [Project Demo Youtube Link](https://www.youtube.com/watch?v=-yrybLH2gpU&t=11s)

