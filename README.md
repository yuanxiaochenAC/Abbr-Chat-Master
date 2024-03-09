# Abbr Chat Master

## Project Overview
Abbr Chat Master is a project that leverages the ChatGPT API to process questions from SPA survey questionnaires. Given a sentence from a questionnaire that conveys specific information, Abbr Chat Master can condense its meaning into a concise, coherent phrase.

## Dataset
The project uses an example dataset stored in `data.xlsx`, which contains 5 randomly extracted questionnaire questions. In the current stage, the ChatGPT-4.0 model has been used to process the sample inputs from `data.xlsx` in four identical trials, and the results are compared in `test_outcome.xlsx`.
![image](https://github.com/yuanxiaochenAC/Abbr-Chat-Master/assets/46996371/4a8451cb-a23e-43d3-b818-7ad8c9cf7329)

## Files
- `Chat_API.ipynb`: Notebook containing functions to call the ChatGPT API.
- `instruction.txt`: File containing prompts for the ChatGPT model.
- `Chat_Abbr_Master.ipynb`: Main project notebook.

## Usage
To use the Chat_Abbr_Master project, you need to configure the ChatGPT API in your system's environment variables.

## Future Plans for Improvement
1. **Project Management**: Add code modules to record processing time and token consumption. To address potential large-scale text processing and instability or disconnection of the ChatGPT API during long working hours, plan to add a project control module that pauses for 1 second after every 50 processing attempts.
2. **Model Optimization**: Considering the high cost of ChatGPT-4.0, the project will test other models like GPT-3.5 Turbo and text-davinci-003 for performance in the same domain.
3. **Prompt Optimization**: Improve the efficiency and accuracy of prompts used for the ChatGPT model.
4. **Code Optimization**: Include fine-tuning of large models, parameter adjustments, and the introduction of model evaluation modules.
