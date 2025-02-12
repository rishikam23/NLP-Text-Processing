# NLP-Text-Processing

This repository contains a Natural Language Processing (NLP) project focused on analyzing stand-up comedy transcripts. The project involves web scraping, text cleaning, and data processing to extract insights, compare linguistic patterns, and structure the collected data.

## Project Overview

This project includes the following tasks:
- **Web Scraping**: Extracting transcripts from `scrapsfromtheloft.com`.
- **Data Cleaning**: Processing text by removing punctuation, stop words, and extraneous characters.
- **Data Organization**: Structuring and storing cleaned transcripts in an accessible format.
- **NLP Processing**: Constructing a document-term matrix and preparing the data for further linguistic analysis.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nlp-comedy-transcripts-analysis.git
   cd nlp-comedy-transcripts-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute the main script:
   ```bash
   python nlp_assignment_2.py
   ```

## Features

- Scrapes transcripts from prominent comedians such as Louis C.K., Dave Chappelle, and Ali Wong.
- Cleans and preprocesses textual data by removing unwanted characters, numbers, and punctuation.
- Structures the processed data for NLP applications.
- Constructs a document-term matrix utilizing `CountVectorizer`.

## Data Sources

The transcripts are sourced from `scrapsfromtheloft.com`, a platform that provides full transcripts of stand-up comedy performances.

## Future Enhancements

- Conduct sentiment analysis on different comedians' performances.
- Implement topic modeling to identify recurring themes within the transcripts.
- Utilize TF-IDF and word embeddings for deeper linguistic insights.

## Contributing

Contributions are encouraged. Please submit a pull request or open an issue to propose enhancements.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for further details.

## Acknowledgment

If this project proves valuable, consider starring the repository on GitHub.

