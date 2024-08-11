# wiki-chatbot
## using automated prompt engineering to customize Q&amp;A results
This project demonstrated automated prompt engineering in the context of a chatbot that uses RAG to answer queries about wiki pages.
The following are the key features:
- UI that allows the user to enter a topic they want to learn about, then select the specific page from the dropdown list of wiki pages related to that topic
- preprocessing of the page content into a pandas dataframe with a 'text' column
- generating embeddings for each text row
- calculating the cosine distance between the query embedding and text embeddings to reorder the df text rows by most to least relevant.
- auto generating the prompt context to include as much of the page content as possible given the context limit of the model
- output of a formatted, custom answer
- comparison of a couple example custom answers with non-custom answers to show difference in output
