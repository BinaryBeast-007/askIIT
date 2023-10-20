# askIIT

I have implemented an integrated open API system at the Indian Institute of Technology Gandhinagar (IIT GN) that provides access to a comprehensive repository of over 175 advisories. These advisories cover a wide range of topics, including academic affairs, campus management, faculty affairs, general administration, research and development, student affairs, and alumni relations. This API allows users to seek answers to their queries by interacting with it much like a chatbot.

To make this system efficient and effective, I break down the extensive textual data within these advisories into smaller, manageable segments, each containing no more than 1000 tokens. These segments are then processed to create embeddings, which are numerical representations of the textual content, using open API embeddings.

When a user submits a question or query through the system, I obtain the corresponding embeddings for that query. These embeddings serve as a way to represent the user's question in a numerical format. Subsequently, I perform a semantic search on these query embeddings to find the most relevant segments of advisories that may contain the answer.

Finally, the results of this semantic search are passed to a language model (LLM) capable of generating human-readable answers. I process the relevant advisories and formulate an appropriate response to the user's query.

In summary, my integrated open API system at IIT GN leverages embeddings and semantic search techniques to access and retrieve information from a diverse set of advisories. It serves as an intelligent and efficient platform for users to seek information, facilitating a more natural and conversational interaction between users and the vast knowledge repository of IIT GN.
