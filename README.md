# Medical-AI-Agent

The application is built using a combination of modern technologies that ensure efficiency, scalability, and ease of use:

Streamlit: A powerful and easy-to-use framework for building web applications in Python. It provides an intuitive interface for users to interact with the AI system, making it accessible even to those without technical expertise.
Ollama: A platform that facilitates the use of large language models like Llama, Mistral, Gemma etc.. It allows seamless integration of AI models into applications, enabling complex natural language processing tasks.
Python: The primary programming language used for developing the application. Python’s rich ecosystem of libraries and frameworks makes it ideal for AI and web development.
Asyncio: A Python library used to write concurrent code using the async/await syntax. It helps in managing asynchronous tasks efficiently, which is crucial for handling multiple AI agents simultaneously.
Workflow
The workflow of the application is as follows:

User Interaction: Users interact with the system via the Streamlit interface, selecting tasks and providing input data.
Task Delegation: The Agent Manager receives the task request and delegates it to the appropriate main agent.
Processing: The main agent processes the input data using the LLaMA model to generate the desired output.
Validation: The output is then passed to the corresponding validator agent, which evaluates the quality and accuracy of the results. A validation score out of 5 is provided for quick assessment.
Result Display: The final validated content is displayed to the user, with options to export the results or return to the main page.
