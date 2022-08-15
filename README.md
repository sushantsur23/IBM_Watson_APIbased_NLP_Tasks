# NLP_Tasks

## This repo is prepared for NLP tasks using IBM Watson library

<img src="https://www.peterfisk.com/wp-content/uploads/2016/09/ibm_watson.png">

#### Project 1. AI Text to speech conversion
Here we have taken the IBM Cloud(Text to Speech-w9) API key and URL to use the API for text to speech conversion and also there are examples of how we can use a different language model as well.


#### Project 2. Speech to text conversion
Here we have taken the IBM Cloud(Speech to Text) API key and URL to use the API for speech to text conversion and also there are examples of how we can use a different language model as well.


#### Project 3. Language translation
Here we are using the language translation API to convert from one language to another language. We are also able to detect the language once the text is updated. One of the use case is Travel Guide where it will be immensely helpful.

#### Project 4. Voice translation
Analyzing the voice using IBM Watson and translating the same. COnverting Speech to text, and translating text to another language.

#### Project 5. Video to text
In this project we will consider a sample video and convert it to audio, Additionally convert video to text, we can also further save the results in a text file.

#### Project 6. Natural Language Understanding 
<Link src="https://cloud.ibm.com/apidocs/natural-language-understanding?code=python#categories">
Since IBM Watson Tone analyzer API has been deprecated hence Natural Langauge Understanding is the replacement with many more added features. The features are listed below with explanation of those.

1) Categories :- Returns a hierarchical taxonomy of the content. For example, a news website may return categories like /international news or /arts and entertainment. The top three categories are returned by default.

2) Classifications :- Classifies input using custom multi-label text classifier. For example, a custom weather classifier may return classifications such as "temperature" or "condition".

3) Concepts :- Returns high-level concepts in the content. For example, a research paper about deep learning might return the concept, "Artificial Intelligence" although the term is not mentioned.

4) Emotion :- Detects anger, disgust, fear, joy, or sadness that is conveyed in the content or by the context around target phrases specified in the targets parameter. You can analyze emotion for detected entities with entities.emotion and for keywords with keywords.emotion.

5) Entities :- Identifies people, cities, organizations, and other entities in the content. See Entity type systems.

6) Keywords :- Returns important keywords in the content. For example, analyzing a company's press release could return keywords such as "sustainability", "hybrid cloud", or "IBM".

7) Metadata :- Returns information from the document, including author name, title, RSS/ATOM feeds, prominent page )image, and publication date. Supports URL and HTML input types only.

8) Relations :- Recognizes when two entities are related and identifies the type of relation. For example, an awardedTo relation might connect the entities "Nobel Prize" and "Albert Einstein".

9) Semantic Roles :- Parses sentences into subject, action, and object form.

10) Sentiment :- Analyzes the general sentiment of your content or the sentiment toward specific target phrases. As an example, the phrase "Thank you and have a nice day!" returns a positive sentiment (score .91). You can analyze sentiment for detected entities with entities.sentiment and for keywords with keywords.sentiment .

11) Syntax :- Returns information about the tokens and sentences in the input text. At least one of syntax.tokens or syntax.sentences must be specified.