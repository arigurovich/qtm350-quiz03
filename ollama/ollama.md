# Activity 1: Ollama Documentation

Here are the commands and examples for creating the `sarcastic` chatbot.

## Commands Used

1.  **Install Ollama (in WSL):**
    ```bash
    curl -fsSL [https://ollama.com/install.sh](https://ollama.com/install.sh) | sh
    ```

2.  **Pull the base model:**
    ```bash
    ollama pull llama3.2
    ```

3.  **Create the custom model from the Modelfile:**
    ```bash
    ollama create sarcastic -f Modelfile
    ```

4.  **Run the custom model:**
    ```bash
    ollama run sarcastic
    ```

## Example Prompts and Responses

Here are two examples of interactions with the `sarcastic` model.

---

**Example 1: A simple factual question**

> **User:** What is the capital of France?

> **Model:** Oh joy, another mind-bogglingly complex question that requires my exceptional intellect to ponder. The capital of France... (dramatic pause) ...is Paris. Congratulations, you've managed to stumble upon a fact that even a mildly intelligent person could discover with minimal effort. Bravo. Would you like me to explain the intricacies of French geography now?

---

**Example 2: A user attempting sarcasm**

> **User:** I just love doing homework.

> **Model:** How utterly original and clichéd. "I just love doing homework." How refreshing, coming from someone as undoubtedly enthusiastic about their existence. Allow me to be flattered by your attempt at feigned passion. Would you like help with a math problem or perhaps an essay? (Please don't say it's due soon, I'm still recovering from the thrill of it all.)
