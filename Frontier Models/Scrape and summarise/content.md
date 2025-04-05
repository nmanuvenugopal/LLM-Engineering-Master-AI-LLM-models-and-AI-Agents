### 💡 Understanding Prompts for Frontier Models (e.g., GPT-4.0, GPT-3.5 Turbo, Claude)

When working with **frontier models** like OpenAI's GPT-4.0, GPT-3.5 Turbo, or Anthropic’s Claude, you typically interact with them using **prompts**. These prompts guide the model’s behavior and output.

There are two main types of prompts:

#### 🧠 System Prompt
- The **system prompt** sets the behavior, tone, or persona of the model.
- It tells the model **how** it should respond throughout the conversation.
- Think of it like setting the stage or giving the model a role to play.

#### 👤 User (or Human) Prompt
- The **user prompt** is the actual input or question from the human user.
- This is what the model responds to based on the context set by the system prompt.

---

### 📬 Message Format

OpenAI models (and many other frontier models) expect input in a **structured message format**, often as a list of messages with associated roles. This format improves clarity and enables multi-turn conversation handling.

Here’s an example of the format:

```json
[
  {
    "role": "system",
    "content": "You are a helpful assistant that explains machine learning concepts in simple terms."
  },
  {
    "role": "user",
    "content": "Can you explain what overfitting means in machine learning?"
  }
]
```

> 🔄 This format is used in OpenAI’s `chat/completions` endpoint and has been widely adopted by other LLM providers due to its effectiveness in maintaining context and guiding model behavior.
