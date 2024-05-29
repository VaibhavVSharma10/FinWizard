# FinWizard

Welcome to the FinWizard Chatbot repository! This project delves into the fascinating world of Gen AI and chatbots, specifically focusing on creating an intelligent chatbot tailored for investment banking scenarios. The chatbot leverages Intel's Neural Chat LLM, Langchain orchestration, and cutting-edge technologies to provide detailed and relevant responses to user queries.


Features

    Developed a FinWizard RAG APP as an end-to-end application extracting data from multiple documents using Intel's Neural Chat LLM and Langchain orchestration for detailed responses and efficient processing.
    Integrated BGE Embeddings and Chroma DB for robust database handling, enhancing chatbot capabilities.
    Developed a user-friendly conversational interface and utilized Flask and FastAPI for backend development, ensuring an engaging end-to-end user experience.

Use Cases


1. Investment Advice: Get personalized stock recommendations, portfolio diversification tips, and risk assessments based on market trends.

2. Financial Education: Learn about compound interest, asset allocation, retirement planning, and other financial concepts in an interactive way.

3. Banking Services: Access account balances, transaction history, fund transfers, bill payments, and other banking tasks conveniently.

4. Market Analysis: Stay updated with real-time market trends, economic indicators, company financials, and industry insights for informed investment decisions.

5. Customer Support: Receive personalized assistance for account troubleshooting, product inquiries, and financial services, improving overall customer satisfaction.


How to Run:

Command 1

create vector store:

    python ingest.py

Command 2

Running application

    python flask_app.py
or

    uvicorn fastapi_app:app
