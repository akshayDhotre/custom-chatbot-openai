# Custom Chatbot with OpenAI Models

## Instructions

### Project Instructions

Work for this project is completed in the Jupyter Notebook titled `project.ipynb`. 

1. **Choose a Dataset and Explain the Scenario**

   - Select a dataset as per instructions.
   - Write a paragraph explaining which dataset you are using and why.

2. **Prepare the Dataset for the Custom Query Process**

   - Format the chosen dataset so it can be loaded as a pandas DataFrame with a column named "text".
   - Use any software you prefer to reshape or clean the data. Upload the cleaned data file to the `data` folder and use pandas to load it.

3. **Perform the Custom Query Process**

   - Integrate your dataset with the custom query code provided. Ensure you are using your custom dataset, not one from the course content.

4. **Write Questions to Demonstrate Custom Performance**

   - In the last cells of the notebook, write at least two questions that show how the model answers differently with and without your custom prompt.

### Local Machine Requirements

- Python 3.9
- An environment containing the dependencies listed in the `requirements.txt` file

## Repository Structure

```
project-repo/
├── dataset.csv
├── project.ipynb
├── requirements.txt
└── README.md
```

- `dataset.csv`: Contains the dataset used for the project.
- `project.ipynb`: Jupyter Notebook with the project tasks.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Project overview and instructions.

## How to Run

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd project-repo
   ```

2. **Set up the environment**:
   ```bash
   python3.9 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook project.ipynb
   ```

4. **Follow the instructions in the notebook to complete the project tasks**.


## References

[Generative AI NanoDegree](https://www.udacity.com/course/generative-ai--nd608)