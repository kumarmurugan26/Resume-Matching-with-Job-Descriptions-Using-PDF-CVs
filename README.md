# Resume-Matching-with-Job-Descriptions-Using-PDF-CVs
# Usage

## PDF Data Extraction
- Download the Kaggle "resume dataset."
- Run the PDF extractor script to extract details from CVs in PDF format.
- Key details extracted include:
  - Category (job role)
  - Skills
  - Education (degree, institution)

## Job Description Data Understanding
- Use the Hugging Face datasets library to fetch job descriptions.
- Consider extracting 10 job descriptions.

## Candidate-Job Matching
- Tokenize and preprocess job descriptions and extracted CV details.
- Convert the tokenized text into embeddings using a pretrained model like DistilBERT from Hugging Face.
- Calculate cosine similarity between job descriptions and CVs.
- Rank CVs based on similarity scores.

# Data Sources
- Kaggle Resume Dataset ([Provide a link](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset))
- Hugging Face Job Descriptions Dataset ([Provide a link](https://huggingface.co/datasets/jacob-hugging-face/job-descriptions/viewer/default/train?row=0))

# Methodology
- PDF extraction with PyPDF2 or PDFMiner.
- Text tokenization and embedding using DistilBERT from Hugging Face.
- Cosine similarity calculation for candidate-job matching.

# Results
- List the top 5 candidates for each job description based on the highest similarity scores.

# Challenges
- "One of the primary challenges encountered during this project was developing a robust PDF extractor that could consistently and accurately extract key details such as job roles, skills, and education information from a variety of resume PDF formats, which often differed in structure and layout."
- Processing a large number of resumes and job descriptions efficiently to provide timely matching results can be resource-intensive.
# Contact
- kumarmurugantamil@gmail.com
