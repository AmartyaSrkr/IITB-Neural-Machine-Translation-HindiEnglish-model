# IITB-Neural-Machine-Translation-HindiEnglish-model
This repository contains the code for training a Neural Machine Translation model aimed at translating Hindi to English using the IIT Bombay Hindi-English Parallel Corpus (v2.0).
This project utilizes the use of the following tools for training the model:
1. OpenNMT-py
2. BLEU Machine Translation evaluation (for accuracy detection)
3. Pytorch for checking and utilizing GPU capabilities
4. shell-based commands (mostly for display of the "filtered dataset", "subworded" etc)

## Data Source 
The dataset implemented for this project is the **IIT Bombay English-Hindi Parallel Corpus** (v2.0), containing sentence pair and their corresponding translations 
https://object.pouta.csc.fi/OPUS-IITB/v2.0/moses/en-hi.txt.zip

## Corpus Information 

- **Corpus Name**: IIT Bombay English-Hindi Parallel Corpus
- **Version**: v2.0
- **Release Date**: November 18, 2022
- **License**: [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)
- **Source Website**: [OPUS - IITB v2.0](http://opus.nlpl.eu/IITB-v2.0.php)

This corpus has been utilized in various workshops, including the Workshop on Asian Language Translation Shared Task in 2016 and 2017, for tasks like Hindi-to-English and English-to-Hindi translation, and as a pivot language for Hindi-to-Japanese and Japanese-to-Hindi translation.

### Citation

Anoop Kunchukuttan
Pratik Mehta 
Pushpak Bhattacharyya
[The IIT Bombay English-Hindi Parallel Corpus](https://www.cfilt.iitb.ac.in/~moses/iitb_en_hi_parallel/lrec2018_iitbparallel.pdf). Language Resources and Evaluation Conference, 2018.

## License

The IIT Bombay English-Hindi Parallel Corpus is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). 

