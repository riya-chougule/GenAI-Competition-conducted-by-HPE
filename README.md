# GenAI-Competition-conducted-by-HPE

This repository includes Python notebooks for generating a sophisticated chatbot, RegulEase, empowered by Retrieval Augmented Generation technology and fortified with FDA (Food and Drug Administration) Drug guidelines. Given the FDA's consistent release of thousands of guidelines annually, with over 2100 documents dedicated solely to drugs, our chatbot significantly streamlines user interactions, sparing users the laborious task of manually navigating extensive documentation.

The project workflow encompasses the following steps:
  1. Segmentation of FDA drug guideline PDF documents into multiple data chunks.
  2. Conversion of PDF documents into text embeddings using the text-embedding-ada-002 model.
  3. Storage of embeddings in the Chroma vector database.
  4. Retrieval of user input queries in text format.
  5. Conversion of textual input queries into text embeddings.
  6. Execution of vector similarity search (Cosine similarity) to identify relevant data chunks akin to the user's query.
  7. Integration of user input queries and relevant data chunks, subsequently fed into the Large Language Model (GPT 3.5 Turbo) for sentence formulation.
  8. Presentation of results to the user in a user-friendly interface.
     
Through this comprehensive workflow, the chatbot seamlessly delivers accurate and pertinent responses, leveraging FDA Drug guidelines and facilitating enhanced accessibility and usability through the Gradio interface




*System architecture*
![Code Crafters- Final Presentation](https://github.com/riya-chougule/GenAI-Competition-conducted-by-HPE/assets/60813327/735a270b-d523-41af-a8bc-e65273e76666)



*User Interface of RegulEase*



<img width="1289" alt="Screenshot 2024-03-07 at 10 51 25 PM" src="https://github.com/riya-chougule/GenAI-Competition-conducted-by-HPE/assets/60813327/0f9b5297-d0bc-479e-a632-35039b26985c">


