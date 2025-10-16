# Harry-Potter-RAG-Chatbot
A RAG chatbot on the Harry Potter book series built on n8n

<img width="1168" height="593" alt="Screenshot 2568-10-12 at 05 04 37" src="https://github.com/user-attachments/assets/5aa7602f-d81b-4b9f-a0ee-2a67b6d4f247" />

### Try it out at:
* https://chonmycareer.app.n8n.cloud/webhook/365543c5-3506-4724-becc-08ec17067bf1/chat
* username: test01
* password: piwfew-nyvzod-7kIpmo
* #### Note that there's a bug on n8n hosted chat when using chat response node as shown in the image where the chat would only briefly show loading animation but it will eventually give a response correctly. This is a bug on n8n itself. If you are using my json template, disconnect the link to evaluation step and edit the "chat trigger node" to not use "respond to chat node"

## Descriptions
* Hosted on n8n platform
* OpenAI GPT-4o mini based
* RAG on Qdrant vector database
* OpenAI text-embedding-3-large
* Evaluation using GPT-4o mini, 100% Accuracy based on 100 domain specific trivia questions
* The chatbot is configured to give excerpts from the book to support its answer whenever possible

<img width="1060" height="126" alt="Screenshot 2568-10-12 at 04 35 31" src="https://github.com/user-attachments/assets/aabca89b-2db7-4c1a-8752-b29320c5ddcc" />
<img width="1066" height="962" alt="Screenshot 2568-10-17 at 05 20 30" src="https://github.com/user-attachments/assets/9bc4d0b9-7a33-419b-951e-c58be7023d4a" />
<img width="1066" height="962" alt="Screenshot 2568-10-17 at 05 22 29" src="https://github.com/user-attachments/assets/4bf5c9dc-7826-421f-bfec-d6f5f3295257" />
