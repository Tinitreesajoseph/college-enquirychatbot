# college-enquirychatbot
Overview
This chatbot helps students and stakeholders with information about engineering and polytechnic institutes under the Department of Technical Education, Government of Rajasthan. It uses advanced technologies to provide real-time responses.

Technologies Used
Streamlit: Builds the chatbot's web interface.
Google Gemini AI: Generates responses to user queries.
Pinecone: Stores and retrieves data for the chatbot.
Sentence Transformers: Converts text into vectors for searching.
BeautifulSoup: Scrapes data from web pages.
JSON: Stores data in a readable format.
Python: The core programming language for the project.
How It Works
User Interaction: Users chat through the Streamlit interface.
Query Processing: User queries are turned into vectors.
Context Retrieval: Relevant information is fetched from Pinecone.
Response Generation: Responses are created using Google Gemini AI.
Output: Responses are shown in the chat interface.
Getting Started
Clone the repo: git clone <repository-url>
Install dependencies: pip install -r requirements.txt
Set up API keys and configuration.
Run the app: streamlit run app.py
References
Google Gemini AI
Pinecone
Streamlit Documentation
BeautifulSoup
Sentence Transformers
