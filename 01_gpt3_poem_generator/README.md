# GPT-3 Streamlit Poem generator Web Application

The application itself is a Poem generator that will generate a poem based on the input words. We are using the text-davinci-002 model from OpenAI which is defined in the model.py file.

## GETTING AN OpenAI API Key

You can get one by signing up at from [beta.openai.com](https://beta.openai.com/). Once your account is created, you can go to your profile and click the "API Keys" tab and create one.

## RUN APPLICATION

- create virtual environment

```bash

python3 -m venv <"Path for Environment/'name of environemnt'">

# Example
python3 -m venv /workspace/streamlit_gpt3_poem_generator/gpt3

```

- Activate virtual environment

```bash

source <"'Path to Environment'/bin/activate">

# Example
source /workspace/streamlit_gpt3_poem_generator/gpt3/bin/activate

```

- install dependencies

```bash
`pip install -r requirements.txt`

```

- Run application

```bash

streamlit run gpt_app.py
```

**APP Link**: [Poem Generator](https://ashish-soni08-streamlit-gpt3-poem-generator-gpt-app-4yab0g.streamlit.app/)
