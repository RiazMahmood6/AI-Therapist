# MeTime (AI Therapist) | Python, GPT-3.5-Turbo, DeepSeek, NLP

**MeTime** is an AI-powered therapeutic assistant designed to engage in context-aware conversations with users, understanding their emotions and offering relevant responses. This project uses advanced Natural Language Processing (NLP) techniques combined with sentiment analysis to create a dynamic and personalized user experience. The AI is powered by GPT-3.5-Turbo and DeepSeek to provide insightful and therapeutic conversations.

## Features

- **Emotion Detection**: Utilizes sentiment analysis to automatically detect the user's emotions from text inputs.
- **Dynamic Conversations**: Integrates GPT-3.5-Turbo and DeepSeek for dynamic, context-aware therapeutic conversations.
- **Personalized Responses**: Based on user inputs, the AI provides responses that are relevant and emotionally appropriate.
- **Intent Recognition**: The AI detects various intents in the user's messages, such as emotional states, needs, and preferences.

## Comparison: MeTime AI Therapist vs GPT-3.5-Turbo

While **GPT-3.5-Turbo** is a highly advanced language model capable of generating human-like text, **MeTime** (the trained AI therapist) offers several key improvements tailored for therapeutic conversations:

### 1. **Response Structure and Formatting**
   - **GPT-3.5-Turbo**: Responses from GPT-3.5-Turbo can be verbose and may lack a consistent structure, resulting in large, free-flowing text. This could make the response overwhelming or less effective in a therapeutic setting.
   - **MeTime**: The AI therapist produces responses in a **structured format**, providing clear, concise, and focused feedback. The structure is designed to maintain emotional sensitivity, keeping the conversation productive and easy to follow.

### 2. **Token Efficiency**
   - **GPT-3.5-Turbo**: While GPT-3.5-Turbo is optimized for generating detailed and accurate responses, it can result in **longer outputs** that use more tokens. This can lead to larger answers that may feel excessive in certain contexts, such as therapy.
   - **MeTime**: The trained model in **MeTime** is optimized for **token efficiency**, generating shorter, more direct answers that focus on clarity and emotional relevance. It uses fewer tokens without sacrificing quality or context, providing more **efficient conversations**.

### 3. **Context-Aware Responses**
   - **GPT-3.5-Turbo**: Although GPT-3.5-Turbo is highly capable of generating contextually aware responses, it doesn't specialize in understanding emotional nuances or therapeutic needs. Responses can sometimes be general or lack emotional depth.
   - **MeTime**: The AI therapist is specifically trained to detect and respond to a user's **emotional state** using sentiment analysis. It provides responses that are not just context-aware, but also tailored to **therapeutic goals**, offering more emotionally attuned and reflective answers.

### 4. **Efficiency in Conversational Flow**
   - **GPT-3.5-Turbo**: GPT-3.5-Turbo is a general-purpose model that may go off-topic or generate responses that are too broad in some cases. This can make the conversation less efficient or relevant to the user's needs.
   - **MeTime**: The AI therapist is designed to maintain a **focused and efficient conversational flow**, keeping the interaction centered around the user's emotional state and therapeutic needs. This results in **more targeted and meaningful interactions**.

## Dataset Overview

The dataset used to train the model consists of examples of various intents with their corresponding positive and negative statements. These are used to train the model to recognize different emotional states and intentions in user inputs.

### Sample Dataset

The training data consists of the following:

- **Intent**: Describes the underlying emotional or conversational need.
- **Definition**: A brief description of the intent.
- **Positive Examples**: Examples of statements that align with the intent.
- **Negative Examples**: Statements that do not align with the intent.

For example:

| Intent                | Definition                                                    | Positive Example 1                                                  | Positive Example 2                                                 | Positive Example 3                                                | Negative Example 1                                                 | Negative Example 2                                                 | Negative Example 3                                                 |
|-----------------------|---------------------------------------------------------------|--------------------------------------------------------------------|-------------------------------------------------------------------|------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| Makes Needs Explicit  | Identifies an implied or background need for the client.      | So, having a dependable and efficient means of transport for your daily commute seems to be a necessity for you, right? | It sounds like you've realized that maintaining a balance between your work and personal life is essential for your overall well-being. | From what you've said, keeping your living environment clean and organized appears to be beneficial for your productivity and mental health. | Your ability to adapt and overcome adversity really shows your resilience and determination. | I can see that your family is very encouraging. That positivity in your environment can be a huge boost for your personal growth. | Brilliant, it seems like your managerial skills have played a significant role in your career progression. |

### Training Data Example

The training data is structured as follows:

| Prompt                                                      | Completion                                                         |
|-------------------------------------------------------------|-------------------------------------------------------------------|
| Do you think it is well?                                    | I hope that through our work together, you'll be able to decide that for yourself. My hope is that we could be partners in thinking about that together. How does that sound? |
| It seems like I've used to this question, which we called a miracle question. | Questions on Emotions                                               |
| I love that analogy; good thinking, Bruce. That's excellent! | Wow, well, just to summarize today... You had some progress, encountered stumbling blocks, but you've decided to run in any weather... And in terms of a support group, I'll send you a list of groups. You rate today’s session an 8 out of 10. Great job! |

## How It Works

1. **User Input**: The user enters text (e.g., asking a question, expressing an emotion, or describing a situation).
2. **Emotion Analysis**: The system analyzes the user's input using sentiment analysis to determine their emotional state.
3. **Contextual Understanding**: Using GPT-3.5-Turbo and DeepSeek, the system interprets the user’s needs and intent to generate appropriate responses.
4. **Therapeutic Interaction**: The AI interacts with the user by offering relevant, emotionally appropriate responses, helping them navigate their feelings or thoughts.

## Usage

To interact with the AI therapist, simply open the Colab notebook:

[Open MeTime in Google Colab](https://github.com/RiazMahmood6/AI-Therapist/blob/main/Finetuned_AI_Therapist.ipynb)

Once opened, follow the instructions in the notebook to input your text and start the conversation.


## Acknowledgements

- **GPT-3.5-Turbo** and **DeepSeek** for context-aware conversational AI.
- **Sentiment Analysis** for emotion detection and understanding.
- Open-source contributors for datasets and tools used in this project.
