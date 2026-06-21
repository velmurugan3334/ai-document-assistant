📄 AI Document Assistant

A lightweight web app that lets you paste any document and ask questions about it in a chat-style interface. Built as a hands-on way to learn how AI can be integrated into real workflows, especially documentation-related ones.

Live Demo

What it does :

Paste any block of text (a document, an article, notes, etc.)
Ask questions about that content in plain English
Get instant AI-generated answers based only on the document provided
Ask multiple follow-up questions — the conversation history is kept on screen
Clear the chat and start fresh anytime


Why I built this

I work as a Technical Writer, and a large part of that role involves helping people quickly find and understand information inside long documents. This project was my way of exploring how AI can make that process faster — instead of manually searching through pages of content, a user can just ask a question and get a direct answer.

It was also my first hands-on project integrating an AI API into a working application, built from scratch to understand the full flow: frontend, API calls, prompt design, and handling responses.

Tech stack


HTML, CSS, JavaScript (no frameworks — built from the ground up)
Google Gemini API for AI-generated answers
Hosted on GitHub Pages


How it works


The user's document and question are combined into a single prompt
The prompt is sent to the Gemini API using a fetch request
The AI's response is displayed in the chat window as a new message bubble
Previous questions and answers stay visible so context isn't lost

Running it locally

Clone or download this repository
Get a free API key from Google AI Studio
Open index.html in a text editor and replace YOUR_GEMINI_API_KEY_HERE with your key
Open index.html in your browser

Note: The API key is intentionally left as a placeholder in this public repository for security reasons. Add your own key locally to run the project.

Possible future improvements


Support uploading actual files (PDF, DOCX) instead of pasting text
Move the API key to a backend service instead of the frontend
Add support for longer documents by splitting them into sections
Save chat history between sessions



Built by Velmurugan as a self-learning project to explore AI integration in real-world tools
