---
title: "Here is what makes a good voice assistant"
show_date: true
excerpt: "The ease of use of voice recognition should not overshadow the advanced technologies it uses: voice recognition algorithm, ability to detect accents and dialect, management of 'background noise', dictation transcription speed..."
tags:
  - Technology
  - Natural Language Processing
header:
  teaser: "/assets/images/posts/20230418-hero.jpg"
image_path: "/assets/images/posts/20230418-hero.jpg"
---

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/20230418-hero.jpg" alt="several people around a table" class="full" loading="lazy">
<figcaption style="color:grey; font-size:10px;">Picture by <a href="https://unsplash.com/@jasonrosewell">Jason Rosewell</a> on <a href="https://unsplash.com">Unsplash</a>
  </figcaption>
</figure>

_The ease of use of voice recognition should not overshadow the advanced technologies it uses. Voice recognition algorithm, ability to detect accents and dialect, management of 'background noise', dictation transcription speed... a high-performance voice transcription solution owes nothing to chance._

Speech recognition software is based on 3 categories of technology: “Speech to Text” (STT), “Natural Language Processing” (NLP) and artificial intelligence (AI).

## Speech to Text (STT), identifying and transcribing voice into text
Once voice recognition has been initiated using the trigger word, it is necessary to use the voice. For this, it is first essential to record it and digitize it with Speech to Text technology (also known as automatic speech recognition).
During this stage, the voice is captured in sound frequencies (in the form of audio files, like music or any other noise) that can be used later.
Depending on the listening environment, noise pollution is present or not. In order to improve the recording of these frequencies and therefore at the same time their reliability, various processing operations can be carried out.
- Normalization to remove peaks and dips in frequencies to harmonize the whole
- Background noise suppression to improve audio quality
- The division of the segments into phonemes (which are distinctive units within the frequencies, expressed in thousandths of a second, making it possible to distinguish the words from each other
The frequencies, once recorded, can be analyzed in order to associate each phoneme with a word or a group of words to constitute a text. This step can be done in different ways, but one method in particular is the state of the art today: Machine Learning.
A subpart of this technology is called Deep Learning: an algorithm that recreates a neural network, capable of analyzing a large amount of information and building a database of associations between frequencies and words. Thus, each association will create a neuron which will be used to deduce new correspondences.
Therefore, the more information there is, the more the model is statistically accurate and able to take into account the general context to assign the best word according to the others already defined.
Limiting the errors of the STT is essential to obtain the most reliable information in order to proceed to the next steps.

## NLP (Natural Language Processing), translating human language into machine language
Once the previous steps have been completed, the textual data is sent directly to the NLP (Natural Language Processing) module. The main purpose of this technology is to analyze the sentence and extract as much linguistic data as possible.
 
To do this, it begins by associating tags with the words of the sentence, this is called tokenization. These are actually “labels” that are affixed to each word in order to characterize them. For example, “Open” will be defined as the verb defining an action, “le” as the determiner relating to “Voice Development Kit” which is a proper noun but also a COD etc… and this for each of the elements of the sentence.
As soon as these first elements are identified, it is necessary to give meaning to the orders resulting from voice recognition. This is why two complementary analyzes are carried out.
First, the syntactic analysis which aims to model the structure of the sentence. It is a question here of identifying the place of the words within the whole but also their relative position compared to the others in order to understand their relations.
To complete and finish, the semantic analysis which, once the nature and position of the words have been found, will try to understand their meaning individually but also when they are assembled in the sentence in order to translate a general intention of the user.
The importance of NLP in speech recognition lies in its ability to translate textual elements (i.e. words and sentences) into standardized orders, including meaning and intent, that can be interpreted by the associated artificial intelligence and carried out.

## Artificial intelligence, a necessary ally of voice recognition
First of all, artificial intelligence, although integrated into the process of previous technologies, is not always essential to achieve use cases. Indeed, if we are talking about connected technologies (therefore Cloud), AI will have its uses. Especially since the complexity of certain use cases, in particular on the information to be correlated to produce them, makes it mandatory.
For example, it is sometimes necessary to compare several pieces of information with actions to be carried out, integration of external or internal services or databases to be consulted.
In other words, artificial intelligence is the use case itself, the concrete action that will result from the voice interface. Depending on the context of use and the nature of the order, the elements requested and the results given will be different.
AI is a centerpiece in many situations. However, for embedded functionalities (therefore offline), the needs are less, closer to the realization of simple commands such as navigation on an interface or the report of actions. This is to have specific use cases that do not require consulting multiple information.

## Test speech-to-text technology for free, without commitment nor credit card
autoScrib is a voice recognition app and website that increases productivity during meetings and lectures. Dictate your notes or let IA transcribe the entire speech.
See you soon on [autoScrib.com](https://autoscrib.com)
