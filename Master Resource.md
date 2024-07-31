# Get started with Azure AI Services
## Prepare to develop AI solutions on Azure
1. What is machine learning, and how is it a subset of data science?
2. How do software engineers use machine learning to train predictive models?
3. What does it mean that AI predictions are probabilistic, and how are confidence scores used in this context?
4. Describe Azure Machine Learning and its role in the machine learning lifecycle.
5. How does Azure Machine Learning facilitate data ingestion, model training, and deployment?
6. What are Azure AI Services, and what types of prebuilt AI capabilities do they offer?
7. How can engineers incorporate natural language processing into their applications using Azure AI Services?
8. What is computer vision, and how is it provided through Azure AI Services?
9. What is the Azure OpenAI Service, and what generative AI models does it provide access to?
10. Describe Azure Cognitive Search and how it uses AI to improve search experiences.
11. What is the role of AI in enriching indexing within Azure Cognitive Search?
12. What are Microsoft's core principles for responsible AI as per their June 2022 updates?
13. How can developers ensure that their AI-integrated applications adhere to ethical standards?
14. Discuss the impact of AI on decision-making processes within software applications.

## Create and consume Azure AI services
1. What is the purpose of Azure AI services?
2. How do users access Azure AI services?
3. What is required to provision resources within an Azure subscription?
4. What are the two primary resource options available for Azure AI services?
5. What does the multi-service resource provide?
6. How does the single-service resource differ from the multi-service resource?
7. What are the benefits of using single-service resources?
8. Why might services require separate resources for training AI models and prediction usage?
9. What are the three critical pieces of information users must identify upon provisioning a resource?
10. Why is the endpoint URI important?
11. What is the purpose of the subscription key?
12. How is the resource location linked to Azure data centers?
13. Through what means can Azure AI services be consumed?
14. What is the role of REST APIs in interacting with Azure AI services?
15. What tools can be used to interact with Azure AI services' REST APIs?
16. Why might developers use language-specific SDKs?
17. Which languages does Azure provide SDK support for?
18. How do SDKs enhance the developer experience?
19. How do Azure AI services support the scalability of applications from evaluation to production levels?

## Secure Azure AI services
1. Why should you regenerate keys regularly for Azure AI services resources?
2. How can you regenerate keys without service interruption?
3. What is the purpose of Azure Key Vault in the context of Azure AI services?
4. How does token-based authentication work with Azure AI services?
5. What is the role of Microsoft Entra ID authentication in Azure AI services?
6. How do you authenticate against Azure AI services using service principals?
7. What are the differences between system-assigned and user-assigned managed identities?
8. How do you implement network security for Azure AI services?
9. What are the steps to apply network access restrictions to Azure AI services?
10. You need to regenerate the primary subscription key for an Azure AI Services resource that an app uses. What should you do first to minimize service interruption for the app?
11. You want to store the subscription keys for an Azure AI Services resource securely, so that authorized apps can retrieve them when needed. What kind of Azure resource should you provision?
12. When running code on your computer that connects to Azure AI Services, you receive an error that access is denied due to Virtual Network/Firewall rules. What configuration do you need to set in the Azure AI Services instance?

## Monitor Azure AI services
1. How can you estimate costs for Azure AI services before deploying a solution?
2. How can you view accumulated costs for AI services resources in the Azure portal?
3. What steps are involved in creating an alert rule for an Azure AI services resource?
4. How can you view metrics for an individual Azure AI services resource in the Azure portal?
5. How can you add metrics to a dashboard in the Azure portal?
6. What resources do you need to create for diagnostic log storage for an Azure AI services resource?
7. How do you configure diagnostic settings for an Azure AI services resource?
8. How should you collect telemetry for your Azure AI Services resource for later analysis?
9. You are defining an alert that notifies you when a key regeneration event is recorded in the activity log for your Azure AI Services resource. What should you do?
10. You are viewing a metric for your Azure AI Services resource in a chart. You want to combine the chart with visualizations of other resources and data. What should you do?

## Deploy Azure AI services in containers
1. What is a container and how does it benefit the deployment of Azure AI services?
2. What is the process for deploying and using an Azure AI services container?
3. How are Azure AI services container images used and where can they be found?
4. What configuration settings must be specified when deploying an Azure AI services container image?
5. How do applications consume Azure AI services from a container?
6. Which of the following parameters must you specify when deploying an Azure AI services container image?
7. You plan to use the language detection functionality of Azure AI Language in a container. Which container image should you deploy?

# Develop natural language processing solutions with Azure AI Services
## Analyze text with Azure AI Language
1. What functionalities does Azure AI Language provide for text analysis?
2. How do you provision an Azure AI Language resource in your Azure subscription?
3. What is the Azure AI Language detection API used for, and what does it return?
4. How does key phrase extraction work, and what is the maximum size of the document that can be analyzed?
5. How is sentiment analysis performed using Azure AI Language, and what does the response include?
6. What is Named Entity Recognition, and what categories of entities can it identify?
7. How does entity linking work, and what knowledge base does Azure AI Language use for disambiguation?
8. How should you create an application that monitors the comments on your company's website and flags any negative posts?
9. You are analyzing text that contains the word "Paris." How might you determine if this word refers to the French city or the character in Homer's "The Iliad"?

## Create question answering solutions with Azure AI Language
1. What is the question answering capability in Azure AI Language, and how is it typically used?
2. How do you create a knowledge base for question answering in Azure AI Language?
3. What is the difference between question answering and conversational language understanding in Azure AI Language?
4. How can you implement multi-turn conversations in a knowledge base?
5. What are the steps to test and publish a knowledge base in Azure AI Language?
6. How do you consume a published knowledge base using the REST interface?
7. How can you improve question answering performance with active learning and synonyms?
8. You want to create a knowledge base from an existing FAQ document. What should you do?
9. How can you add a multi-turn context for a question in an existing knowledge base?
10. How can you enable users to use your knowledge base through email?

## Build a conversational language understanding model
1. What are the pre-configured and learned features of the Azure AI Language service?
2. How do you build, train, and deploy a model using the Azure AI Language service?
3. What are the differences between pre-configured features like summarization, named entity recognition, PII detection, key phrase extraction, sentiment analysis, and language detection, and learned features like conversational language understanding (CLU)?
4. How do you define intents, utterances, and entities when building a conversational language understanding model?
5. How can you use patterns to differentiate similar utterances in a language model?
6. What are pre-built entity components, and how can they be used in a language model?
7. What are the steps involved in training, testing, publishing, and reviewing a conversational language understanding model?
8. Your app must interpret a command such as "turn on the light" or "switch the light on." What do these phrases represent in a language model?
9. Your app must interpret a command to book a flight to a specified city, such as "Book a flight to Paris." How should you model the city element of the command?
10. Your language model needs to detect an email when present in an utterance. What is the simplest way to extract that email?

## Create a custom text classification solution
1. What are the two types of custom text classification projects available in Azure AI Language service?
2. What are the differences between single label and multiple label classification projects in terms of labeling data, evaluating and improving the model, and the API payload?
3. What are the steps involved in the Azure AI Language project life cycle for building a custom text classification model?
4. How should you split datasets for training in custom text classification projects?
5. What are the deployment options available for custom text classification models in Azure AI Language?
6. How do you use the REST API to build and interact with custom text classification projects in Azure AI Language?
7. You want to train a model to classify book summaries by their genre, and some of your favorite books are both mystery and thriller. Which type of project should you build?
8. You just got notification your training job is complete. What is your next step?
9. You want to submit a classification task via the API. How do you get the results of the classification?

## Custom named entity recognition
1. What is Custom NER, and how does it differ from built-in NER in Azure AI Language?
2. What are the types of projects available in custom text classification, and how do they differ?
3. What are the considerations for data selection and refining entities in a custom NER project?
4. How do you label data for a custom NER model, and what are the best practices for labeling?
5. How do you train and evaluate a custom NER model, and what metrics are used to assess its performance?
6. How can you interpret the precision, recall, and F1 score metrics when evaluating a custom NER model?
7. What is a confusion matrix, and how can it help in improving a custom NER model?
8. You've trained your model and you're seeing that it doesn't recognize your entities. What metric score is likely low to indicate that issue?
9. You just finished labeling your data. How and where is that file stored to train your model?
10. You train your model with only one source of documents, even though real extraction tasks will come from several sources. What data quality metric do you need to increase?

## Translate text with Azure AI Translator service
1. What functionalities does Azure AI Translator provide?
2. How do you provision an Azure AI Translator resource in your Azure subscription?
3. What are the capabilities of Azure AI Translator for language detection, translation, and transliteration?
4. How can you specify translation options such as word alignment, sentence length, and profanity filtering in Azure AI Translator?
5. How do you define custom translations using Azure AI Translator, and what is the process for creating a custom model?
6. What function of Azure AI Translator should you use to convert the Chinese word "你好" to the English word "Hello"?
7. What function of Azure AI Translator should you use to convert the Russian word "спасибо" in Cyrillic characters to "spasibo" in Latin characters?

## Create speech-enabled apps with Azure AI services
1. What are the steps to provision an Azure resource for speech services?
2. How do you use the Azure AI Speech to Text API, and what are the two REST APIs available for speech recognition?
3. What is the pattern for using the Azure AI Speech SDK for speech recognition and synthesis?
4. How can you configure audio format and voices for speech synthesis using Azure AI Speech?
5. What is Speech Synthesis Markup Language (SSML), and how can it be used to control speech synthesis?
6. What information do you need from your Azure AI Speech service resource to consume it using the Azure AI Speech SDK?
7. Which object should you use to specify that the speech input to be transcribed to text is in an audio file?
8. How can you change the voice used in speech synthesis?

## Translate speech with the Azure AI Speech service
1. What are the prerequisites for using the Azure AI Speech service for speech translation?
2. What is the pattern for speech translation using the Azure AI Speech SDK?
3. How do you specify the source and target languages for speech translation using the Azure AI Speech SDK?
4. What is the process for synthesizing translations as speech in speech-to-speech translation solutions?
5. Which SDK object should you use to specify the language(s) into which you want speech translated?
6. Which SDK object should you use as a proxy for the Translation API of Azure AI Speech service?
7. When translating speech, in which cases can you use the Synthesizing event to synthesize the translations and speech?

# Create computer vision solutions with Azure AI Vision
## Analyze images
1. What functionalities does the Azure AI Vision service provide?
2. How do you provision the Azure AI Vision service?
3. How can you analyze an image using the Azure AI Vision service?
4. What are the available visual features that can be analyzed by the Azure AI Vision service?
5. How does the Azure AI Vision service enable the generation of smart-cropped thumbnails?
6. How does the Azure AI Vision service's background removal feature work?

## Image classification with custom Azure AI Vision models
1. What are the different types of custom models available in Azure AI Vision?
2. What is the difference between image classification, object detection, and product recognition in Azure AI Vision?
3. What are the components of a custom Vision project in Azure AI Vision?
4. What is a COCO file and what information does it contain?
5. How do you create a dataset for training a custom model in Azure AI Vision?
6. What are the steps involved in labeling and training a custom model in Azure AI Vision?
7. How many images per class are recommended to train a custom image classification model with Azure AI Vision?
8. How can you access your custom image classification model after training it with Azure AI Vision?
9. What are the two types of custom models that you can train with Azure AI Vision?

## Detect, analyze, and recognize faces
1. What are the two Azure AI services that can be used to detect faces or people in images?
2. What are the capabilities of the Azure AI Vision service for face detection?
3. What additional facial analysis capabilities does the Face service offer compared to the Azure AI Vision service?
4. What are the ethical and responsible considerations when building a solution that uses facial data?
5. How do you detect and analyze faces with the Azure AI Vision service?
6. What are the comprehensive facial detection, analysis, and recognition capabilities provided by the Face service?
7. How do you compare and match detected faces using the Face service?
8. What are the steps to train a facial recognition model with the Face service?
9. You need to create a facial recognition solution to identify named employees. Which service should you use?
10. You need to verify that the person in a photo taken at hospital reception is the same person in a photo taken at a ward entrance 10 minutes later. What should you do?

## Read Text in images and documents with the Azure AI Vision Service
1. What are the two Azure AI features that read text from documents and images, and how do they differ?
2. When should you use the Image Analysis Optical Character Recognition (OCR) feature?
3. When is the Document Intelligence service recommended for use?
4. How do you use the Read OCR feature in the Image Analysis service?
5. What levels of division are the OCR results returned in?
6. Which API would be best for reading a large number of files with high accuracy, including short sections of handwritten text in multiple languages?
7. You've scanned a letter into PDF format and need to extract the text it contains. What should you do?

## Analyze video
1. What functionalities does the Azure Video Indexer service provide?
2. What are the requirements for using facial recognition in Azure Video Indexer?
3. How can you extend the recognition capabilities of Azure Video Analyzer with custom models?
4. What are the two ways you can incorporate Azure Video Indexer service into custom applications?
5. How do you use Azure Video Indexer widgets in custom HTML interfaces?
6. How do you obtain an access token and use the Azure Video Indexer API to automate video indexing tasks?
7. What is the purpose of Azure Resource Manager (ARM) templates in the context of Azure Video Indexer?
8. You want Azure Video Indexer to analyze a video. What must you do first?
9. You want Azure Video Indexer to recognize brands in videos recorded from conference calls. What should you do?

# Implement knowledge mining with Azure AI Search
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

# Develop solutions with Azure AI Document Intelligence
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

# Develop Generative AI solutions with Azure OpenAI Service
## Get started with Azure OpenAI Service
1. How do you provision an Azure OpenAI resource in your Azure subscription?
2. What steps do you need to follow to create an Azure OpenAI Service resource in the Azure portal?
3. How can you create an Azure OpenAI Service resource using the Azure CLI?
4. What is Azure OpenAI Studio, and what features does it provide for working with Azure OpenAI Service?
5. What types of generative AI models are available in Azure OpenAI, and what are their capabilities?
6. How do you deploy a generative AI model in Azure OpenAI Service, and what methods are available for deployment?
7. What is a prompt in the context of Azure OpenAI, and what types of tasks can prompts be used for?
8. What factors affect the quality of completions from a generative AI model in Azure OpenAI?
9. How can you test models in Azure OpenAI Studio's playgrounds, and what are the different types of playgrounds available?
10. Which Azure OpenAI base model can you deploy to access the capabilities of ChatGPT?
11. Which parameter can you adjust to change the randomness or creativeness of the completions returned by an Azure OpenAI model?
12. Which Azure OpenAI Studio playground supports conversation-in, message-out scenarios?

## Build natural language solutions with Azure OpenAI Service
1. How do you provision an Azure OpenAI resource in your Azure subscription?
2. What are the steps to create an Azure OpenAI resource using the Azure portal?
3. How can you create an Azure OpenAI resource using the Azure CLI?
4. What are the different families of models available in Azure OpenAI, and what tasks does each excel at?
5. What information do you need from your Azure OpenAI resource to authenticate and specify the deployed model in your application?
6. What is prompt engineering, and how does it affect the responses from Azure OpenAI models?
7. What are the available endpoints for interacting with deployed Azure OpenAI models, and what functionalities do they provide?
8. How do you install the necessary client libraries to use Azure OpenAI SDKs in your application?
9. What configuration is required in your application to access an Azure OpenAI resource?
10. How do you send a prompt to an Azure OpenAI model using the SDKs, and what optional parameters can you include in your request?
11. What resource values are required to make requests to your Azure OpenAI resource?
12. What are the three available endpoints for interacting with a deployed Azure OpenAI model, and which endpoint is best for modeling the next completion of a conversation?

## Apply prompt engineering with Azure OpenAI Service
1. What is prompt engineering, and why is it important when interacting with AI models like those in Azure OpenAI?
2. How can providing clear instructions in prompts improve the responses from Azure OpenAI models?
3. What considerations should be taken into account when formatting instructions in prompts?
4. How can section markers be used effectively in prompts?
5. What is the difference between primary, supporting, and grounding content in the context of prompt engineering?
6. How can cues be used to guide the responses of Azure OpenAI models?
7. Why might you want to break down a complex task into multiple queries when using Azure OpenAI?
8. What is few-shot learning, and how does it relate to providing conversation history to an AI model?
9. How can you use the system message in a prompt to influence the AI model's response?
10. What is the purpose of providing conversation history to an AI model, and how does it affect the model's performance?
11. How can developers optimize the performance of Azure OpenAI models through prompt engineering?
12. What is the purpose of the system message in a prompt, and how does it guide the AI model's response?

## Generate code with Azure OpenAI Service
1. What capabilities do Azure OpenAI models have in terms of generating code from natural language prompts?
2. Which Azure OpenAI models are particularly suited for code generation tasks?
3. How can Azure OpenAI models assist in writing functions or complete applications based on a description?
4. In what ways can Azure OpenAI help if you need to translate code from one programming language to another?
5. How can Azure OpenAI models be used to understand code that is written in an unfamiliar language or syntax?
6. How can Azure OpenAI assist developers in completing partial code and writing unit tests?
7. What role can Azure OpenAI play in adding comments and generating documentation for existing code?
8. How can Azure OpenAI models help identify and fix bugs in code or suggest performance improvements?
9. What are some benefits of using Azure OpenAI to generate code, and how can providing more context improve the accuracy of the model's response?
10. How can Azure OpenAI models be used to refactor inefficient code to make it more modular and maintainable?

## Generate images with Azure OpenAI Service
1. What is the primary function of the DALL-E model in Azure OpenAI?
2. How does DALL-E differ from a traditional image search system?
3. What is required to experiment with DALL-E in Azure OpenAI Studio?
4. In the DALL-E playground, what settings can you adjust to influence the generated images?
5. How do you use the Azure OpenAI REST API to generate images with DALL-E?
6. What information is included in the response from an image generation request using the Azure OpenAI REST API?
7. If you want to generate images using a model in Azure OpenAI, which model should you use?
8. Which playground in Azure OpenAI Studio is specifically designed for exploring image generation?
9. In a REST request to generate images with DALL-E, what does the parameter "n" indicate?
10. What are the available sizes for the resolution of images generated by DALL-E through the Azure OpenAI REST API?

## Implement Retrieval Augmented Generation (RAG) with Azure OpenAI Service
1. What is the purpose of Retrieval Augmented Generation (RAG) in Azure OpenAI?
2. How does Azure OpenAI enable RAG with your own data?
3. What are the steps involved in using RAG with Azure OpenAI on your data?
4. What is the difference between fine-tuning and RAG in the context of Azure OpenAI?
5. How can you add your own data source to Azure OpenAI for RAG?
6. What file types are supported when adding your own data to Azure OpenAI?
7. Why is it recommended to use Azure OpenAI Studio to create the search resource and index when adding your own data?
8. How can enabling semantic search improve the use of RAG with Azure OpenAI?
9. What considerations should be taken into account regarding token usage when using RAG with Azure OpenAI on your data?
10. How do you use the API to chat with your model using your own data in Azure OpenAI?

## Fundamentals of Responsible Generative AI
1. What are the four stages defined by Microsoft for developing a responsible generative AI solution?
2. What is the first stage in the responsible generative AI process and what are the steps involved in this stage?
3. Why is it important to prioritize identified potential harms in a generative AI solution?
4. What is "red team" testing and how is it used in the context of generative AI?
5. After identifying potential harms, what is the next step in ensuring a responsible generative AI solution?
6. Describe the process of measuring potential harms in a generative AI solution.
7. What are the layers at which potential harms can be mitigated in a generative AI solution?
8. How can the model layer be adjusted to mitigate potential harms in a generative AI solution?
9. What role do content filters play in the safety system layer of harm mitigation?
10. Why is it recommended to have a phased delivery plan for a generative AI solution?

# What are Azure AI services
## What are Azure AI services
1. What are Azure AI services and what types of applications can they enable?
2. How can developers access most Azure AI services?
3. What types of Azure AI services are available and what are their primary functions?
4. What is Azure AI Studio and how is it related to Azure AI services?
5. How are pricing tiers and billing structured for Azure AI services?
6. What are the development options available for working with Azure AI services?
7. What is the difference between using client libraries and REST APIs versus UI tools for Azure AI services?
8. How can continuous integration and deployment be utilized with Azure AI services?
9. What are the benefits of deploying Azure AI services in on-premises containers?
10. How can you train custom models with Azure AI services and what might be required when bringing your own data?
11. What ecosystem tools and services are available to enhance the capabilities of Azure AI services?
12. How can you find out about the regional availability and language support for Azure AI services?
13. What security measures are in place for Azure AI services?
14. What certifications and compliance standards do Azure AI services meet?
15. Where can you find help and support for Azure AI services?

# Azure AI services and the AI ecosystem
## Azure AI services and the AI ecosystem
1. What general problems can Azure AI services solve without requiring special machine learning or data science knowledge?
2. How do Azure AI services differ from Azure Machine Learning in terms of their target audience?
3. What are the benefits of using Azure AI services for big data, and which platforms and connectors do they support?
4. Who are the target users for Azure Databricks, Azure Synapse, Azure Kubernetes Service, and Data Connectors within the Azure AI ecosystem?
5. What is the role of Azure Functions and Azure App Service Web Jobs in integrating with Azure AI services?
6. How do Azure Logic Apps provide advanced control and integration for Azure AI services?
7. What are the benefits of using Azure Logic Apps, and who are the intended users?
8. Describe the purpose of Power Automate and its relationship with Azure Logic Apps.
9. Who are the target users for Power Automate, and what are its benefits?
10. What is AI Builder, and how does it integrate Azure AI services for business users?

# Custom subdomain names for Azure AI services
## Custom subdomain names for Azure AI services
1. When did Azure AI services start using custom subdomain names for each resource?
2. What is the purpose of using custom subdomain names for Azure AI services resources?
3. How do custom subdomain names impact existing Azure AI services resources created before July 2019?
4. What are the steps to migrate an existing Azure AI services resource to use a custom subdomain name?
5. Can a custom subdomain name be changed once it has been created for an Azure AI services resource?
6. Is it necessary to update existing Azure AI services resources to use custom subdomain names?
7. How do you find the region information for an Azure AI services resource?
8. Are custom subdomain names for Azure AI services regional or global?
9. What are the requirements for creating a custom subdomain name for an Azure AI services resource?
10. Can you reuse a custom subdomain name, and if so, under what conditions?
11. Where can you find a list of regional endpoints for Azure AI services?

# SDK, REST API, Accounts
## Azure AI services SDK reference
1. How can Azure AI services help developers meet their development goals?
2. What are some of the supported services listed in the Azure AI services SDK reference?
3. For each supported service, what types of tasks can developers perform using the Azure AI services SDKs?
4. Where can developers find the SDK and package documentation for Azure AI Search?
5. What natural language tasks can be performed with the Azure OpenAI Service SDK?
6. How can developers create and connect bots across channels using the Bot Service SDK?
7. What is the function of the Content Safety service and its associated SDK?
8. Describe the capabilities provided by the Custom Vision service and its SDK.
9. What solutions can be developed using the Document Intelligence service and its SDK?
10. How does the Face service SDK assist in detecting and recognizing human faces in images?
11. What natural language understanding capabilities are available through the Language service SDKs?
12. What speech-related features can be added to applications using the Speech service SDK?
13. How does the Translator service SDK enable translation of languages and dialects?
14. What functionalities does the Vision service SDK offer for analyzing digital images and media assets?

## Azure AI services REST API reference
1. How can developers utilize Azure AI services REST APIs to enhance their applications?
2. What types of cloud search capabilities does the Azure AI Search REST API provide?
3. Which REST APIs are available for the Azure OpenAI Service, and what tasks do they enable?
4. How can developers use the Bot Service REST API to create and manage bots?
5. What is the role of the Content Safety REST API in detecting unwanted content?
6. Describe the functionalities offered by the Custom Vision REST APIs for prediction and training.
7. What solutions can be developed using the Document Intelligence REST API?
8. How does the Face REST API assist in detecting and identifying people and emotions in images?
9. What capabilities does the Language REST API offer for natural language understanding?
10. What features can be added to applications using the Speech REST APIs for speech to text and text to speech?
11. How does the Translator REST API facilitate the translation of languages and dialects?
12. What insights can be extracted from videos using the Video Indexer REST API?
13. What functionalities does the Vision REST API offer for analyzing content in images and videos?

## Accounts
1. What is the purpose of creating a Cognitive Services account using the Azure AI Services API?
2. What does the Delete operation do in the context of a Cognitive Services account?
3. How can you retrieve the details of a specific Cognitive Services account using the API?
4. What is the List operation used for in Azure AI Services API management?
5. How does the List By Resource Group operation differ from the List operation?
6. What information is provided by the List Keys operation for a Cognitive Services account?
7. What is the purpose of the List Models operation in Azure AI Services?
8. How can you find out what SKUs are available for a Cognitive Services account?
9. What does the List Usages operation show for a Cognitive Services account?
10. How do you regenerate an account key for a Cognitive Services account?
11. What changes can be made to a Cognitive Services account using the Update operation?

## Practice Exam
1. When executing the initial run of the indexer in an Azure AI Search solution, which stages will be included?
2. In Azure AI Search, which type of projection should be used to save normalized binary files?
3. What are the minimum sections that should be included in a skillset definition for Azure AI Search?
4. Which `@odata.type` should be used to call a custom web app as part of an Azure AI Search solution?
5. To apply AI enrichment in an Azure AI Search indexer pipeline to generate links to Wikipedia articles, which skill should be used?
6. Which built-in skill should be used to extract content from a file within the enrichment pipeline by using AI enrichment in Azure AI Search?
7. In a generative Azure AI model, which two capabilities does the system message offer for the model?
8. When provisioning an Azure OpenAI service resource, which network security setting should be configured to ensure it is only available to applications hosted in your Azure subscription?
9. If an Azure OpenAI solution uses a newer version of a GPT-35-Turbo model than was initially deployed with auto-update disabled, why was the model version updated?
10. In a web app that generates images using the DALL-E 3 Azure OpenAI model, which HTTP body property should be included to ensure successful image generation?
11. When deploying an Azure OpenAI service that will use your own data, which additional Azure service should be deployed to ensure the model can index your data sources?
12. In a GPT-based chat application using Azure OpenAI, which four types of files can be used to ground the model with company data?
13. While testing a GPT-based chat application using Azure OpenAI, which parameter should be configured to filter out less-relevant documents for responses?
14. In an Azure OpenAI REST API service application that generates images using a DALL-E model, what does the `size` parameter indicate?
15. To build a bot that uses a knowledge base containing semi-structured data as part of user conversations, which service should be used?
16. To extract text and key/value pairs from scanned invoices, which service should be used?
17. To identify the prebuilt models available in Azure AI Document Intelligence for a solution that extracts information from documents, which three models are available?
18. To extract text from scanned receipts with minimal development effort, which service should be recommended?
19. To deploy an Azure AI Language solution to a location without internet connectivity, what should be done?
20. To identify the endpoint for an Azure AI Services resource using the Azure CLI, which command should be run?
21. To build an app that will use Azure AI Services, which two methods can be used to authenticate to Azure AI Services?
22. To configure an Azure App Services web app to use Azure AI Services with Microsoft Entra ID authentication, what should be done?
23. When developing a containerized OCR-capable application using Azure AI Services containers and encountering a "Mismatch" status message, what should be done to ensure the solution can connect to the AI Services resource?
24. To configure the Azure AI Language PII detection feature for an app that analyzes resumes, which categories should be specified in the request?
25. When analyzing a test document with one positive sentence and multiple neutral sentences using Azure AI Language, which label will the app return for the document?
26. To flag documents containing the names of staff members using Azure AI Language PII detection feature, which category should be used?
27. To configure a voice profile for an app that analyzes meeting recordings, which type of voice profile should be used?
28. To recommend an Azure AI Speech service model for an app that enables users to create notes by speech in noisy environments, which model should be recommended?
29. To implement the pattern matching intent recognition mechanism in an app that recognizes the intent and entities of user utterances in real-time, which entity type should be used?
30. When evaluating the use of intent recognition with Azure AI Speech and Azure AI Language services or simple pattern matching, when should pattern matching be used?
31. To improve the quality of translation for user-uploaded documents in an app that uses Azure AI Services Document Translation, what should users include when they upload a document?
32. To ensure that an Azure AI Translator custom model has a BLEU score indicating high quality, what is the minimum score range required?
33. To train a model that uses Conversational Language Understanding (CLU), which training methods can be used?
34. To configure workflows for multiple languages in an orchestration workflow for Language Understanding, what should be created for each language?
35. To measure how accurate a model is that uses Conversational Language Understanding (CLU), which metric should be used?
36. In an orchestration workflow based on Azure AI Language service, which two operations can be performed?
37. To optimize the performance of a multilingual CLU model serving multiple languages, what should be done?
38. To ensure that customer questions are included in the active learning suggestions for a question answering project, what should be done?
39. To ensure that an API call for a question answering solution executes successfully after receiving an error, what should be done?
40. To identify scenarios suitable for use with the Azure AI Language question answering service for a chatbot that helps users answer FAQs, which scenarios should be identified?
41. When using the Azure AI Language question answering service to import FAQ documents, which types of data will be extracted during the import process?
42. To optimize an app named App1 that uses the Azure AI Face service for images containing blurry faces, what should be done?
43. When evaluating the use of the Image Analysis API to detect the dominant background color of an image, which color can the API return as a dominant background color?
44. To detect the presence of people in a video feed using Azure AI Vision, which feature should be used?
45. To troubleshoot an issue with an app named App1 that extracts invoice data from PDF files using Azure AI Document Intelligence, what is a possible cause of the issue?
46. To detect when all the spaces in a parking lot are empty using the Azure AI Custom Vision API, which feature of the API should be used?
47. To analyze and classify images to build an image library of animals using Azure AI Vision, which type of classification should be used?
48. To extract keyframes from uploaded video and store them on a disk using the Azure AI Video Indexer API, how should the solution be implemented?
49. To configure the training and learning phases for a video processing app using Azure AI Video Indexer, which practices should be followed for the training data?
50. To enable multilingual identification in a video processing app using Azure AI Video Indexer, which value should be set for the `sourceLanguage` parameter?