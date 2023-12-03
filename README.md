# DailyDialog Dataset

## Overview

- **Name:** DailyDialog: A Manually Labelled Multi-turn Dialogue Dataset
- **Domain:** Multi-turn dialogues reflecting daily communication.

## Download

- **Source:** [DailyDialog Dataset](http://yanran.li/dailydialog.html)
- **Download:** [DailyDialog.zip](http://yanran.li/dailydialog.html)
- **Updated:** Nov 1, 2017

## Collection

- **Collection Method:** Manually is crawled from various websites designed for English learners to practice English dialogue in daily life. The language is human-written and less noisy. 

## Purpose

- **Designed For:** Research and development in dialogue systems, focusing on multi-turn conversations.

## Annotation

- **Type:** Manual labeling of communication intention and emotion information.
- **Extra Annotations:** Poria et al. added extra annotations in 2020.

## Data Format

- **Format:** ZIP file containing dialogue data, likely in CSV or JSON.

## License

- **License:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
  - Not for commercial use; intended for research purposes only.

## Measurments

The DailyDialog training set contains 11,118 multi-turn dialogues. The resulting statistics are given below. 

**Total dialogues length for user/system**
- Total Dialogues	11,118
- Total User Dialogue Length: 506,376
- Total System Dialogue Length: 492,849

**Total Sentences Length for user/system**
- Total User Sentences: 70,126
- Total System Sentences: 68,319
- Total Sentences: 138,445

**Total Turns Length for user/system**
- Total User Turns: 45,533
- Total System Turns: 41,637

**Total Word Length for user/system**
- Total User Words: 614,231
- Total System Words: 600,515
- Total Words: 1,214,746
  
**Mean data Length**

- Average Length User Dialogue: 45.5
- Average Length System Dialogue: 44.3

- Average User Sentences per Dialogue: 6.3
- Average System Sentences per Dialogue: 6.1

- Average User Turns per Dialogue: 4.1
- Average System Turns per Dialogue: 3.7
- Average Speaker Turns Per Dialogue: 7.8

- Average Tokens(words) Per Dialogue: 114.5

**Vocabulary Size**
- Vocabulary Size User: 30,209
- Vocabulary Size System: 29,653

**Standard deviation Dialogue Lengths**

- Std for Dialogue Length User: 8.73
- Std for Dialogue Length System: 9.81

- Std for Sentence Length User: 0.82
- Std for Sentence Length System: 0.87

- Std for Turns Length User: 2.04
- Std for Turns Length System: 2.00

- Std for Word Length User: 9.87
- Std for Word Length System: 11.03

## Impressions
The DailyDialog dataset appears to be a valuable resource due to its focus on natural and human-written language, reflecting the subtle differences of daily communication. This naturalness is beneficial for training models to understand and generate human-like responses.  For instance, in Dialogue 11090, the user discusses ordering business cards, and the system responds appropriately, capturing the typical back-and-forth of a business transaction.

However, the complexity of capturing human conversational dynamics, such as expressions, context-dependent replies, and nuanced emotions (e.g a mixture of joy, surprise, gratitude, or disbelief), may be the reason for the dataset's difficulty for learning purposes. 

The dataset's usability in an actual system is promising, especially for training chatbots or dialogue systems aiming to provide automatic customer services or engaging in open-ended conversations.

Moreover, the dataset seems well-structured for understanding everyday conversations, but its applicability to more complex or specialized domains might be limited.
