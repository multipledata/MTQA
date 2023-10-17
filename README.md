# Multiple-QA
The repo contains the dataset for Multiple-QA. We released two versions of the dataset: a basic version that contains only questions with multiple answers and an expanded version that contains both multiple and single answers. Here are the download addresses for both versions of the dataset:
Multiple-dataset[!https://drive.google.com/file/d/1L59s5zDGph4vvwDrT2PXhWQwBuxJ_rol/view?usp=drive_link]
Multiple-expand[!https://drive.google.com/file/d/1lUT8A83CMH0TrDWe28VNhLNXXr4pvA61/view?usp=drive_link]

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
