# Prompt_Engineering

## Project Overview
The primary objective of this project is to showcase the versatility and control achievable through effective prompt engineering. It illustrates how to guide LLMs to perform specific tasks, adapt their output style, extract structured information, and manage creativity levels.

## Key Assignments and Concepts Demonstrated

### 1. Customer Review Classification
Objective: To classify customer reviews into predefined categories (e.g., "Delivery Issues," "Product Quality," "General Feedback").

Methodology: The notebook demonstrates how to provide the LLM with a customer review and a set of candidate categories, prompting it to identify the most relevant classification. This highlights the model's capability for contextual understanding and categorization.

### 2. Personalized Email Response Generation
Objective: To compose personalized email responses to customer complaints, varying the tone and style.

Methodology: Two distinct tones are explored:

Casual and Empathetic: Generating friendly and understanding responses.

Formal and Concise: Producing business-oriented and to-the-point replies.
This section emphasizes the importance of tone variation in communication and the LLM's ability to adapt its linguistic style.

### 3. Structured Information Extraction (JSON Format)
Objective: To extract specific data points from unstructured text (e.g., customer reviews) and present them in a structured JSON format.

Methodology: A Python function is implemented to parse a customer review and extract details such as product, operating_system, issue_description, and order_number into a predefined JSON schema. This showcases the LLM's utility in data extraction and preparation for further processing.

### 4. Creative Product Name Generation with Temperature Control
Objective: To generate creative product names for a smart home assistant, demonstrating the impact of the temperature parameter on output creativity.

Methodology: The notebook compares product names generated using:

Low Temperature: Resulting in more deterministic and consistent outputs.

High Temperature: Leading to more creative, varied, and sometimes unexpected outputs.
This assignment provides insights into controlling the randomness and originality of LLM generations, a crucial aspect for creative content generation.

# Technologies Used
Python: The primary programming language for interacting with the LLM APIs.

OpenAI API: Utilized for various text generation and classification tasks.

Google Gemini API: Also used for comparative text generation and classification tasks, demonstrating multi-model capabilities.

Jupyter Notebook: For interactive code execution, documentation, and visualization of results.


# Conclusion
This repository serves as a valuable resource for anyone looking to understand and apply prompt engineering principles to leverage the full potential of large language models. The examples provided offer clear insights into how careful prompt design can lead to more accurate, relevant, and controlled AI-generated content.
