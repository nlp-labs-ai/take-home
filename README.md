# Assignment

The goal of this take home assignment is to assess product engineering mindset and approach.

## Task

Your work for an AI fintech company that is looking to build an AI-enabled product for financial analysts to conduct research faster. Through customer interviews you've learned that one of the biggest painpoints in researching a company is pouring through hundreds to thounsands of pages of [EDGAR SEC 10-K Filings](https://www.sec.gov/edgar/searchedgar/companysearch). Assume from the interviews that analysts typically have 2 types of research questions, factual and summarization. Here are some plausible research questions:

* What was Tesla's revenue and COGS in 2022Q3? (Factual)
* Summarize the operating risks of Amazon (Summarization)

You and your team think that solving the problem of extracting information from 10-K filings would be a huge value add to the company's product/platform. 

Before spending weeks to engineer a solution, you decide it's better to come up with a quick prototype that an analyst can get their hands on and execute some queries. The goal of the prototype is to allow your team learn/obseve/measure how a user would use such a research tool and use the data to come up with next features/requirements.

To help you build the prototype, here are some libraries and tools to help you get started:
* [https://www.llamaindex.ai/](LlamaIndex)
* [https://www.langchain.com/](Langchain)
* [https://sec-edgar-downloader.readthedocs.io/en/latest/](SEC Edgar Downloader)
