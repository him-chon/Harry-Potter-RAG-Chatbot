# Harry-Potter-RAG-Chatbot
A RAG chatbot on the Harry Potter book series built on n8n

<img width="1168" height="593" alt="Screenshot 2568-10-12 at 05 04 37" src="https://github.com/user-attachments/assets/5aa7602f-d81b-4b9f-a0ee-2a67b6d4f247" />

* #### Note that there's a bug on n8n hosted chat when using chat response node as shown in the image where the chat would only briefly show loading animation but it will eventually give a response correctly. This is a bug on n8n itself. If you are using my json template, disconnect the link to evaluation step and edit the "chat trigger node" to not use "respond to chat node"

## Descriptions
* Hosted on n8n platform
* OpenAI GPT-4o mini based
* RAG on Qdrant vector database
* Each vector is a 1,000 words chunk with 200 words overlap
* Embeded using OpenAI text-embedding-3-large
* Evaluation using GPT-4o mini, 100% Accuracy based on 100 domain specific trivia questions
* The chatbot is configured to give excerpts from the book to support its answer whenever possible

<img width="1060" height="126" alt="Screenshot 2568-10-12 at 04 35 31" src="https://github.com/user-attachments/assets/a2a8f1de-cbcf-4321-a0a9-afc587bcb510" />
<img width="1068" height="962" alt="Screenshot 2568-10-17 at 06 16 05" src="https://github.com/user-attachments/assets/d70b5230-a375-4555-b1c9-82b18eea7864" />
<img width="1068" height="962" alt="Screenshot 2568-10-17 at 06 17 27" src="https://github.com/user-attachments/assets/15cd4912-4cdb-4df9-b868-1ec834afe938" />
<img width="1068" height="962" alt="Screenshot 2568-10-17 at 06 18 38" src="https://github.com/user-attachments/assets/c3d37762-8141-4944-b826-05127a31e800" />

