# Unlocking Data Relationships: Embedding with Large Language Models and Visualizing with Neo4j, Pinecone & Geminidata Explore
This project showcases how to leverage OpenAI's text-embedding-ada-002 model and Pinecone, a vector database, to discover hidden relationships within complex datasets. We organize our data using the Neo4j graph database and visualize the intricate connections using Gemini Explore. The demonstrated example uses a movie dataset, but the methodology is adaptable to various data types with minor modifications. Dive in to learn about uncovering and understanding hidden data relationships in a user-friendly and visual way.
The process:
    1. Import raw data into Neo4j and decide which properties to be embedded.
    2. Embed node properties through the OpenAI API and save the results back to each Node.
    3. Store the results in Pinecone.
    4. Use Pinecone to calculate the similarity between each node.
    5. Use the similarity list to establish edges between nodes.
    6. Use Geminidata Explore to browse the data in Neo4j for visualization.
