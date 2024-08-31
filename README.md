Text and Document Summarization App
This project is a web application designed to simplify the process of summarizing text and documents, leveraging the capabilities of Streamlit and txtai. The application provides an intuitive interface for users to either input text directly or upload PDF documents, with the goal of generating concise summaries.

Features
Text Summarization: Users can enter any text into a text area, and the application will generate a summary using the txtai library's Summary pipeline. The summarization is executed efficiently, ensuring that key points are captured and presented in a concise format.

Document Summarization: The application allows users to upload PDF files. The text is extracted from the first page using PyPDF2, and the extracted content is then summarized. This feature is particularly useful for quickly digesting lengthy documents by obtaining a summary of the main ideas.

Interactive UI: The application features a user-friendly interface built with Streamlit, offering a sidebar for navigation between text and document summarization options. The layout is responsive, utilizing Streamlit's column feature to display the original text or document alongside its summary for easy comparison.

Caching for Performance: To improve performance and user experience, the application implements caching using @st.cache_resource. This reduces processing time by reusing previous computations for repeated operations.

Installation
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the application with streamlit run app.py.
Usage
Summarize Text: Enter text in the provided area and click "Summarize Text" to generate a summary.
Summarize Document: Upload a PDF document, and the app will extract the text and provide a summary.
This project showcases the integration of natural language processing tools with an easy-to-use web interface for text and document summarization tasks.


#Workable link
https://summarry.streamlit.app/
