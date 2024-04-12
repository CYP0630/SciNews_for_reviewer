human_written_articles.json : 600 True News Articles, 600 False News Articles 
llm_generated_articles.json:  600 True News Articles, 600 False News Articles 
evidence_corpus.json: 7,087 paper's abstract from CORD-19 

Data Sample Structure:
[
 {
    "text": "Body of scientific news report",
    "type": "LLAMA2 Generated/ GPT-3.5 Generated/ Human-Written",
    "evidence": [ 
      "CORD_UID 1",
      "CORD_UID 2",
      "CORD_UID 3"
    ],
    "label": 1 (reliable) / 0 (unreliable)
  },
  
  ...

]



Evidence Corpus Structure:
[
 {
    "CORD_UID": "....",
    "title": "Paper's Title",
    "abstract": "..."
  },
  
  ...
]
