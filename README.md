# About Emera

Emera is an open source AI combined with a discord bot. It's designed to be one of the few open-source AI Assistants out there.

## How add vocabulary to Emera

  1. Download the project with Git or by using the GitHub download as .zip button
  2. Open the file in the main folder named 'intents.json' using your favorite .json editor (e.g. VSCode)
  3. Scroll to the last tag in the list and add your own tag after it, ensuring that your tag doesn't match any others
  
  **Example Tag:**
  ```
  ,
  {"tag": "exampletag",
    "patterns": ["text-to-respond-to", "text-to-respond-to-2","text-to-respond-to-3"],
    "responses": ["response-1", "response-2", "response-3"],
    "context": [""]
  }
  ```
  **Note:**
  * That you may have any number of responses and patterns
  * The AI training will recognize phrases that are close to the 'text-to-respond-to' as opposed to exactly that phrase
  * Please make a Pull Request for your new content so others can enjoy it and Emera can continue to grow.