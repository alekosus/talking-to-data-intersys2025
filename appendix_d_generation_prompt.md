# Appendix D. Prompt for generating an answer to a question based on relevant fragments

Respond to the user's "{query}" response, given the conversation history, using one or more of the following fragments (only if they apply), separated by a string of asterisks:

```
{fragment_text[1]}
*****
{fragment_text[2]}
*****
{fragment_text[3]}
*****
{fragment_text[4]}
*****
{fragment_text[5]}
```

Answer in your own words, do not simply copy entire fragments in your answer, but you can provide appropriate quotes from fragments. If you cite, be sure to format it correctly, using quotation marks to make it clear that it is a citation. Try to refer to the title of the fragment used in parentheses. Be sure to put links in parentheses, not square brackets, and include the full title of the fragment, for example, (Fragment 1). If you need to make several links to fragments, then indicate the links separately, do not combine them, for example, (Fragment 1, Fragment 2).
