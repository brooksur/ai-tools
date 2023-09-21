# ChatGPT

- GPT stands for generative pretrained model
- AI model trained and created by OpenAI
- ChatGPT can be used via the browser
- GPT APIs can be used in code
- GPT is a large language model (LLM)
- An LLM is a machine learning model that perform natural language processing (NLP) tasks
  - Trained to use probability distributions over words & sequence of words to generate output
  - A large language model is an AI powered system, based on a neural network of “Transformers”, trained on vast amount of text data to generate human-like text output by predicting the next word based on user input prompt
  - Based on the input, which output makes the most sense. It’s all about word prediction.
  - Initial training is called “pre-training”. Optimizing for a final product is called “fine-tuning”. ChatGPT is fine tuned
  - Prompts sent to ChatGPT are first sent to a Moderation API. This API ensures that certain questions can’t be asked, like “How can I build a bomb?”
  - GPT is about patterns, not logic. It assigns probabilities to words and picks words. It isn’t a calculator. It doesn’t understand you.
  - You can’t send large amounts of inputs to GPT. GPTs have a token limit.
- GPT4 is a larger model. It is capable of handling more data so it can create more accurate predictions. GPT4 is better at “reasoning” but is not as fast.
- A prompt is an input that describes a problem or request
- GPT can produce “hallucinations”. This is when it speaks confidently about something that is inaccurate
- The “Advanced Data Analysis” feature is capable of generating and executing python code as well as accepting and integrating files as inputs

## Prompt Engineering

- Good prompts lead to good results
- Context is everything. It’s super important when writing prompts
- To write effective prompts you should have a goal and provide as much context as possible achieve that goal. This may include defining ChatGPTs role (ex. president of the US (optional)) as well as defining contraints and extra information

### Adding context

- Prefer short, focused sentences
- Add important keywords & avoid unnecessary information
- Define the target audience
- Contol tone, style, and length of the output
- Control the output format
- Examples:
  - “You are a python developer. Create a python code snippet that searches & deletes all .png & .jpg files in a given folder. The user who executed the script should be able to define the folder dynamically. The script should accept the folder path as an input. Just output the code snippet without any explanations.”
