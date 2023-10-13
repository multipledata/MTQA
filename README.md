# Multiple-QA
The repo contains the dataset for Multiple-QA. The 'Multi-answer' directory contains only the multi-answer dataset, while the 'all' directory contains the full dataset, which includes both multi-answer and single-answer datasets.
A sample of the data is as follows:

```JSON
{
    "idx": "/wiki/Armitage_Robinson#P39#12",
    "question": "Which two positions did Armitage Robinson take between Dec 1929 and Jun 1930?",
    "targets": [
        {
            "answer": "Dean of Wells",
            "from": 48,
            "to": 61
        },
        {
            "answer": "Lord High Almoner",
            "from": 13,
            "to": 30
        }
    ],
    "answer_num": 2,
    "context": "Armitage Robinson Joseph Armitage Robinson...",
    "paragraphs": [
        "Joseph Armitage Robinson...",
        "during which he was also a prebendary ...",
    ]
}
```
