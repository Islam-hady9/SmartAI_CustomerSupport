# SmartAI_CustomerSupport

SmartAI_CustomerSupport is an AI-driven customer support assistant built using GPT-2. The project demonstrates how to fine-tune a pre-trained language model on custom customer support data and integrate it into a simple interactive environment.

## Features

- Fine-tunes GPT-2 on customer support data.
- Generates contextually relevant responses to customer queries.
- Interactive Jupyter Notebook for experimentation and testing.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Islam-hady9/SmartAI_CustomerSupport.git
   cd SmartAI_CustomerSupport
   ```

2. Create and activate a conda environment:
   ```bash
   conda create --name smartai_customersupport python=3.8
   conda activate smartai_customersupport
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Open the Project:**
   - Start by opening the `SmartAI_CustomerSupport.ipynb` Jupyter Notebook in your preferred environment (e.g., Jupyter Lab or Jupyter Notebook).

2. **Run the Notebook Cells:**
   - Follow the sequential execution of the cells in the notebook. This will:
     - Load the pre-trained GPT-2 model and tokenizer.
     - Tokenize sample queries.
     - Fine-tune the model if necessary.
     - Generate and display responses to the input queries.

3. **Interact with the Model:**
   - Modify the input queries within the notebook to test the model with different customer support questions.
   - Observe and analyze the generated responses for evaluation.

4. **Experiment and Modify:**
   - Use the notebook to experiment with different hyperparameters, input data, or model configurations to better suit your needs.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
