# Automatic Spelling Correction (ASC) System
## Masters in DSBA NLP Assignment 

**Groups members:**
- Wong Zheng Qie
- Lim Chun Cheak
- Justin Ng Zheng Xin

This is a Natural Language Processing (NLP) group project that aims to develop an Automatic Spelling Correction (ASC) system for detecting and correcting non-word and real-word errors, based on Astrological-text domain. The detection of non- and real-word errors will be differentiated using different colour highlights (red = non-word error; yellow = real-word error), followed by generating a list of suitable candidate replacement words based on their likelihood ranking. Prior to that, an Astrological book was scrapped for its text, which served as the corpus for the ASC system.

**Candidate techniques utilized:**
1. Spell Check Techniques -> Dictionary Lookup and N-Gram Probability
2. Spelling Correction Techniques -> Levenshtein Edit Distance, N-Gram Probability and Phonetic Algorithm

**Primary python libraries utilized:**
1. "nltk" -> Contained most of the packages and tasks needed to pre-process the text corpus, including tokenization, spelling correction and generating bigram models.
2. "eng_to_ipa" ->  Maps and converts English text into International Phonetic Alphabet (IPA) symbols, which represent individual sounds (phonetics) of a spoken language instead of the written representation of the word. 


Overall design architecture of the ASC system, outlining the entire process flow of the system in sequence.
![image](https://github.com/justin950717/Spell_Checker_and_Correction_System/assets/95216403/286395e2-56cd-4ea6-bbff-ad5d88e4ae09)


ASC system’s GUI design, developed using the Tkinter python library.
![image](https://github.com/justin950717/Spell_Checker_and_Correction_System/assets/95216403/6c036054-8826-4d56-a315-0b69ee3e13b4)


To conclude, the ASC system developed in this project had successfully met all its design requirements, particularly in detecting and correcting non- and real-word errors in the astrological-text domain. I would also like to express my gratitude towards my wonderful groupmates Lim Chun Cheak and Wong Zheng Qie for their dedication and hardwork in making this project successful.


***Note: Below is repository legend for easier naviagation***

Repository Legend:
1. Corpus folder -> Contains Astrological book (pdf) used as the corpus for the system
2. NLP ASC.ipynb -> Python codes for developing ASC system and generating GUI
3. NLP_Corpus cleaning and Dictionary Generation.ipynb -> Python codes for corpus pre-processing & dictionary generation
4. bigram_prob_dict_final.pickle -> Bigram model to store bigram probabilities
5. unigram_ipa.pickle -> IPA model to store the phonetic sound of words in the corpus
6. unigrams_counter_final.pickle -> Counter objects for unigram and bigram that stores the frequency of unigram and bigram in the corpus
7. unique_unigram_list.pickle -> Unigram model to store unique words in the corpus
