Q1. What is artificial intelligence, and where exactly does machine learning fit?
=> 1. Labelled Concept Map
Artificial Intelligence (AI)
│
├── Rule-Based AI
│   └── Uses predefined rules and logic
│
└── Machine Learning (ML)
    └── Learns patterns from data
        │
        └── Deep Learning (DL)
            └── Uses multilayer neural networks
                │
                └── Generative AI
                    └── Creates new content
                        │
                        └── Large Language Models (LLMs)
                            └── Understand and generate text

2. Five Distinctions in My Own Words

i.   Automation vs. AI: Automation makes tasks run automatically, whereas AI focuses on tasks that require capabilities such as reasoning, recognition, or decision-making.

ii.  AI vs. ML: AI is the broader field of intelligent computer systems, while ML is one approach within AI that learns patterns from data.

iii. Rule-Based Programming vs. ML: Rule-based programming follows rules written by programmers, whereas ML learns patterns from training examples.

iv.  ML vs. Deep Learning: ML includes various learning methods, while deep learning uses neural networks with multiple layers to learn complex patterns.

v.   Generative AI vs. LLMs: Generative AI creates new content of different types, while LLMs are a type of deep-learning model designed primarily to process and generate language.


Example                                                                               Classification                                        Reason

A timer automatically switches                                                          Automation                                         It executes a predefined           off a light after 10 minutes.                                                                                                                                                                                                                                                                                         instruction without needing AI.  
                                                                                                  

A rule-based chatbot answers “Hello”                                                    Rule-Based AI 
with “Welcome!” using a predefined rule.                                                                                                 It responds according to explicitly                                                                                                                                          programmed rules and does not                                                                                                                                                 necessarily learn from data.

An email spam detector learns from labelled spam and                                  Machine Learning                               It learns patterns from training    legitimate emails to classify new messages.                                                                                        data to predict whether an email is spam.                                                                                                                                


Q2. What does it mean to learn a pattern from data?
=>
 Illustrative Dataset and Data Quality

  1. Sample Dataset

    The following dataset is used to predict whether an email is spam.

| Email ID | Number of Links | Contains “Win” | Sender Known | Spam (Target) |

| E1       |               0 | No             | Yes          | No            |
| E2       |               5 | Yes            | No           | Win           |
| E3       |               3 | Yes            | No           | Yes           |
| E4       |               0 | No             | Yes          | No            |
| E5       |               4 | Yes            | No           | Yes           |
| E6       |               1 | No             | Yes          | No            |

 2. Identify Features and Target

- Dataset: The complete table containing six email records.
- Samples/Observations: Each row represents one email.
- Features: Number of links, contains “Win,” and sender known. These are the input variables used to make a prediction.
- Target: Spam. It is the output the model learns to predict.
- Labels: The known answers, “Yes” or "No", in the Spam column.

 3. Two Ways Data Quality Can Affect a Model

i. Missing or incorrect values: If the number of links is missing or recorded incorrectly, the model may learn misleading patterns and make incorrect predictions.

ii. Incorrect labels: If a legitimate email is incorrectly labelled as spam, the model may learn the wrong relationship between features and the target, reducing prediction accuracy.









