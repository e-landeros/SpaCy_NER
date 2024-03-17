# SpaCy NER Fine-tuning

This project is designed to generate synthetic data for fine-tuning a Named Entity Recognition (NER) model using SpaCy. The synthetic data is generated based on a specific template that includes a company name, which is randomly generated. The generated data is then used to train and evaluate a SpaCy NER model to recognize company names within text.


## Installation

To run this project, you need to have Python installed on your system. Additionally, you will need to install the following Python packages:

- spacy
- pandas
- numpy

You can install these packages using pip:

```bash
pip install spacy pandas numpy
python -m spacy download en_core_web_sm
```

## Usage

### Data Generation

Generate Synthetic Data: Run the script to generate synthetic data. This will create a CSV file named `synthetic_data.csv` containing the synthetic data.

### Model Training

Train the Model: Use the generated synthetic data to train a SpaCy NER model. The training script will update the model to recognize company names within text.

### Evaluation

Evaluate the Model: After training, evaluate the model's performance on a test set to measure its accuracy in recognizing company names.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

## License

This project is licensed under the [MIT License](LICENSE).
