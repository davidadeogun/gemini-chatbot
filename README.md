# Gemini Chatbot

## Overview
The **Gemini Chatbot** is an AI-powered conversational assistant built using HTML, CSS, and JavaScript, integrated with the Gemini large language model (LLM) via APIs. It is designed to handle real-time queries, provide personalized responses, and adapt to user preferences over time. This chatbot can be deployed directly in a browser and is intended for use in various industries such as customer service, education, and personal assistance.

## Features
- **Real-time Conversations**: Provides real-time responses to a variety of user queries.
- **Personalization**: Learns from user interactions to deliver personalized responses.
- **API Integration**: Supports integration with third-party APIs for news, weather, and customer service data.
- **Browser-Based**: Runs entirely in the browser using HTML, CSS, and JavaScript.

## Prerequisites
You will need:
- **Access to Gemini Model API** (contact Gemini for API keys)
- **A modern web browser** (Chrome, Firefox, Safari, etc.)
- **Internet Connection** (for API requests)

## Installation

1. **Clone or Download the Project Files**
   - Clone the repository:
     ```bash
     git clone https://github.com/adeogundavid/gemini-chatbot.git
     ```
   - Or download the ZIP and extract the files.

2. **Open `index.html` in a Browser**
   - Simply open the `index.html` file in any modern web browser to start the chatbot.

## Usage
Once the page is loaded in the browser, you can interact with the chatbot via the UI. The bot will handle a variety of queries, including:
- General conversation
- News updates
- Weather information
- Customer service-related questions

## Get Your API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Navigate to the API key section and create a new API key.



**Note:** The API is free but has a limited number of usage requests.

## Insert Your API Key

1. Open your project folder in VS Code.
2. Locate to the `script.js` file in your project.
3. Find the `API_KEY` variable and replace `PASTE-YOUR-API-KEY` with your actual API key.

### Example Queries
- "Will AI take over our jobs?"
- "What are the best tips to improve my public speaking skills? ."
- "Tell me about AI chatbots."


## Technologies Used
- HTML: For structuring the chatbot’s interface.
- CSS: For styling the interface and making it responsive.
- JavaScript: For handling logic, API requests, and interactions.
- Express.js: For setting up the backend server and routing API requests
- Gemini Model API: For natural language processing and conversation handling.
- Firebase: For deployment and hosting
- CORS: To enable cross-origin requests between the frontend and backend.
- dotenv; For managing environment variables securely
- node-fetch: For making HTTP requests from the backend. 

### Customization
Feel free to customize the chatbot by editing the following:

- **HTML**: Modify the structure in `index.html` to change the layout or add new elements.
- **CSS**: Change styles in `style.css` to adjust the appearance.
- **JavaScript**: Add new API integrations or extend functionality by editing `script.js`.

### Known Issues
- The chatbot may provide irrelevant responses if API calls fail or incorrect data is received.
- Long conversations may slow down the browser if not optimized.

### Future Improvements
- **Multi-language Support**: Add support for multiple languages.
- **Enhanced UI**: Improve the user interface with more interactive elements.
- **Offline Mode**: Add limited offline functionality by caching responses.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
