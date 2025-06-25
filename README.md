# Mars_Project
In this project, I developed a tool that can read documents such as PDFs, Word files (.docx), and text files (.txt), and automatically generate useful information (called metadata) about them. This helps people understand what the document is about without having to read the entire thing.
First, the tool reads the document and gets the full text from it. If the document is scanned or doesn't have real text (like some PDFs), it uses OCR to read the text from images. After getting the text, I split it into smaller parts called "chunks" so that it's easier to understand.
Then, I used Google’s Gemini AI model to summarize each chunk. This is called the "map" step. After that, I combined all the summaries and again used the AI to create the final metadata, like the main summary, number of words, file name, and other details if available. This is the "reduce" step.
At the end, I built a simple web app using Gradio where anyone can upload a document and see the metadata directly. It’s easy to use and shows the output in a clear JSON format.

This project helped me learn how to use AI models, work with different file types, and build a complete application from start to finish.
