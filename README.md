# SAP-Machine-Learning-Embedding-OpenAI
"SAP Machine Learning Embedding in OpenAI"<br>

“Have you ever wished to ask an AI agent questions about selected thousands of pages after you have woken up from a good sleep?” 🙂 <br>
I wrote the blog “Hello, world! your crafted chat GPT bot!” ”https://blogs.sap.com/2023/04/19/hello-world-your-crafted-chat-gpt-bot/ about how to use OpenAI API to submit completions and ask further questions. The questions are restricted to the content the OpenAI was trained and that is not always enough as we want to extend the capabilities with actual online-specific content or local content.
Asking questions from additional content requires data augmentation. Let’s see what is possible nowadays with OpenAI API and LlamaIndex.

https://blogs.sap.com/2023/05/25/sap-machine-learning-embedding-in-openai/ 

Execute notebook in your browser with Binder. <br>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/itsergiu/SAP-Machine-Learning-Embedding-OpenAI/HEAD) <br>
Execute notebook _05 SAP HANA Machine Learning content embedding v1.3.1.ipynb_. It uses already embedded data in _vector_store_. Tokens are consumed only for questions.

The notebook _05 SAP HANA Machine Learning content embedding v1.3.ipynb_ is the full version with collecting documents from previous steps and creation of _vector_store_. Creation of _vector_store costs_ tokens.

