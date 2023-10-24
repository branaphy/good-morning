# Morning Mist vs. Evening Clarity: A Comparative Study of Vowel Space Area and Speech Rate
Authors: Brandi Hongell, Page, Xueying Liu, Yi Lei, Yilan Wei

## Introduction

Fatigue and its impact on cognitive functions have been subjects of extensive research over the years. The state of tiredness, often influenced by the circadian rhythm, can significantly affect an individual’s motor and 
cognitive abilities, thereby potentially altering the acoustic properties of speech. 

The motivation behind this study stems from the curiosity to explore how "morning grogginess" may impact speech production, which could have substantial implications in fields like voice recognition technology, speech 
pathology, and human-computer interaction. The goal of this study is to analyze and compare the vowel space area and speech rate of the specified phrase recorded by participants immediately upon waking and later at 8:00pm 
over a span of three days. By discerning any noticeable patterns in speech rate or vowel space areas, this study aims to contribute valuable insights into the temporal dynamics of vocal articulation. 

Moreover, the insights garnered from this study could significantly contribute to real-world applications, notably in the realm of fatigue/tiredness detection technologies. Understanding how speech parameters such as vowel 
space area and speech rate may be altered by tiredness lays foundational knowledge for developing sophisticated fatigue/tiredness detection systems, particularly for drivers. Such advancements could be pivotal in 
enhancing road safety by alerting drivers of fatigue in real-time, thereby reducing the likelihood of fatigue-related accidents. Additionally, the findings could fuel the creation of more adaptive voice recognition 
systems that account for variations in speech due to different levels of alertness, such as smart home systems. In an era where voice-activated systems are becoming increasingly common in our daily lives, tailoring these 
technologies to accurately respond to speech, regardless of the user's state of tiredness, is imperative. Beyond safety, this study also paves way for improving communication tools and technologies, ensuring they remain 
effective and reliable under varying physiological states. The potential extensions of this research underline its relevance and applicability in addressing contemporary challenges in both safety and communication domains.

## Methods
We conduct research in the following ways:

1. Participant:
We have 5 participants. The gender composition is 1 male and 4 females. The nationality composition is 1 American and 4 Chinese.

2. Experimental design: 
Each participant will be asked to read specific short sentences at two time points over three days. The short sentence text is “Ah, good morning, I’m going to brew a cup of coffee.” The first time point will be set shortly after they wake up to capture morning speech expressions, while the second time point will be set at 8:00 pm to capture evening speech expressions. These two time points were chosen to compare speech performance in the morning and evening.

3. Recording and data collection: 
Participants will be asked to conduct voice recordings at designated time points to ensure that the recording conditions are relatively consistent. Everyone has submitted 6 audio files in wav format on github.

4. Data analysis:
Use praat to get the speech rate and the F1 and F2 values for each vowel. Use statistical methods and create data visualizations in R. We compared morning and evening speech data for different participants to detect whether there were significant differences. The script to analyze VSA is available here https://search.r-project.org/CRAN/refmans/phonR/html/vowelSpaceArea.html

## Results

Through data visualization, we found significant differences in speech rates in the morning and evening. The speech rate is lower in the morning and obviously increases in the evening. The same was true for each participant's speech rate graph.

![speech_rate](https://github.com/branaphy/good-morning/assets/144012055/c2523695-ba0c-42ac-9b3b-a619600560e0)
![Brandi](https://github.com/branaphy/good-morning/assets/144012055/80a15a88-d2fb-49eb-8414-f3943d66181b)
![Xueying](https://github.com/branaphy/good-morning/assets/144012055/dd3c35b7-af3d-4f65-b2b5-5054436dc6c3)
![Yi](https://github.com/branaphy/good-morning/assets/144012055/7e79a066-a53a-42e0-bafe-a517c44c5fb9)
![Yilan](https://github.com/branaphy/good-morning/assets/144012055/02e3a9aa-ba6c-442b-8516-5e9952999c7b)
![Page](https://github.com/branaphy/good-morning/assets/144012055/b199b099-0eb2-4dba-b4cd-d60c27d276f5)

Looking at the vowel space area plot, the VSA statistic does not seem to have a significant relationship between morning and evening. Three people had higher VSA in the morning and lower VSA in the evening. The other two have the opposite. And the individual differences are obvious. Xueying's VSA value is significantly higher than everyone else's, and Page's is too low. Therefore we do not think there is a relationship between the time variations between morning and evening with VSA.

![VSA](https://github.com/branaphy/good-morning/assets/144012055/1ab3b691-2c86-48d4-ad8b-dc4c61385734)










## Discussion and Conclusions
Based on the results, we guessed the reasons:
1. Changes in biological clock rhythm and speech characteristics:
VSA changes reflect speech intelligibility in the early morning and evening. A smaller VSA may indicate a more ambiguous or restricted vowel, while a larger VSA may be associated with clearer vowel pronunciation. The vowel space area (VSA) is smaller in the morning, which may be related to the influence of the human body clock rhythm. Morning is the time when the body's body temperature and muscle activity are lowest, which may cause the throat muscles to be tighter, thereby limiting the clarity of vowels and resulting in a smaller VSA. At night, as body temperature rises and muscle activity increases, sound clarity may improve, resulting in a larger VSA.

2. Speech rate and daytime energy difference:
The difference in Speech Rate may be related to the individual's life rhythm and energy level. Slower speech rates in the morning may reflect a lower energy state upon awakening, in which the laryngeal muscles are tense, resulting in slower articulation. In the evening, as the day progresses, the individual may be more active, with a slight increase in speech rate.

In conclusion, XXXXXX

Contribution
All authors of the project participated in the discussion on project goals, Brandi proposed the idea and Page proposed the sentence of the experiment. Everyone participated in the experiment and processed the respective audio data via Praat to get the formant table, vowel space area and speech rate. 
Brandi created a repository in GitHub to store the data and wrote introductions, methods and results sections.
Xueying edited and ran the R-file used to make unified plots of speech rate and Vowel Space Area to better present. 
Yilan wrote the methods, results and wrote the first version of the abstract.
Page and Xueying worked for the slides and Yi, Yilan, Brandi were responsible for presenting it. 
All authors together rewrote the abstract into the final version.
