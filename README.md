# Overview:
SmartResumeAI is an AI-driven application designed to assist students and job seekers in optimizing their resumes for specific job applications. The motivation behind this project stems from the need to secure internships or employment opportunities during the third year of university. As the job market becomes increasingly competitive, tailoring resumes to match specific job descriptions is crucial for standing out to potential employers.

## Features:
1. Resume Evaluation: Users can upload their resumes along with job descriptions. The application evaluates the resumes based on the provided job descriptions, considering keywords and skills relevant to the job market.

2. Gemini AI Integration: Utilizes the Google Gemini API to generate tailored feedback on the resume. The Gemini AI analyzes the resume against the job description, providing insights into areas of improvement and missing keywords.

3. Customized Assistance: Offers personalized suggestions for enhancing the resume, focusing on key areas such as technical skills, software engineering expertise, data science proficiency, data analysis capabilities, and AI engineering knowledge.

4. Percentage Matching: Provides a percentage match indicating how well the resume aligns with the job description. This metric helps users gauge the suitability of their resumes for specific positions.

5. Missing Keywords Identification: Highlights missing keywords or skills essential for the targeted job role. This feature enables users to address any gaps in their resumes effectively.

6. Profile Summary Generation: Generates a concise profile summary based on the resume content and the job description. This summary serves as a valuable addition to the resume, encapsulating the candidate's qualifications and suitability for the position.

## Usage:
- Upload Resume: Users upload their resumes in PDF format.
- Input Job Description: Users input the job description or paste it into the provided text area.
- Submit: Upon submission, the application processes the resume and job description to provide feedback.
- Review Feedback: Users receive a comprehensive evaluation of their resumes, including the percentage match, missing keywords, and a profile summary.
- Resume Enhancement: Based on the feedback, users can make necessary revisions to their resumes to enhance their suitability for the desired job role.

## Technologies Used:
- Python
- Streamlit (for building the user interface)
- Google Gemini API
- PyPDF2 (for parsing PDF files)

# Installation:
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Set up the necessary environment variables, including the Google API key.
Run the Streamlit application using streamlit run app.py.
