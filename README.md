# AI-Enhanced-Multi-Client-Chat-Summarization-Application
In this project, a single server can handle multiple clients chatting at a same time and summarizes the chat when summarize is called or at the end of the chat.

Steps:
1. RUN the server.
2. Download the required files through terminal e.g. transformers, pipeline, etc.
3. Run the Client, enter chatroom using a nickname start chatting.
4. Follow the step 3 to activate new client.
5. Type "/summarize the chat" if you want the summary.
6. Else the server will automatically summarize the chat in the end(when everyone lefts).

"lidiya/bart-large-xsum-samsum model" is used to load the summarization pipeline using the pipeline function from the transformers library.