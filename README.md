# Knowledge embedding
This project is a case study of automatic draft customer emails based on the company's best practices.

first add the openai API key in .env

## Finetune LLM: 
-  It is useful when you want an LLM to behave in a certain way
- But it is not very great at retrieving very specific data and knowledge

## Knowledge base embedding:
-  When you want your LLM to have specific domain knowledge
-  It means that when a user has a question, instead of sending his question to LLM, instead you it will search for relevant documents for this question
-  image

 # how it is implemented
1. Vercorise the sales repones csv data
2. Function for similarity search
3. Setup LLMChain and prompts
4. Reterival augmented generation
