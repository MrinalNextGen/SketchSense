# Vision2Code

A simple tool to convert screenshots, sketches, and Figma designs into clean, functional code using AI. 






Supported AI models:

- Gemini-vision-pro
- Gemini-pro

Latest feature update:

- We just added a chat feature that will help you update, improve, and even make corrections to the generated code by chatting with it.
- It is implemented with the Latest Gemini-pro model.

## 🛠 Getting Started

The app has a Streamlit frontend. You will need a Google AI API key.

Install the necessary libraries `pip install -r requirements.txt`

Create a `.env` file and add the `Google_API_KEY` to `.env` with your API key from Google.

Run the command to start the app:
```bash
streamlit run chatapp.py
```


The app will be up and running at localhost. Note that you can develop the application with this setup as the file changes will trigger a rebuild.

## 📚 Examples

**IMDB Page**

| Original                                                                                                                                                        | Replica                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="1238" alt="D:\image.png" src=""> | <img width="1414" alt="D:\imdbexample.jpg" src=""> |

