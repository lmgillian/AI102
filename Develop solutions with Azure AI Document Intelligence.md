## Plan an Azure AI Document Intelligence solution
1. What is Azure AI Document Intelligence and how does it improve upon manual data entry?
2. What are the principles Microsoft uses when designing and building AI solutions, and how should they be considered when using Azure AI Document Intelligence?
3. What types of models does Azure AI Document Intelligence offer, and how do they differ?
4. When should you use a prebuilt model versus a custom or composed model in Azure AI Document Intelligence?
5. How does Azure AI Document Intelligence relate to Azure AI Vision, and when might you choose one service over the other?
6. What tools are available for exploring and understanding the capabilities of Azure AI Document Intelligence without writing code?
7. How do you create and configure Azure AI Document Intelligence resources in your Azure subscription?
8. What information do you need to connect your application to Azure AI Document Intelligence, and where can you find it?
9. What are the differences between custom template models and custom neural models in Azure AI Document Intelligence?
10. In what scenarios would you use a composed model, and what are the limitations based on the pricing tier?

## Use prebuilt Document intelligence models
1. What are prebuilt models in Azure AI Document Intelligence, and how do they simplify data extraction from common forms and documents?
2. What types of specific form types are the prebuilt models trained on, and what common fields can they extract?
3. How do the general document analysis models like Read, General Document, and Layout differ in their data extraction capabilities?
4. What are the input requirements for submitting documents to prebuilt models in Azure AI Document Intelligence?
5. When would you use a custom model instead of a prebuilt model in Azure AI Document Intelligence?
6. How can you explore and test prebuilt models using Azure AI Document Intelligence Studio?
7. What information is needed to call Azure AI Document Intelligence using APIs, and where can you find it?
8. What are the features and limitations of the invoice model in Azure AI Document Intelligence?
9. How does the receipt model in Azure AI Document Intelligence differ from the invoice model in terms of extracted data?
10. What types of identity documents can the ID document model analyze, and what fields can it extract?
11. What sensitive data considerations should you keep in mind when using the ID document model?
12. What information can the business card model extract from business cards?
13. What fields can the W-2 model extract from the United States Internal Revenue Service W-2 tax declaration form?

## Extract data from forms with Azure Document intelligence
1. What is Azure Document Intelligence, and what capabilities does it offer for extracting data from documents?
2. How does OCR work within Azure Document Intelligence, and what types of data can it capture from documents?
3. What are the components of Azure Document Intelligence, and what types of models does it include?
4. How can you access Azure Document Intelligence services, and what are the options available?
5. What are the requirements for subscribing to an Azure Document Intelligence resource, and what are the differences between Azure AI Service and Azure Document Intelligence resources?
6. What file input requirements must be met for documents to be processed by Azure Document Intelligence?
7. How do you decide which component of Azure Document Intelligence to use for your specific needs?
8. What is the process for training custom models in Azure Document Intelligence?
9. How do you use the API to extract form data using a custom model in Azure Document Intelligence?
10. What is the Azure Document Intelligence Studio, and what projects does it support?
11. How do you build projects using document analysis models, prebuilt models, and custom models in Azure Document Intelligence Studio?
12. What is required to train a custom model using Azure Document Intelligence services?

## Create a composed document intelligence model
1. What are composed models in Azure AI Document Intelligence, and when would you use them?
2. What are the two types of custom models you can create in Azure AI Document Intelligence, and how do they differ?
3. How do you specify the identity of the model you want to use when sending a form for analysis in Azure AI Document Intelligence?
4. How does Azure AI Document Intelligence categorize forms and select the best custom model for analysis when using a composed model?
5. What are the steps to create a composed model in Azure AI Document Intelligence Studio?
6. How do you create a composed model using code with the Azure AI Document Intelligence SDKs?
7. What information do you need to connect to Azure AI Document Intelligence when creating a composed model in code?
8. After creating a composed model, how do you send a form to it for analysis, and how do you determine which custom model was used to analyze the form?

## Build a Document intelligence custom skill for Azure AI search
1. How can Azure AI Document Intelligence enrich an Azure AI Search index?
2. What are the five stages of the indexing process in Azure AI Search?
3. What is a skillset in Azure AI Search, and what types of skills can it include?
4. How do you create a custom skillset in Azure AI Search?
5. What are the two types of custom skills you can create in Azure AI Search, and when would you use each type?
6. What are the requirements for integrating a custom Web API skill into the Azure AI Search indexing pipeline?
7. How do you test a custom skill during development, and what tool can you use to formulate and submit REST requests?
8. What hosting options are available for a custom skill within Azure?
9. How do you add a custom skill to a skillset in Azure AI Search?
10. What information does Azure AI Search use to match a submitted form with the correct response from a custom skill?