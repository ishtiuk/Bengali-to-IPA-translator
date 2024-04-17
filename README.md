# Bengali to IPA Translator

Finalist at ITverse2023 Datathon, developed an accurate Bengali to International Phonetic Alphabet (IPA) translation model, facilitating linguistic analysis and language education. [Kaggle Notebook](https://www.kaggle.com/code/ishtiukahammed/bengali-to-ipa-translation/notebook)
### [Kaggle Notebook](https://www.kaggle.com/code/ishtiukahammed/bengali-to-ipa-translation/notebook) 
...............

## Executive Summary
This project focuses on the development of a sophisticated Bengali to International Phonetic Alphabet (IPA) translation model. The primary objective is to establish a seamless bridge between the intricate Bengali language and the standardized IPA notation, catering to various linguistic, educational, and research applications.

## Methodology

### Data Preprocessing
The project commenced with a meticulous data preprocessing phase, meticulously curated to ensure the integrity of the dataset. Key steps included:
- **URL Removal:** Rigorous extraction of embedded URLs to maintain data purity.
- **Bengali Numeral Conversion:** Implementation of a transformation mechanism to convert Bengali numerals into word equivalents, enhancing both readability and phonetic accuracy.
- **Elimination of English Alphanumeric Words:** Systematic removal of extraneous English alphanumeric content to minimize interference.

These efforts culminated in the creation of a pristine dataset, laying the groundwork for subsequent model development.

### Model Selection
The project embarked on a journey of model exploration to achieve optimal translation performance:
1. **LSTM Sequence-to-Sequence Model:** Initial implementation of raw LSTM sequence-to-sequence models, augmented by advanced tokenization techniques such as SentencePiece and Byte-Pair Encoding (BPE). However, the effectiveness of this approach was constrained by dataset scale limitations.
2. **mT5-small:** Emerged as a promising alternative, exhibiting commendable translation accuracy despite longer training times.
3. **mT5-base:** The project culminated with the adoption of the mT5-base model, overcoming training speed challenges and elevating translation quality to a superior standard.

## The Cleaner Class
A pivotal contribution to the project was the introduction of the Cleaner class—a sophisticated tool meticulously designed to streamline the data preprocessing pipeline. This class ensures strict adherence of Bengali text to IPA standards, thereby enhancing data consistency and model performance.

## Conclusion
This project represents a successful endeavor in facilitating Bengali to IPA translation, effectively bridging the gap between two distinct linguistic realms. By enabling accurate phonetic transcription, it significantly expands the horizons of linguistic analysis, language education, and phonetic research. Anticipated to serve as a cornerstone for further advancements, this initiative promises a deeper exploration of language nuances and a continued commitment to linguistic excellence.
