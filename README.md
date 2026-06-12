# fon
FON: a working set extracted from an entity linking   (EL) dataset and  augmented to support mentions in phonological representation for relieving memory-impaired named entity recognition (NER).

# What is FON?

The working set is formatted as a collection of 3,559 json objects represented as follows:
```json
{
        "mention": "Robbie Coltrane",
        "class": "PERSON",
        "target": "Robbie Coltrane",
        "phonemes": [
            [
                "R",
                "AA1",
                "B",
                "IY0"
            ],
            [
                "K",
                "OW1",
                "L",
                "T",
                "R",
                "AH0",
                "N"
            ]
        ]
        "id": 0
    }
```


# Download FON
The single file to download the entire data is [nephon.json](nephon.json).

# Paper
Details of data construction and performance analyses are available in our companion paper:

- Avi Bleiweiss. *Relieving Memory Impaired Named Entity Recognition using Phonological Similarity of Mentions*. In BShalem, 2026. 

### Citation
     @techreport{bleiweiss-2026-bshalem,
      title = "Relieving Memory Impaired Named Entity Recognition using PhonologicalSimilarity of Mentions",
      author = "Bleiweiss, Avi",
      institution = "BShalem",
      number = "02",
      month =jun,
      year = "2026",
      address = "online",
      note = "In: \url{https://www.aviitshakb.com/publications}"
    }
