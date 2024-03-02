# Real-time-Website-Conversation
<!DOCTYPE html> <html> <head> 
<title>Advanced Chatbot Development with LangChain and Streamlit GUI</title> </head> <body> <h1>Project Overview</h1> <p>This repository serves as a comprehensive guide for developing an advanced chatbot capable of interacting with websites, extracting information, and providing user-friendly communication. It leverages the power of LangChain 0.1.0 and integrates it with a Streamlit GUI for an enhanced user experience.</p>
<h2>Features</h2>
<ul>
	<li>Website Interaction: Utilize the latest version of LangChain to interact with and extract information from various websites.</li>
	<li>Large Language Model Integration: Compatible with models like GPT-4, Mistral, Llama2, and ollama, allowing flexibility in model selection.</li>
	<li>Streamlit GUI: A clean and intuitive user interface built with Streamlit for accessibility to users with varying technical expertise.</li>
	<li>Python-based: Entirely coded in Python for ease of understanding and modification.</li>
</ul>

<h2>RAG Bot Explanation</h2>
<p>A RAG bot, short for Retrieval-Augmented Generation, enhances the chatbot's knowledge by augmenting it with new information passed in the prompt. This involves vectorizing text to find the most similar information to the prompt, which is then used as a prefix for the Large Language Model.</p>

![docs](https://github.com/Riteshs677/Real-time-Website-Conversation/assets/143122816/d1d68cfb-615e-4fd6-a4cb-1146699c3720)


<h2>Installation</h2>
<ol>
	<li>Ensure Python is installed on your system.</li>
	<li>Clone this repository:
		```
		git clone [repository-link]
		cd [repository-directory]
		```
	</li>
	<li>Install required packages:
		```
		pip install -r requirements.txt
		```
	</li>
	<li>Create a .env file with the following variables:
		```
		OPENAI_API_KEY=[your-openai-api-key]
		```
	</li>
</ol>

<h2>Usage</h2>
<p>To run the Streamlit app:
	```
	streamlit run app.py
	```
</p>

<h2>Contributing</h2>
<p>Contributions are welcome for fixing bugs or typos. Please refer to the guidelines mentioned in the repository.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. Refer to the LICENSE file for details.</p>

<h2>Note</h2>
<p>This project is intended for educational and research purposes. Users are advised to comply with API terms of use and guidelines.</p>

<h2>Happy Coding!</h2>
<p>🚀👨‍💻🤖</p>

<p>Don't forget to star this repo if you find it useful!</p>
