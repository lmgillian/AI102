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