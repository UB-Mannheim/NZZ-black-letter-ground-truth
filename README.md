# Ground truth for Neue Zürcher Zeitung black letter period

## About the original data set
The original [NZZ Black Letter Ground Truth](https://github.com/impresso/NZZ-black-letter-ground-truth) was published in 2019 by Phillip Ströbel and Simon Clematide under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.en). The data set contains 167 randomly chosen frontpages of the Neue Zürcher Zeitung (NZZ) that were published between 1780 and 1947. The ground truth was produced using [Transkribus](https://transkribus.eu/Transkribus) and it's internal ABBYY FineReader Server 11 with additional manual corrections. 

For more information about the original data set, the ground truth production, transcription guidelines and known issues, see the corresponding [wiki page](https://github.com/UB-Mannheim/NZZ-black-letter-ground-truth/wiki/Ground-Truth-v1.1-%E2%80%93-v1.0).


## NZZ Black Letter Ground Truth 2.0.0 (July 2023)
A revision of the data set was carried out by [Mannheim University Library](https://www.bib.uni-mannheim.de/en/)
from March 2023 to June 2023 using [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus).
All transcriptions are provided as `PAGE XML` in the `data` folder.

The revision includes: 
1. Layout correction of text regions, text lines and baselines.
2. Region labeling ("header", "headings", "paragraphs"). 
3. Correction and enhancement of transcriptions according to [OCR-D Ground Truth Guidelines Level 2](https://ocr-d.de/en/gt-guidelines/trans/level_2_2.html).

### Transcription guidelines:
The transcription rules are based on the [OCR-D Ground Truth Guidelines Level 2](https://ocr-d.de/en/gt-guidelines/trans/level_2_2.html) with some exceptions (see below):

1) **Special characters**:
    - Long s (ſ)
    - R rotunda (ꝛ)
    - Combining latin small letter e ( ͤ)
    - Asterisk (*)
    
2) **Additional characters** transcribed true to original (contrary to OCR-D Level 2):
    - Double oblique hyphen (⸗)
    - Em dash (—) instead of En dash (–)

### Funding
This revision is part of the [OCR-D project](https://ocr-d.de/en/) and predominantly funded by the [German Research Foundation (DFG)](https://www.dfg.de/foerderung/info_wissenschaft/2020/info_wissenschaft_20_15/index.html).

# Links
- [[Original data set] Ground truth for Neue Zürcher Zeitung black letter period](https://github.com/impresso/NZZ-black-letter-ground-truth) 
- [University Library Mannheim](https://www.bib.uni-mannheim.de/en/)
