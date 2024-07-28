# Chess Commentary Generation Documentation
## Project Overview
The Chess Commentary Generation project leverages advanced language model technology to generate insightful and engaging chess commentary. The core of this project is built around the Mistral-7B-Instruct-v0.1 language model, which has been fine-tuned using commentary scripts from International Master (IM) Sagar Shah. By utilizing these scripts, the model can produce high-quality commentary that captures the nuances and excitement of chess matches.

## Key Components
### Language Model
- Model: Mistral-7B-Instruct-v0.1
- Fine-Tuning Method: qLora (Quantized Low-Rank Adaptation)
### Data Source: Commentary scripts from Sagar Shah's YouTube videos

### Data Collection
A YouTube playlist consisting of around 100 videos of chess matches commentated by IM Sagar Shah was scraped and cleaned. The extracted data was preprocessed and formatted to be suitable for instruct fine-tuning the Mistral-7B-Instruct-v0.1 model.

### Fine-Tuning Process
- Dataset Preparation: The commentary scripts were cleaned, formatted, and annotated to facilitate instruct fine-tuning.
- Fine-Tuning Method: qLora (Quantized Low-Rank Adaptation) was used to adapt the pre-trained Mistral-7B-Instruct-v0.1 model to the specific task of generating chess commentary.
