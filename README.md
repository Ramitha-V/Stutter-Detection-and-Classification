# Stutter Detection and Classification

Stuttering is a neuro-developmental speech disorder that interrupts the flow of speech due to involuntary pauses and sound repetitions. It has profound psychological impacts that affect social interactions and professional advancements. 

Automatically detecting stuttering events in speech recordings could assist speech therapists or speech pathologists track the fluency of people who stutter (PWS). It will also assist in the improvement of the existing speech recognition system for PWS. 

In this project, the SEP-28k dataset is utilized to perform comparative analysis to assess the performance of various machine learning models in classifying the five dysfluency types namely Prolongation, Interjection, Word Repetition, Sound Repetition and Blocks.

## Contributions:

 1. Developing robust machine learning models for classifying the five classes of Stutter- Interjection, Prolongation, Blocks, Sound Repetitions and Word Repetitions.
 2. Conducting analysis on the impact of various features extracted manually as well as using pre-trained models.
 3. Performing comparative analysis on each class of stutter using various machine learning models. 

## Dataset
The SEP-28k dataset, published by Apple Machine Learning Research, is used for training and evaluation.It consists of audio recordings from six podcast shows and is annotated with various dysfluency types. The dataset is multi-label and multi-class, with annotations done by at least three annotators.

**Annotations: The SEP-28k dataset includes annotations for audio clips, labeled by at least three annotators. These labels cover various categories such as 'Unsure', 'PoorAudioQuality', 'Music', 'DifficultToUnderstand', 'Interjection', 'Prolongation', 'Blocks', 'WordRep', 'SoundRep', 'NoStutteredWords', 'NoSpeech', and 'NaturalPause'. Each 3-second clip can have multiple labels, making the dataset both multi-label and multi-class. 
- Negative Correlation: 'NoStutteredWords' and the five dysfluency classes are rarely labeled together, showing strong inter-annotator agreement.
- Weak Positive Correlations:
'Block' and 'NaturalPause' (0.11): Annotators struggle to distinguish between these, often requiring physical cues.
'PoorAudioQuality' and 'DifficultToUnderstand' (0.20): Annotators frequently label the same clips with these categories.
   


<p align="center">
    <img width="550" alt="image" src="https://github.com/Ramitha-V/Stutter-Detection-and-Classification/assets/162662008/bd132e26-b6da-4016-a542-19843db8c81a">
</p>





