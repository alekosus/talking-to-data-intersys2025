# Talking to Data: Designing Smart Assistants for Humanities Databases

**Abstract** Access to humanities research databases is often hindered by the limitations of traditional interaction formats, particularly in the methods of searching and response generation. This study introduces an LLM-based smart assistant designed to facilitate natural language communication with digital humanities data. The assistant, developed in a chatbot format, leverages the RAG approach and integrates state-of-the-art technologies such as hybrid search, automatic query generation, text-to-SQL filtering, semantic database search, and hyperlink insertion. To evaluate the effectiveness of the system, experiments were conducted to assess the response quality of various language models. The testing was based on the Prozhito digital archive, which contains diary entries from predominantly Russian-speaking individuals who lived in the 20th century. The chatbot is tailored to support anthropology and history researchers, as well as non-specialist users with an interest in the field, without requiring prior technical training. By enabling researchers to query complex databases with natural language, this tool aims to enhance accessibility and efficiency in humanities research. The study highlights the potential of Large Language Models to transform the way researchers and the public interact with digital archives, making them more intuitive and inclusive.

**Keywords** Chatbot Assistants, Retrieval-Augmented Generation, Large Language Models

## List of appendices

* [**Appendix A.** Chatbot interface](./appendix_a_chatbot_interface.md)
* [**Appendix B.** Prompt with instruction for solving the Text-to-SQL task](./appendix_b_text2sql_prompt.md)
* [**Appendix C.** Topics of the experimental dataset](./appendix_c_dataset_topics.md)
* [**Appendix D.** Prompt for generating an answer to a question based on relevant fragments](./appendix_d_generation_prompt.md)
* [**Appendix E.** Description of expert scoring criteria for answer generation evaluation](./appendix_e_scoring_description.md)
* [**Appendix F.** Examples of factual errors of LLMs found during evaluation analysis](./appendix_f_error_analysis.md)