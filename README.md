# Morning Mist vs. Evening Clarity: A Comparative Study of Vowel Space Area and Speech Rate
Authors: Brandi H., Page O., Xueying L., Yi L., Yilan W.

This experiment was conducted for a final project in the Speech Sounds course in the first term of the MSc Voice Technology program at the University of Groningen.

## Introduction and Background

Fatigue and its impact on cognitive functions have been subjects of extensive
research over the years. The state of tiredness, often influenced by the circadian
rhythm, can significantly affect an individual’s motor and cognitive abilities,
thereby potentially altering the acoustic properties of speech.

The motivation behind this study stems from the curiosity to explore how
”morning grogginess” may impact speech production, which could have sub-
stantial implications in fields like voice recognition technology, speech pathol-
ogy, and human-computer interaction. The insights garnered from this study
could significantly contribute to real-world applications, notably in the realm of
fatigue/tiredness detection technologies. Understanding how speech parame-
ters may be altered by tiredness creates foundational knowledge for developing
fatigue/tiredness detection systems, particularly for drivers and machine opera-
tors. Such advancements could be pivotal in enhancing road safety by alerting
drivers of fatigue in real-time, thereby reducing the likelihood of fatigue-related
accidents.

Additionally, the findings could fuel the creation of more adaptive voice recog-
nition systems that account for variations in speech due to differing levels of
alertness, such as smart home systems. In a time where voice-activated systems
are becoming increasingly common in our daily lives, tailoring these technolo-
gies to accurately respond to speech, regardless of the user’s state of tiredness,
is inevitable and imperative.

## Methods

The authors hypothesized that there are relevant differences in speech patterns
between fatigued and alert speech. To measure this, each of the authors recorded
themselves speaking the same phrase, twice per day, for three consecutive days.
The recordings were made on each respective author’s cell phone. The first
recording was made immediately upon waking, and the second was made at
20:00. The time immediately after waking was chosen as a reliable control for
tired speech, and 16:00 was chosen as the reliable control for alert speech.

The control phrase was: ”Ah, good morning! I’m going to brew a cup of
coffee.” This phrase was chosen for several reasons:
– The phrase offers a relation to the abstract topic.
– The phrase offers multiple vowel sounds.
– The length of the phrase is brief, yet long enough to accurately measure the
speech rate.

After collecting the recordings, the data was measured to analyze patterns
in two specific areas:
– Vowel space area in vowels a, i, and u.
– Overall speech rate.

The measurement of vowel space area was computed with an R script,
and the measurement of speech rate was calculated using a PRAAT script.

## Results

The data sets for each participant were compiled individually into Vowel Space
Area plots and Speech Rate plots using the mean values across the 3 days. 

![speech_rate](https://github.com/branaphy/good-morning/assets/144012055/c2523695-ba0c-42ac-9b3b-a619600560e0)
![Brandi](https://github.com/branaphy/good-morning/assets/144012055/80a15a88-d2fb-49eb-8414-f3943d66181b)
![Xueying](https://github.com/branaphy/good-morning/assets/144012055/dd3c35b7-af3d-4f65-b2b5-5054436dc6c3)
![Yi](https://github.com/branaphy/good-morning/assets/144012055/7e79a066-a53a-42e0-bafe-a517c44c5fb9)
![Yilan](https://github.com/branaphy/good-morning/assets/144012055/02e3a9aa-ba6c-442b-8516-5e9952999c7b)
![Page](https://github.com/branaphy/good-morning/assets/144012055/b199b099-0eb2-4dba-b4cd-d60c27d276f5)

Looking at the vowel space area plot, the VSA statistic does not seem to have a significant relationship between morning and evening. Three people had higher VSA in the morning and lower VSA in the evening. The other two have the opposite. And the individual differences are obvious. Xueying's VSA value is significantly higher than everyone else's, and Page's is too low. Therefore we do not think there is a relationship between the time variations between morning and evening with VSA.

![VSA](https://github.com/branaphy/good-morning/assets/144012055/1ab3b691-2c86-48d4-ad8b-dc4c61385734)

## Discussion and Conclusions
In conclusion, the hypothesis is partially supported by the results. While there
were no significant differences in vowel space area, there were consistent measur-
able differences in the speech rate from morning to evening. The average speech
rate when tired was significantly lower than the alert speech rate. These find-
ings not only highlight the tangible impact of fatigue on verbal communication
but also hold promising implications for future research, potentially serving as
a foundational reference in the development of fatigue detection systems and in
studies centered around cognitive performance and communication dynamics.

## Contribution
All authors of the project participated in the discussion on project goals, Brandi
proposed the idea and Page proposed the sentence of the experiment. Everyone
participated in the experiment and processed the respective audio data via Praat
to get the formant table, vowel space area and speech rate. Brandi created a
repository in GitHub to store the data and wrote introductions, methods and
results sections. Xueying edited and ran the R-file used to make unified plots of
speech rate and Vowel Space Area to better present. Yilan wrote the methods,
results and wrote the first version of the abstract. Page and Xueying worked for
the slides and Yi, Yilan, Brandi were responsible for presenting it. All authors
together rewrote the abstract into the final version.
