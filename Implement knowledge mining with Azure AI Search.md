## Create an Azure AI Search solution
1. What are the service tiers and capacity management options available when creating an Azure AI Search resource?
2. What are the main components of an Azure AI Search solution, including data source, skillset, indexer, and index?
3. How does the indexing process work in Azure AI Search, and what is the role of the enrichment pipeline?
4. How do you search an index in Azure AI Search, and what is full text search?
5. How can you apply filtering and sorting to query results in Azure AI Search?
6. What are some ways to enhance an index in Azure AI Search to provide a better user experience, such as search-as-you-type, custom scoring, and synonyms?
7. You want to find information in Microsoft Word documents that are stored in an Azure Storage blob container. What should you do to ensure the files can be accessed by Azure AI Search?
8. You are creating an index that includes a field named modified_date. You want to ensure that the modified_date field can be included in search results. Which attribute must you apply to the modified_date field in the index definition?
9. You have created a data source and an index. What must you create to map the data values in the data source to the fields in the index?
10. You want to create a search solution that uses a built-in AI skill to determine the language in which each indexed document is written, and enrich the index with a field indicating the language. Which kind of Azure AI Search object must you create?
11. You want your search solution to show results in descending order of the file_size field value. What is the simplest way to accomplish this goal?
12. You have created a search solution. Users want to be able to enter a partial search expression and have the user interface automatically complete the input. What should you add to the index?

## Create a custom skill for Azure AI Search
1. What is the expected input schema for a custom skill in an Azure AI Search skillset?
2. What should the output schema of a custom skill reflect, and what should it contain?
3. How do you add a custom skill to a skillset in Azure AI Search, and what information must the skill definition specify?
4. You want to include a sentiment score for each document in an index. What should you do?
5. You have implemented a custom skill as an Azure function. You want to include the custom skill in your Azure AI Search indexing process. What should you do?

## Create a knowledge store with Azure AI Search
1. What is the expected input schema for a custom skill in an Azure AI Search skillset?
2. What should the output schema of a custom skill reflect, and what should it contain?
3. How do you use the Shaper skill to create a simplified structure for the fields you want to map to projections in a knowledge store?
4. How do you define a knowledge store and the projections you want to create in it within a skillset?
5. You want to create a skillset that includes a knowledge store definition. Which type of skill should you use to map the enriched fields extracted by your skillset to the desired structure for the knowledge store data?
6. You want to create a knowledge store that contains JSON representations of the indexed documents. What kind of projection should you define?
7. You want to create a knowledge store that contains a relational schema for your enriched data. What kind of projection should you define?
8. You want to create a knowledge store that contains the images extracted from your indexed documents. What kind of projection should you define?

## Enrich your data with Azure AI Language
1. What are the main feature areas of Azure AI Language?
2. How can you test and use preconfigured language features in Azure AI Language?
3. What are the steps to create, train, and deploy a conversational language understanding model using Azure AI Language?
4. How do you enrich a search index in Azure AI Search with custom classes and Azure AI Language?
5. Which of the following features of Azure AI Language can you use out of the box without needing to train a model?
6. Which step enables an AI Search index to store the enrichments from an Azure AI Language project?
7. Where do you copy the full endpoint of the function app to use in the custom web skill that includes the api-version and path to the actual function name?

## Implement advanced search features in Azure AI Search
1. How can you write more complex Lucene queries to improve the relevance of search results by boosting specific terms in your search query?
2. What are analyzers in Azure AI Search, and what is the purpose of a custom analyzer?
3. What components make up a custom analyzer, and how do you create one?
4. How can you test a custom analyzer to ensure it returns tokens correctly?
5. How do you use a custom analyzer for a field in an Azure AI Search index?
6. How can you enhance an index to include multiple languages, and what steps are involved in adding language-specific fields?
7. What are geo-spatial functions in Azure AI Search, and how can you use them to search for items associated with a geographical location?
8. What character do you add after a search term to boost the term?
9. Which of the following options is a function you can use in a scoring profile?
10. What Azure product can you use to enrich an index with different language translations?

## Build an Azure Machine Learning custom skill for Azure AI Search
1. How does using a machine learning custom skill differ from adding other custom skills to a search index?
2. What is the schema for an Azure Machine Learning (AML) custom skill in an Azure AI Search skillset?
3. How do you create and train a model in Azure Machine Learning studio?
4. What changes need to be made to the scoring code of an Azure Machine Learning model to allow it to be used by an AML custom skill in Azure AI Search?
5. How do you create an endpoint for your Azure Machine Learning model to use?
6. How do you connect the AML custom skill to the endpoint in Azure AI Search?
7. Which of the following options is the only supported endpoint for use with Azure AI Search custom AML skill?
8. Which is the correct custom skill you need to use to connect to an Azure Machine Learning model?
9. What's the best way to improve the performance of an AML skill when enriching documents?

## Search data outside the Azure platform in Azure AI Search using Azure Data Factory
1. How can you use Azure Data Factory to push data into an Azure AI Search index?
2. What are the steps to create an Azure Data Factory pipeline to push data into a search index?
3. How do you map source fields to target fields in an Azure Data Factory pipeline?
4. What are the limitations of using the Azure Search linked service as a sink in a copy data task?
5. How do you use the Azure AI Search REST API to index any data, and what are the supported operations?
6. What is the best practice for batching documents when using the Azure AI Search REST API to add data to an index?
7. Which response code will require you to implement a backoff strategy when using the Azure AI Search REST API?

## Maintain an Azure AI Search solution
1. How does Azure AI Search encrypt data at rest and what key management options are available?
2. What methods are available to restrict inbound traffic to an Azure AI Search solution?
3. Explain the difference between admin keys and query keys in Azure AI Search.
4. How can role-based access control (RBAC) be used to manage access to Azure AI Search resources?
5. What are the key metrics to monitor for measuring the performance of an Azure AI Search service?
6. Describe best practices for writing efficient search queries in Azure AI Search.
7. How can you estimate the baseline costs of an Azure AI Search solution?
8. What components make up the billing model for Azure AI Search?
9. How does increasing the number of replicas improve the availability of an Azure AI Search service?
10. What is the purpose of using Availability Zones in Azure AI Search?
11. How can the Debug Session tool in Azure AI Search be used to troubleshoot issues with a skillset?

## Perform search re-ranking with semantic ranking in Azure AI Search
1. What is semantic ranking and how does it improve the ranking of search results in Azure AI Search?
2. How does the BM25 ranking function work, and why might it not always produce the most relevant search results?
3. What are the two functions of semantic ranking in Azure AI Search?
4. How does semantic ranking use language understanding models to improve search result relevance?
5. What are semantic captions and answers, and how do they enhance search results?
6. Describe the process of how semantic ranking works, starting from the top 50 BM25 results.
7. What are the key advantages of using semantic ranking over traditional search results?
8. What limitations does semantic ranking have in terms of the results it can re-rank?
9. How can you enable semantic ranking in Azure AI Search, and what are the prerequisites?
10. What steps are involved in configuring semantic ranking for an index in Azure AI Search?

## Perform vector search and retrieval in Azure AI Search
1. What is vector search and what new capabilities does it bring to AI Search?
2. In what scenarios is vector search particularly useful?
3. How does vector search overcome the limitations of text-based searches?
4. What are the limitations to be aware of when using vector search in Azure AI Search?
5. How do you check if your index in Azure AI Search has vector fields?
6. What steps must you take to convert a query input into a vector for searching?
7. When would you choose to use vector search over traditional text search methods?
8. What is required to run a successful vector query in Azure AI Search?
9. Which type of vector search would you use to capture semantic similarity?