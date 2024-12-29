# Kannada News Article Classification

This project focuses on classifying Kannada news articles into various categories based on their titles. The model utilizes natural language processing (NLP) techniques to process and analyze text in the Kannada language. 

## Overview

Classifying Kannada news articles helps users quickly identify the nature of content without reading the entire article. This project demonstrates how titles can be used to categorize articles into predefined categories such as politics, sports, entertainment, technology, etc.

### Key Objectives:
- Process and analyze Kannada text.
- Train a machine learning model for multi-class classification.
- Achieve high accuracy and generalization across categories.

## Features

- **Text Preprocessing**: Tokenization, stemming, and stop-word removal tailored for Kannada.
- **Multilingual Support**: Handles Unicode Kannada text efficiently.
- **Custom Categories**: Allows for customizable classification categories.

## Dataset

The dataset used for training and testing consists of Kannada news titles labeled with their corresponding categories.

### Data Sources:
- Kannada news portals
- Open-source datasets
- Manually labeled data for underrepresented categories

### Format:
| Title                             | Category       |
|-----------------------------------|----------------|
| "ರಾಜಕೀಯ ಕ್ಷೇತ್ರದಲ್ಲಿ ಹೊಸ ಚರ್ಚೆಗಳು" | Politics       |
| "ಕ್ರಿಕೆಟ್ ತಂಡದ ಐತಿಹಾಸಿಕ ಜಯ"       | Sports         |
| "Samsung Galaxy M30s: ಲಭ್ಯವಾಗಲಿದೆ ಶಕ್ತಿಶಾಲಿ ಸ್ಮ..."       | Tech         |
| "ಯುವೆಂಟಸ್ ತಂಡ ಸೇರಿದ ಕ್ರಿಸ್ಟಿಯಾನೊ ರೊನಾಲ್ಡೊ\nಯುವೆ..."       | Sports         |
| "ತಮ್ಮದು ಒಪ್ಪಿತ ʼಸಂಬಂಧʼ ಎಂದು ಹೇಳಿದ ನಟ\n  12-05-2...	" | Entertainment       |

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/kannada-news-classifier.git
   cd kannada-news-classifier
