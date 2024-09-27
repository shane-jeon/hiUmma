This project is a simple English-to-Korean translation script utilizing OpenAI's GPT API. The focus is on translating in the Haeyoche speech level—a polite but informal style suitable for Korean-American (Gyopo) children communicating with their parents. It accepts user input in the terminal and outputs a translation that balances formality and warmth, making it ideal for casual family conversations where direct and natural language is preferred.

Key features:

Uses OpenAI's GPT-4 model.
Allows custom user input for translations.
Designed to generate nuanced translations, considering context and tone.

## How to Run This Project Locally

Follow the instructions below to set up and run this project on your local machine.

1. Clone the Repository
   `git clone https://github.com/shane-jeon/hiUmma.git`
2. Navigate to Project Directory
   `cd hiUmma`
3. Create Virtual Enviornment (Optional but Recommended)
   `python -m venv venv`
   Activate virtual environment:

- On Windows:
  `.\venv\Scripts\activate`
- On macOS/Linux:
  `source venv/bin/activate`

4. Install Required Dependencies
   `pip install -r requirements.txt`

5. Set up Environment Variables
   Create a `.env` file in the root directory of the project, and add your OpenAI API Key:
   `OPENAI_API_KEY=your_openai_api_key`
   Replace your_openai_api_key with your actual API key, which you can get from [OpenAI](https://platform.openai.com/docs/quickstart).

6. Run the Script
   `python hiUmma.py`

7. Quitting the Script:
   `CTRL + C`

8. Deactivate the Virtual Environment
   `deactivate`
