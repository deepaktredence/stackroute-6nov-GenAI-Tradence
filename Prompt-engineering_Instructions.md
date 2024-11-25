---
lab:
    title: 'Prompt engineering in your app'
---



## Configure your application
1. Open prompt_engineering.ipynb notebook file, and replace the following values with your OpenAI model values in the application.
        (your_azure_oai_endpoint)
        (your_azure_oai_key)
        (your_azure_oai_deployment)


## Run your application

### In the folder, open system.txt. For each of the interations, you'll enter the System message in this file and save it. Each iteration will pause first for you to change the system message.


   1. Enter the following prompts (with the **system message** still being entered and saved in `system.txt`).

    **System message**

    ```prompt
    You're an AI assistant who helps people find information. You'll provide answers from the text provided in the prompt, and respond concisely.
    ```

    **User message:**

    ```prompt
    What animal is the favorite of children at Contoso?

    ```

    2. To quit the running event, pass the system message - 'quit' (with the **system message** still being entered and saved in `system.txt)




