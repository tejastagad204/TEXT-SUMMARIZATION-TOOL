# TEXT-SUMMARIZATION-TOOL
Thrilled to share that I’ve started a Data Analytics internship at CODTECH IT Solutions! Excited to gain hands-on experience and enhance my skills in real-world projects.
company codtech it solutions

name tejas tagad

intern id CT04DR1129

Domian Artificial Intelligence

Duration 4 weeks

Mentor NEELA SANTOSH

##The objective of this task is to develop an intelligent tool that can summarize lengthy articles using Natural Language Processing (NLP) techniques. This task demonstrates the practical application of NLP in real-world text processing, helping users condense long pieces of content into short, readable summaries that retain the essential information. With the exponential growth of digital content, summarization tools are increasingly valuable in education, journalism, research, and more.

This project uses Python and the Hugging Face Transformers library, specifically the pre-trained facebook/bart-large-cnn model, which is known for its effectiveness in abstractive summarization. Unlike extractive summarization (which only pulls exact sentences from the text), abstractive summarization generates new sentences to express the core ideas of the article in a concise form, much like how a human might write a summary.

The script begins by importing necessary libraries, including the pipeline function from transformers and textwrap for formatting the console output. It defines a function summarize_article() that accepts a block of text and uses the summarization pipeline to return a shortened version. Another function, pretty_print(), is used to display both the original article and its summary in a readable format in the terminal.

The script can be executed directly using Python, and upon running, it displays the original article followed by its summarized form. This allows users to compare the input and output, verifying the quality and clarity of the summarization. The model used works best with text under 1024 tokens (about 800–1000 words), so it is well-suited for medium-sized articles such as news stories or blog posts.

From a learning perspective, this task helps interns understand: How to use pre-trained NLP models effectively.

The difference between extractive and abstractive summarization.

The practical applications of artificial intelligence in solving real-world problems.

How to manage dependencies, use virtual environments, and build readable, well-commented Python scripts.

Additionally, this task introduces good software development practices such as organizing code, documenting functionality with comments and docstrings, and formatting outputs for better user experience. Interns are encouraged to keep their code in a GitHub repository with proper folder structure and commit history, which is valuable for future reference and showcasing their work.

This task can be extended further by allowing input from external sources (like .txt files or URLs), adding a graphical user interface using Tkinter or Streamlit, or exporting the summary to a file. These improvements provide opportunities to explore file handling, web scraping, or GUI development — all valuable skills in modern software engineering.

In conclusion, this article summarizer task offers a solid foundation in applied NLP, helping interns bridge the gap between theory and real-world usage. It encourages the use of powerful AI models while reinforcing essential programming habits, making it a vital part of the CodTech internship program.

