human_written example : 5 True with correct predictions, 5 False with correct predictions
llm_generated example:  5 True with correct predictions, 5 False with correct predictions

Sample Structure:
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
    "abstractive": abstractive summary 
    "selected_sentence": selected several sentences from abstracts.
    "prediction": support / refute 
    "reason": LLM generated explanations.
  },
  
  ...
]

