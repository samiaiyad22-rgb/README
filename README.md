# Google Colab demos

Beginner-friendly notebooks you can upload and run in [Google Colab](https://colab.research.google.com/):

- [hello_colab.ipynb](hello_colab.ipynb) prints a greeting and adds two numbers.
- [creative_ideas.ipynb](creative_ideas.ipynb) asks for an everyday object and uses the OpenAI Responses API with **gpt-6-luna** to suggest three unusual but practical ideas.

## Run the creative ideas notebook

1. Upload creative_ideas.ipynb to Colab and run the cells from top to bottom.
2. The first code cell installs the OpenAI Python SDK if it is not already installed.
3. Run the idea cell and enter your API key in the hidden getpass prompt.
4. Enter an everyday object. The notebook displays three numbered ideas.
5. Enter another object to continue, or type quit or exit to stop.

You need API access to gpt-6-luna. Each API request may incur charges.

Keep your API key private: enter it only in the hidden runtime prompt. Never paste it into notebook code, print it, save it in a file, or commit it to Git. Disconnect and delete the Colab runtime when you finish.

See the OpenAI Python SDK documentation (https://developers.openai.com/api/reference/python) and GPT-6 Luna model page (https://developers.openai.com/api/docs/models/gpt-6-luna) for details.
