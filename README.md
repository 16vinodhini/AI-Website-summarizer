# AI Website Summarizer

https://github.com/16vinodhini/AI-Website-summarizer.git

Built with Python, Groq (LLM) and Gradio.

## How it works
1. Scrape the page text (requests + BeautifulSoup)
2. Send the text to an LLM with a summary prompt
3. Show the summary in a Gradio web app

## Run it
pip install openai gradio requests beautifulsoup4 python-dotenv

Create a file named .env and add:
GROQ_API_KEY=your_key_here

Then run:
python app.py
