# GPT Explainer

GPT Explainer is a web application that allows users to upload PowerPoint files and receive short explanations for the content within the presentations. It utilizes the OpenAI GPT-3.5 Turbo model to generate these explanations and manages the data using SQLAlchemy for database management. This README provides an overview of the project's structure and how to set it up.

## Prerequisites

Before running the GPT Explainer web application, ensure you have the following prerequisites installed on your system:

- Python (version 3.7 or higher)
- OpenAI API key (sign up and obtain an API key from OpenAI)
- Flask (install via `pip install flask`)
- SQLAlchemy (install via `pip install sqlalchemy`)

## Project Structure

The GPT Explainer project consists of several components and files:

1. **WebApi.py**: This is the main Flask script that handles file uploads and status retrieval from the users.

2. **extract_text.py**: Contains functions to read PowerPoint presentations and extract text from the slides.

3. **chatgpt.py**: This module is responsible for interacting with the GPT-3.5 Turbo model to generate explanations based on the extracted text.

4. **database.py**: Manages the database models and setup using SQLAlchemy.

5. **templates folder**: Contains HTML templates for rendering the web pages. These templates are used to create the user interface for the application.

6. **uploads folder**: Stores the uploaded PowerPoint presentations.

7. **outputs folder**: Stores the generated explanations for the uploaded presentations.

## Getting Started

To get started with the GPT Explainer web application, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages using `pip`.
3. Set up your OpenAI API key by replacing YOUR_API_KEY in chatgpt.py with your actual API key.
4. Start the Flask web server
5. Start the chatgpt script
6. Open a web browser and navigate to http://localhost:5000 to access the GPT Explainer web application.

## Usage

To get started with the GPT Explainer web application, follow these steps:

1. Upload a PowerPoint file using the web interface.
2. The application will process the file, extract text from the slides, and then generate a short explanation for the presentation content using the GPT-3.5 Turbo model.
3. Users can view and download the generated explanations.


Enjoy using the GPT Explainer web application! 
