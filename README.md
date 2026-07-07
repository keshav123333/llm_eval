# llm_eval


llm eval workflow 
1. define task and target : example you want to build a agentic workflow which will classify if the email is billing or autonomous
2. define sucess criteria
3. build dataset
4. define a eval method: like if inp a text if this text if for billing department or some other department this is the task output will be there if output is single billing or like this u can use accuracy score and automate if a text outcome is there u can use a human or llm model to evaluate
5. run model
6. analys result
7. improve result: how ? actually u can improve prompt u can use more capable model for that task and these are some things u can do there is not much option present here
8. deploy it :
9. monitoring karo


# why ur application need more eval pipeline 
wrokflow: 
query->  retriver (it retirves some documents from the vector db) -> gen (it genrate output based on query and given rag output)

1. now understand one eval needed in retirver if it can fetch needed docs build db and what is ouput and fetch doc from ur retirver and check if ur retiriver works fine tis output u can give to llm and ask if this works fine if it able to fetch related docs
2. Genrator will also have one llm eval which eval its ouput
3. and one final llm eval will be there at last evaluate if the final output is the output u want so its testing phase u have ur expected ouput 
