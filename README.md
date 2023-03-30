# awesome-ai-services [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An overview of the AI-as-a-service landscape

## Sharing
- [Share on Twitter](http://twitter.com/home?status=http://github.com/salinourian/awesome-ai-services)
- [Share on Facebook](http://www.facebook.com/sharer/sharer.php?u=http://github.com/salinourian/awesome-ai-services)
- [Share on Google Plus](http://plus.google.com/share?url=http://github.com/salinourian/awesome-ai-services)
- [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=http://github.com/salinourian/awesome-ai-services)

## Table of Contents

### Natural Language
- [Entity Recognition](#entity-recognition)
- [Keyphrase Extraction](#keyphrase-extraction)
- [Machine Translation](#machine-translation)
- [Sentiment Analysis](#sentiment-analysis)

## Speech
- [Speech to Text / Speech Recognition](#speech-to-text)
- [Text to Speech / Speech Synthesis](#text-to-speech)

### Vision
- [Face Detection](#face-detection)
- [Text Recognition](#text-recognition)

# Natural Language

## Entity Recognition
[Sample input](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/sample-input.txt)

### Amazon Comprehend
General: [Overview](https://docs.aws.amazon.com/comprehend/latest/dg/how-entities.html) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/amazon-comprehend/sample-output.json) | [UI](https://console.aws.amazon.com/comprehend/v2/home?region=us-east-1#home) | [Pricing](https://aws.amazon.com/comprehend/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/amazon-comprehend/amazon-comprehend-entity-recognition.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-comprehend) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/amazon-comprehend/AmazonComprehendEntityRecognition.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/amazon-comprehend/AmazonComprehendEntityRecognition.kt)

- What are the entities mentioned in the document?
- What are their types?
- How often is each of these entities mentioned?

Supported entity types: commercial items, dates, events, locations, organizations, persons, quantities, other types, titles

### Google Cloud Natural Language
General: [Overview](https://cloud.google.com/natural-language/docs/reference/rest/v1/Entity) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/google-cloudnatural-language/sample-output.json) | [Demo](https://cloud.google.com/natural-language/) | [Pricing](https://cloud.google.com/natural-language/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/language) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/google-cloud-natural-language/google-cloud-natural-language-entity-recognition.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-language) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/google-cloud-natural-language/GoogleCloudNaturalLanguageEntityRecognition.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/google-cloud-natural-language/GoogleCloudNaturalLanguageEntityRecognition.kt)

- What are the entities mentioned in the document?
- What are their types?
- How salient is each of these entities in the document?
- Where in the text are these entities mentioned?
- What are the URLs to the corresponding Wikipedia entries?

Supported entity types: consumer good, event, location, organization, person, work of art, other types

### IBM Watson Natural Understanding
General: [Overview](https://console.bluemix.net/docs/services/natural-language-understanding/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/ibm-watson-natural-language-understanding/sample-output.json) | [Demo](https://natural-language-understanding-demo.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-natural-language-understanding/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/ibm-watson-natural-language-understanding/ibm-watson-natural-language-understanding-entity-recognition.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/natural-language-understanding) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingEntityRecognition.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingEntityRecognition.kt)

- What are the entities mentioned in the document?
- What are their types and subtypes?

Supported entity types:
- Types: anatomy, award, broadcaster, company, crime, drug, email address, facility, geographic feature, health condition, hashtag, ip address, job title, location, movie, music group, natural event, organization, person, print media, quantity, sport, sporting event, television show, twitter handle, vehicle
- [Subtypes](https://console.bluemix.net/docs/services/natural-language-understanding/entity-types-v1.html#entity-types-and-subtypes-version-1-#entity-subtypes)

### Microsoft Cognitive Services Text Analytics (Preview)
General: [Overview](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/how-tos/text-analytics-how-to-entity-linking) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/microsoft-cognitive-services-text-analytics/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/text-analytics/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/microsoft-cognitive-services-text-analytics/microsoft-text-analytics-entity-recognition.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsEntityRecognition.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/entity-recognition/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsEntityRecognition.kt)

- What are the entities mentioned in the document?
- Where in the document are they mentioned?
- What are the URLs to the corresponding Wikipedia entries?
- What are their Wikipedia and Bing IDs?

## Keyphrase Extraction
[Sample input](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/sample-input.txt)

### Amazon Comprehend
General: [Overview](https://aws.amazon.com/comprehend/features/#Keyphrase_Extraction) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/amazon-comprehend/sample-output.json) | [Demo](https://console.aws.amazon.com/comprehend/v2/home?region=us-east-1#home) | [Pricing](https://aws.amazon.com/comprehend/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/amazon-comprehend/amazon-comprehend-keyphrase-extraction.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-comprehend) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/amazon-comprehend/AmazonComprehendKeyphraseExtraction.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/amazon-comprehend/AmazonComprehendKeyphraseExtraction.kt)

- Which keywords can be extracted for the given document?
- How often do each of these keywords occur?

### Google Cloud Natural Language
*Not supported*

### IBM Watson Natural Understanding
General: [Overview](https://console.bluemix.net/docs/services/natural-language-understanding/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/ibm-watson-natural-language-understanding/sample-output.json) | [Demo](https://natural-language-understanding-demo.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-natural-language-understanding/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/ibm-watson-natural-language-understanding/ibm-watson-natural-language-understanding-keyphrase-extraction.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/natural-language-understanding) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingKeyphraseExtraction.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingKeyphraseExtraction.kt)

- Which keywords can be extracted for the given document?

### Microsoft Cognitive Services Text Analytics
General: [Overview](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/how-tos/text-analytics-how-to-keyword-extraction) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/microsoft-cognitive-services-text-analytics/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/text-analytics/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/microsoft-cognitive-services-text-analytics/microsoft-text-analytics-keyphrase-extraction.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsKeyphraseExtraction.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/keyphrase-extraction/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsKeyphraseExtraction.kt)

- Which keywords can be extracted for the given document?

## Machine Translation
[Sample input](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/sample-input.txt)

### Amazon Translate
General: [Overview](https://aws.amazon.com/translate/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/amazon-translate/sample-output.txt) | [UI](https://console.aws.amazon.com/translate/home?region=us-east-1#explorer) | [Pricing](https://aws.amazon.com/translate/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/amazon-translate/amazon-translate-machine-translation.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-translate) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/amazon-translate/AmazonTranslateMachineTranslation.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/amazon-translate/AmazonTranslateMachineTranslation.kt)

Support for [seven languages](https://aws.amazon.com/translate/details/)

### Google Cloud Translation API
General: [Overview](https://cloud.google.com/translate/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/google-cloud-translation/GoogleCloudTranslationMachineTranslation.java) | [Demo](https://cloud.google.com/translate/#translate_demo_section) | [Pricing](https://cloud.google.com/translate/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/translate) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/google-cloud-translation/google-cloud-translation-machine-translation.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-translate) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/google-cloud-translation/GoogleCloudTranslationMachineTranslation.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/google-cloud-translation/GoogleCloudTranslationMachineTranslation.kt)

Support for [98 language pairs](https://cloud.google.com/translate/docs/languages#languages-nmt) in neural machine translation model

### IBM Watson Language Translator
General: [Overview](https://www.ibm.com/watson/services/language-translator/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/sample-output.txt) | [Demo](https://www.ibm.com/watson/services/language-translator/#demo) | [Price](https://www.ibm.com/cloud/watson-language-translator/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/ibm-watson-language-translator/ibm-watson-language-translator-machine-translation.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/language-translator) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/MicrosoftTranslatorTextMachineTranslation.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/MicrosoftTranslatorTextMachineTranslation.kt)

Support for [33 language pairs](https://console.bluemix.net/docs/services/language-translator/translation-models.html#translation-models)

### Microsoft Cognitive Services Translator Text
General: [Overview](https://azure.microsoft.com/en-us/services/cognitive-services/translator-text-api/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/sample-output.txt) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/translator-text-api/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/microsoft-translator-text-machine-translation.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/MicrosoftTranslatorTextMachineTranslation.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/machine-translation/microsoft-translator-text/MicrosoftTranslatorTextMachineTranslation.kt)

Support for [39 language pairs](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/languages) 

## Sentiment Analysis
[Overview](https://towardsdatascience.com/machine-learning-as-a-service-487e930265b2) | [Sample input](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/sample-input.txt)

### Amazon Comprehend
General: [Overview](https://aws.amazon.com/comprehend/features#Sentiment_Analysis) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/amazon-comprehend/sample-output.json) | [Demo](https://console.aws.amazon.com/comprehend/v2/home?region=us-east-1#home) | [Pricing](https://aws.amazon.com/comprehend/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/amazon-comprehend/amazon-comprehend-sentiment-analysis.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-comprehend) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/amazon-comprehend/AmazonComprehendSentimentAnalysis.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/amazon-comprehend/AmazonComprehendSentimentAnalysis.kt)

- To what extent does the document express an overal positive, negative, neutral or mixed sentiment?

### Google Cloud Natural Language
General: [Overview](https://cloud.google.com/natural-language/docs/analyzing-sentiment) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/google-cloud-natural-language/sample-output.json) | [Demo](https://cloud.google.com/natural-language/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/text-analytics/)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/language) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/google-cloud-natural-language/google-cloud-natural-language-sentiment-analysis.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-language) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/google-cloud-natural-language/GoogleCloudNaturalLanguageSentimentAnalysis.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/google-cloud-natural-language/GoogleCloudNaturalLanguageSentimentAnalysis.kt)

- To what extent does the document express an overal positive, negative, neutral or mixed sentiment?

### IBM Watson Natural Understanding
General: [Overview](https://console.bluemix.net/docs/services/natural-language-understanding/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/ibm-watson-natural-language-understanding/sample-output.json) | [Demo](https://natural-language-understanding-demo.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-natural-language-understanding/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/ibm-watson-natural-language-understanding/ibm-watson-natural-language-understanding-sentiment-analysis.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/natural-language-understanding) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingSentimentAnalysis.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/ibm-watson-natural-language-understanding/IbmWatsonNaturalLanguageUnderstandingSentimentAnalysis.kt)

- To what extent does the document express an overal positive, negative or neutral sentiment?

### Microsoft Cognitive Services Text Analytics
General: [Overview](https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/how-tos/text-analytics-how-to-sentiment-analysis) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/microsoft-cognitive-services-text-analytics/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/text-analytics/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/microsoft-cognitive-services-text-analytics/microsoft-text-analytics-sentiment-analysis.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsSentimentAnalysis.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/sentiment-analysis/microsoft-cognitive-services-text-analytics/MicrosoftCognitiveServicesTextAnalyticsSentimentAnalysis.kt)

- To what extent does the document express an overal positive, negative or neutral sentiment?

# Speech

<h2 id="speech-to-text">Speech to Text / Speech Recognition</h2>

[Sample input](http://awesome-ai-services.s3.amazonaws.com/speech-recognition/greys-anatomy-introduction-60-seconds.mp3)

### Amazon Transcribe
General: [Overview](https://aws.amazon.com/transcribe/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/amazon-transcribe/sample-output.json) | [UI](https://console.aws.amazon.com/transcribe/home) | [Pricing](https://aws.amazon.com/transcribe/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/amazon-transcribe/amazon-transcribe-speech-recognition.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-transcribe) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/amazon-transcribe/AmazonTranscribeSpeechToText.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/amazon-transcribe/AmazonTranscribeSpeechToText.kt)

Support for US English and Spanish

### Google Cloud Speech-to-Text
General: [Overview](https://cloud.google.com/speech-to-text/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/google-cloud-speech-to-text/sample-output.txt) | [Demo](https://cloud.google.com/speech-to-text/) | [Pricing](https://cloud.google.com/speech-to-text/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/speech) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/google-cloud-speech-to-text/google-cloud-speech-to-text.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-speech) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/google-cloud-speech-to-text/GoogleCloudSpeechToText.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/google-cloud-speech-to-text/GoogleCloudSpeechToText.kt)

Support for 119 languages/locales

### IBM Speech to Text
General: [Overview](https://www.ibm.com/watson/services/speech-to-text) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/ibm-watson-speech-to-text/sample-output.json) | [Demo](https://speech-to-text-demo.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-speech-to-text/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/ibm-watson-speech-to-text/ibm-watson-speech-to-text.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/speech-to-text) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/ibm-watson-speech-to-text/IbmWatsonSpeechToText.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/ibm-watson-speech-to-text/IbmWatsonSpeechToText.kt)

Support for 9 languages

### Microsoft Cognitive Services Speech to Text (Preview)
General: [Overview](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/microsoft-cognitive-services-speech-to-text/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/speech-services/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/microsoft-cognitive-services-speech-to-text/microsoft-cognitive-services-speech-recognition.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/microsoft-cognitive-services-speech-to-text/MicrosoftCognitiveServicesSpeechToText.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-recognition/microsoft-cognitive-services-speech-to-text/MicrosoftCognitiveServicesSpeechToText.kt)

The REST API is limited to utterances of up to [14 seconds](https://docs.microsoft.com/gl-es/azure/cognitive-services/speech-service/rest-apis#speech-to-text).

Support for 8 languages

<h2 id="text-to-speech">Text to Speech / Speech Synthesis</h2>

[Overview](https://towardsdatascience.com/speech-synthesis-as-a-service-5c65d17e62f4) | [Sample input](https://github.com/salinourian/awesome-ai-services/tree/master/speech-synthesis/sample-input)

### Amazon Polly
General: [Overview](https://aws.amazon.com/polly/) | [Sample output](https://soundcloud.com/sebastian-e-kwiatkowski/sets/amazon-polly) | [UI](https://console.aws.amazon.com/polly/home) | [Pricing](https://aws.amazon.com/polly/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/amazon-polly/amazon-polly-speech-synthesis.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-polly) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/amazon-polly/AmazonyPollyTextToSpeech.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/amazon-polly/AmazonyPollyTextToSpeech.kt)

34 voices in 25 languages

SSML extensions:
- Breathing
- Dynamic Range Compression
- Speaking softly
- Timbre
- Whispering

### Google Cloud Text-to-Speech (Beta)
General: [Overview](https://cloud.google.com/text-to-speech/) | [Sample output](https://soundcloud.com/sebastian-e-kwiatkowski/sets/google-cloud-text-to-speech) | [Demo](https://cloud.google.com/text-to-speech/) | [Pricing](https://cloud.google.com/text-to-speech/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/text-to-speech) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/google-cloud-text-to-speech/google-cloud-text-to-speech.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-speech) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/google-cloud-text-to-speech/GoogleCloudTextToSpeech.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/google-cloud-text-to-speech/GoogleCloudTextToSpeech.kt)

28 voices in 14 languages

### IBM Watson Text to Speech
General: [Overview](https://www.ibm.com/watson/services/text-to-speech/) | [Sample output](https://soundcloud.com/sebastian-e-kwiatkowski/sets/ibm-watson-text-to-speech) | [Demo](https://text-to-speech-demo.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-text-to-speech/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/ibm-watson-text-to-speech/ibm-watson-text-to-speech.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/text-to-speech) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/ibm-watson-text-to-speech/IbmWatsonTextToSpeech.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/ibm-watson-text-to-speech/IbmWatsonTextToSpeech.kt)

13 voices in 7 languages

SSML extensions:
- Good news
- Apology
- Uncertainty

Customization:
- Pitch
- Glottal tension
- Breathiness
- Timbre

### Microsoft Cognitive Services Text to Speech (Preview)
General: [Overview](https://azure.microsoft.com/en-us/services/cognitive-services/text-to-speech/) | [Sample output](https://soundcloud.com/sebastian-e-kwiatkowski/sets/microsoft-cognitive-services) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/text-to-speech/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/speech-services/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/microsoft-cognitive-services-text-to-speech/microsoft-cognitive-services-speech-synthesis.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/microsoft-cognitive-services-text-to-speech/MicrosoftCognitiveServicesTextToSpeech.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/speech-synthesis/microsoft-cognitive-services-text-to-speech/MicrosoftCognitiveServicesTextToSpeech.kt)

80 voices in 32 languages

Customization in private preview

# Vision

## Face Detection
[Sample input](http://awesome-ai-services.s3.amazonaws.com/face-detection/face-detection-sample-input.jpg)

### Amazon Rekognition
General: [Overview](https://aws.amazon.com/rekognition/image-features/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/amazon-rekognition/sample-output.json) | [Demo](https://console.aws.amazon.com/rekognition/home?region=us-east-1#/face-detection) | [Pricing](https://aws.amazon.com/rekognition/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/amazon-rekognition/amazon-rekognition-face-detection.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-rekognition) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/amazon-rekognition/AmazonRekognitionFaceDetection.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/amazon-rekognition/AmazonRekognitionFaceDetection.kt)

- Where are the faces and face parts located in the image?
- What are the age ranges of the persons shown?
- Are they smiling?
- Do they wear eyeglasses or sunglasses?
- What are their genders?
- Do they have a beard or mustache?
- Are their eyes or mouth open?
- Do they express emotions of happiness, sadness, anger, confusion, disgust, surprise or calmness?
- Given a face image, what other image shows the most similar face?
- Are the faces in two images of the same person?

### Google Cloud Vision
General: [Overview](https://cloud.google.com/vision/docs/detecting-faces) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/google-cloud-vision/sample-output.json) | [Demo](https://cloud.google.com/vision/) | [Pricing](https://cloud.google.com/vision/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/vision) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/google-cloud-vision/google-cloud-vision-face-detection.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-vision) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/google-cloud-vision/GoogleCloudVisionFaceDetection.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/google-cloud-vision/GoogleCloudVisionFaceDetection.kt)

- Where are the faces and face parts located in the image?
- What is the pose of the faces?
- Does the faces express emotions states of joy, sorrow, anger or surprise?
- Is the person wearing headwear?
- Is the photo underexposed or blurred?

### IBM Watson Visual Recognition
General: [Overview](https://console.bluemix.net/docs/services/visual-recognition/getting-started.htm) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/ibm-watson-visual-recognition/sample.output.json) | [Demo](https://watson-visual-recognition-duo-dev.ng.bluemix.net/) | [Pricing](https://www.ibm.com/cloud/watson-visual-recognition/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/watson-developer-cloud) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/ibm-watson-visual-recognition/ibm-watson-visual-recognition-face-detection.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.ibm.watson.developer_cloud/visual-recognition) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/ibm-watson-visual-recognition/IbmWatsonVisualRecognitionFaceDetection.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/ibm-watson-visual-recognition/IbmWatsonVisualRecognitionFaceDetection.kt)

- Where are the faces located in the image?
- What are the age ranges of the persons shown?
- What are their genders?

### Microsoft Cognitive Services Face
General: [Overview](https://azure.microsoft.com/en-us/services/cognitive-services/face/) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/microsoft-cognitive-services-face/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/face/) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/face-api/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/microsoft-cognitive-services-face/microsoft-cognitive-services-face-face-detection.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/microsoft-cognitive-services-face/MicrosoftCognitiveServicesFaceFaceDetection.java) | [Kotlin](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/microsoft-cognitive-services-face/MicrosoftCognitiveServicesFaceFaceDetection.kt)

- What are the faces and face parts located in the image?
- Are parts of the faces occluded?
- What is the pose of the heads?
- How old are they?
- What are their genders?
- Does the face express the emotional states of anger, contempt, disgust, fear, happiness sadness, surprise or a neutral state?
- Arey they smiling?
- Is the hair visible? What is the hair color? Or is the person bald?
- Do they have a moustache, a beard or sideburns?
- Are they wearing make-up?
- What kind of acessories is the person wearing, if any?
- What kind of glasses is the person wearing, if any?
- Is the photo blurred? What is the exposure level? What is the noise level?
- Are the faces in two images of the same person?

## Text Recognition
[Sample input](http://awesome-ai-services.s3.amazonaws.com/text-recognition/welcome-to-utah.jpg)

### Amazon Rekognition
General: [Overview](https://docs.aws.amazon.com/rekognition/latest/dg/text-detection.html) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/amazon-rekognition/sample-output.json) | [Demo](https://console.aws.amazon.com/rekognition/home?region=us-east-1#/text-detection) | [Pricing](https://aws.amazon.com/rekognition/pricing/)

JavaScript: [NPM](https://www.npmjs.com/package/aws-sdk) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/face-detection/amazon-rekognition/amazon-rekognition-face-detection.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-rekognition/1.11.351) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/amazon-rekognition/AmazonRekognitionTextRecognition.java)

- Where in the image file is text located?
- What is the text content?
- Which boxes do individual words belong to?

### Google Cloud Vision
General: [Overview](https://cloud.google.com/vision/docs/ocr) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/google-cloud-vision/sample-output.json) | [Demo](https://cloud.google.com/vision/) | [Pricing](https://cloud.google.com/vision/pricing)

JavaScript: [NPM](https://www.npmjs.com/package/@google-cloud/vision) | [Node](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/google-cloud-vision/google-cloud-vision-text-recognition.js)

JVM: [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-vision) | [Java](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/google-cloud-vision/GoogleCloudVisionTextRecognition.java)

- Where in the image file is text located?
- What is the text content?
- What is the language of the text content?

### IBM Watson Visual Recognition
*This feature is currently in [private beta](https://datasciencex.typeform.com/to/nU6efl).*

### Microsoft Cognitive Services Computer Vision
General: [Overview](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/#text) | [Sample output](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/microsoft-cognitive-services-computer-vision/sample-output.json) | [Demo](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/#text) | [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/computer-vision/)

JavaScript: [Node](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/microsoft-cognitive-services-computer-vision/microsoft-cognitive-services-cv-text-recognition.js)

JVM: [Java](https://github.com/salinourian/awesome-ai-services/blob/master/text-recognition/microsoft-cognitive-services-computer-vision/MicrosoftCognitiveServicesComputerVisionTextRecognition.java)

- Where in the image file is text located?
- What is the text content?

## License
[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
