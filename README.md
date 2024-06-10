# Interview-Question-Creator

This project is a web application designed using the Retrieval-Augmented Generation (RAG) architecture to extract data from PDF files and generate interview questions based on the content. The application utilizes various technologies including FAISS, OpenAI, Langchain, Jinja2, and FastAPI.

### Tech Stack

- Python: The core programming language used for the application.
- FAISS: A library for efficient similarity search and clustering of dense vectors, used here for document retrieval.
- OpenAI: Utilized for generating questions from the extracted content.
- Langchain: Used to manage the language model's pipelines.
- Jinja2: A templating engine for rendering HTML templates.
- FastAPI: The web framework used for building the API.

### Features

- Upload PDF files.
- Extract content from uploaded PDFs.
- Generate interview questions based on the extracted content.
- Download the generated questions in CSV format.

### How to run?:

1. Clone Repository

```
git clone https://github.com/patelshehbaz/Interview-Question-Creator.git
```

2. Create an environment

```
conda create -n interview python=3.10 -y

conda activate interview

```

3. Activate the environment

```
conda activate interview
```

4. Install requirements

```
pip install -r requirements.txt
```

### Access the Application

Open your web browser and navigate to http://127.0.0.1:8000/ to access the application.

### Upload a PDF

1. Use the upload form on the homepage to upload a PDF file.
2. The application will extract content from the uploaded PDF and generate interview questions.
3. Download the generated questions in CSV format.

### Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.

### Where This Tool Will Be Helpful

The Interview Question Creator is particularly useful in the following scenarios:

- Educational Institutions: Teachers and professors can use this tool to generate practice questions for their students based on textbook chapters or lecture notes in PDF format. This helps in creating comprehensive and relevant study material quickly.
- Corporate Training: HR and training departments can create interview questions from company training materials to prepare employees for internal assessments or external certifications, ensuring a thorough understanding of the material.
- Job Seekers: Individuals preparing for job interviews can upload technical manuals, study guides, or other relevant documents to generate potential interview questions, aiding in more focused and effective preparation.
- Content Creators: Authors and content creators can generate discussion questions for their books or articles to engage their audience, facilitating better interaction and understanding of the content.
