Q1. AI → ML → Deep Learning → Generative AI → Agents
1. Explain Artificial Intelligence, Machine Learning, Deep Learning, Generative AI, and AI Agent in your own
    words.
-> Artificial Intelligence (AI)
=> AI means making computers perform tasks that normally require human intelligence.

-> Machine Learning (ML)
=> ML is a part of AI where computers learn patterns from data and use them to make predictions or decisions.

-> Deep Learning (DL)
=> DL is a type of ML that uses multi-layer neural networks to learn complex patterns.

-> Generative AI
=> Generative AI creates new content such as text, images, audio, video, or code.

-> AI Agent
=> An AI Agent understands a goal, plans what to do, uses tools when needed, and takes actions to complete the task.

2. Create one simple hierarchy or concept map showing how these ideas relate.
      AI
      │                                     
      └── Machine Learning
          │
          └── Deep Learning
              │
              └── Generative AI



   AI Agent
   │
   ├── Understands a goal
   ├── Plans
   ├── Uses AI models/tools
   └── Takes actions to complete a task

3. Give one everyday example for each term.
=>
 i.   AI → Google Maps suggesting a route.
 ii.  ML → YouTube recommending videos based on your watch history.
 iii. DL → Face Unlock recognizing your face.
 iv.  Generative AI → ChatGPT generating an answer.
 v.   AI Agent → An AI travel assistant planning a trip and using tools to help complete it.

4. Use at least two reliable sources to check your definitions.
=>  IBM: https://www.ibm.com/think/topics/artificial-intelligence
    Google Cloud: https://cloud.google.com/discover/what-are-ai-agents

5. Finish with 3-5 sentences explaining the relationship and the key difference between a generative model and an agentic system.
=> -> AI is the broader field, while Machine Learning and Deep Learning are approaches used to build AI systems, and Generative AI focuses on creating new content.
   -> Generative AI models mainly generate outputs such as text, images, code, or audio based on the input they receive.
   -> An AI agent goes beyond generating content by understanding a goal, planning steps, using tools, and taking actions to complete a task.
   -> In simple words,Generative AI creates content, while an agentic system uses AI capabilities to perform tasks and achieve goals.

Q2. Is Everything That Looks Intelligent Actually AI?
=> 

|No.| System                   | Classification | Short Reasoning 
| 1 | Calculator               | Not AI         | It follows fixed mathematical instructions given by the programmer. 
| 2 | Traffic Light Controller | Not AI         | It changes lights according to predefined timing and rules. 
| 3 | Spam Email Detector      | AI             | It learns patterns from email data and predicts whether a new email is spam. 
| 4 | Face Recognition System  | AI             | It learns patterns from faces and identifies or verifies people from new images. 
| 5 | ChatGPT                  | AI             | It uses a trained model to understand input and generate new responses rather than following only fixed instructions.

Short Reasoning :
1. Calculator:
   A calculator performs calculations according to explicitly programmed mathematical rules. It does not learn from previous calculations.
2. Traffic Light Controller:
   A basic traffic light system follows predefined rules such as changing from green to yellow to red after specific time intervals. It does not learn or make decisions based on learned patterns.
3. Spam Email Detector:
   A spam detector can learn from examples of spam and normal emails. It uses the learned patterns to classify new emails.
4. Face Recognition System:
   A face recognition system learns visual patterns from face data and uses them to recognize or verify a new face.
5. ChatGPT:
   ChatGPT uses a trained AI model to understand the user's input and generate an appropriate response. It is not simply executing one fixed instruction for every possible question.

Final Explanation; 

 i.  The main difference is how the system produces its output. A normal program that follows explicit instructions uses predefined rules written by a programmer for specific situations. 
 ii. An AI system can use learned patterns from data to make predictions, recognize patterns, generate content, or make decisions for inputs it has not seen before. 
 iii.Therefore, following instructions alone does not make a program AI, learning, reasoning, prediction, recognition, or generation based on an AI model is what makes it different.


Q3. What Happens When You Ask an LLM a Question?
=> 1. Annotated Diagram

User Prompt
    ↓
1. Input Processing 
   The model processes the user's question as tokens.
    ↓
2. Context Understanding
   The model uses the available context to determine what kind
   of response is likely to be appropriate.
    ↓
3. Next-Token Prediction
   The model predicts likely next tokens based on patterns
   learned during training.
    ↓
4. Response Generation
   Tokens are generated one after another to form a response.
    ↓
5. Fluent but Possibly Incorrect Answer
   The answer may sound natural and confident,
   but it can still contain false or unsupported information.

2. Short Explanation of Each Stage

-> Input Processing:
   The user's prompt is broken into tokens that the model can process.

-> Context Understanding:
   The model considers the prompt and available context to determine what response fits the situation.

-> Next-Token Prediction:
   The model predicts likely next tokens based on patterns it learned from its training data.

-> Response Generation:
   The predicted tokens are produced one after another until the response is completed.

-> Fluent but Possibly Incorrect Answer:
   Because the model focuses on generating likely language rather than automatically checking every fact against reliable evidence, the response can sound convincing while still being wrong.

3. Sources :

  IBM Research – Debugging LLMs for reliability:
  https://research.ibm.com/blog/debugging-LLMs-for-reliability

  IBM – What are Large Language Models (LLMs)?:
  https://www.ibm.com/think/topics/large-language-models

4. Verification Note :
  -> I verified this explanation using reliable technical sources from IBM Research and IBM.
  -> The sources support the idea that LLMs generate plausible language based on learned patterns, so fluent output does not necessarily guarantee factual accuracy.

Q4. Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?
=>   Prompt                         Model             Response  Summary                     Verified Claim            Evidence                       Result       Lesson
   
   What is the default            ChatGPT           HTTPS uses port 443 by default.       HTTPS uses port 443.      IANA lists HTTPS on port 443.  Correct      The answer was accurate and easy to verify. 
   port number used by HTTPS?    
   
   What is the default            Google Gemini     HTTPS uses port 443 by default.       HTTPS uses port 443.      ANA lists HTTPS on port 443.   Correct      The test did not expose a hallucination because the fact is simple and well established.
   port number used by HTTPS?     

   Overall Lesson :

   AI can produce correct and useful answers, but a confident-sounding response should not automatically be considered reliable. Important factual or technical claims should be checked against an independent, trustworthy source.

   Reference: IANA Service Name and Port Number Registry — https://www.iana.org/assignments/service-names-port-numbers


Q5. AI Assistant vs Search vs Authoritative Reference
=>  # Q5. AI Assistant vs Search vs Authoritative Reference

 Question                                         AI Answer Summary               |                Search Findings                   | Authoritative Reference                                                               | Differences                                                                                                  | Final Conclusion 

 What is the default port number used by HTTPS? | HTTPS uses port 443 by default. | Web search also showed that HTTPS uses port 443  | IANA Service Name and Transport Protocol Port Number Registry lists HTTPS on port 443 | There was no difference in the final answer. AI and search gave the same result as the authoritative source. | The answer is correct and verified. For important technical decisions, the authoritative source provides the strongest evidence.

-> Final Conclusion :

  -> AI assistants are useful for getting quick explanations, while web search helps find relevant information and sources. 
  -> An authoritative or primary source provides the strongest evidence for verifying an important technical claim. In this experiment, all three approaches agreed that HTTPS uses port 443.

Q6. What Is an AI Agent?
=> 1. Comparison Table :
      Concept                     Simple Explanation
      
      LLM Application             A software application that uses an LLM to perform a specific task. 
      RAG System                  A system that retrieves relevant information from external sources and gives it to the LLM to generate a better answer.
      Tool-Using Assistant        An AI assistant that can use external tools such as search, calculators, databases, or APIs.
      AI Agent                    An AI system that understands a goal, plans steps, uses tools, makes decisions, and takes actions to complete the goal.


Simple AI Agent Architecture :

            User Request
                  ↓
            AI Agent / LLM
                  ↓
          Understand & Decide
                  ↓
           Need a Tool?
             ↙       ↘
           Yes        No
            ↓          ↓
        Tool Call   Final Response
            ↓
      External Tool
            ↓
        Tool Result
            ↓
       Agent / LLM
            ↓
     Decision / Next Step
            ↓
       Final Response
            ↓
           User


Example of an Agentic Workflow

AI Travel Planning Agent

User request:

"Plan a 3-day trip to Goa within ₹20,000."

The agent can:

i.  Understand the user's travel goal.
ii. Search for transport options.
iii.Search for hotels.
iv. Check and compare prices.
v.  Create a 3-day itinerary.
vi. Provide the final travel plan.

Why it is agentic:
The system does not simply answer the question. It breaks the goal into steps, uses tools to gather information, evaluates the results, and produces a final plan.

Verification :
 The explanation was verified against IBM's resources on AI agents and agentic workflows. IBM describes AI agents as systems that can plan actions, use tools or APIs, evaluate results, and take actions to achieve a goal.

Verification conclusion :
 The travel-planning example is consistent with the concept of an AI agent because it involves goal understanding, planning, tool use, decision-making, and completing a task.

Sources :
  IBM – AI Agent Planning
  IBM – Agentic Workflows

Q7. Where Should Humans Still Make the Decision?
=>

| Situation                    | Possible Failure                                                             | Required Verification                                                             | Who/What Approves the Result? 

| Hiring decisions             | AI may misunderstand qualifications or introduce bias.                       | Check resume, skills, experience, interview results, and job requirements.        | Hiring manager / HR 
| Medical decisions            | AI may provide an incorrect or incomplete diagnosis or treatment suggestion. | Check medical records, test results, and clinical guidelines.                     | Qualified doctor 
| Financial decisions          | AI may use incorrect or outdated information and cause financial loss.       | Check current financial data, risks, and supporting information.                  | Financial professional / decision-maker 
| Legal decisions              | AI may misunderstand laws or provide incorrect legal information.            | Check current laws, official documents, and relevant legal information.           | Qualified lawyer 
| Important business decisions | AI may make recommendations based on inaccurate data or assumptions.         | Check business data, financial reports, market research, and supporting evidence. | Responsible manager / decision-maker 

 Simple Rule :
   Use AI to assist and recommend, but verify important information and keep humans responsible for the final decision.


Q8. Find AI Around You
=> 
| System                      | AI Involvement                                  | Task Type                    | Evidence / Source                                                                                                           | Conclusion 

|   Google Maps               | Yes — uses machine learning                     | Prediction + Recommendation  | Google explains that Maps uses ML to predict traffic and determine routes.                                                  | AI/ML verified 
|   YouTube Recommendations   | Yes — uses machine learning                     | Recommendation               | YouTube explains that its recommendation system uses ML models and signals such as watch time, clicks, likes, and dislikes. | AI/ML verified 
|   Face Unlock / Face ID     | Yes — uses machine learning and neural networks | Recognition + Classification | Apple explains that Face ID uses machine learning and neural networks for facial matching.                                  | AI/ML verified 
|   Voice Assistant           | Depends on the specific assistant               | Recognition + Generation     | The exact AI/ML implementation varies between assistants.                                                                   | Not enough public evidence to conclude for a generic voice assistant.
|   Gmail Spam Filter         | Yes — uses machine learning                     | Classification               | Google explains that Gmail uses machine learning to identify and filter spam.                                               | AI/ML verified 

 Rule-Based Comparison :

Example: Gmail Spam Filter
         A basic rule-based system could mark emails as spam when they contain certain words, come from a blocked sender, or contain suspicious links.
        This could work for simple spam, but modern spam changes frequently. Machine learning can identify more complex patterns and adapt better to new types of spam.

Conclusion: Rule-based systems can produce similar behavior in simple cases, but ML is more flexible for complex and changing spam patterns.

Sources :
 Google  – Google Maps and machine learning
 YouTube – Recommendation System
 Apple   – Face ID and machine learning
 Google  – Gmail and machine learning


Q9. Prediction, Classification, and Generation
=>

1. Classification Table

| Example                                                       | Classification |                         Reason                                     |
| A. Predicting house prices**                                  | Prediction     | Predicts a numerical value, such as the expected price of a house. |
| B. Detecting whether an image contains a cat**                | Classification | Assigns the image to a category such as "cat" or "no cat."         |
| C. Writing an email with a short instruction**                | Generation     | Creates new text based on the given instruction.                   |
| D. Predicting whether a customer will cancel a subscription** | Prediction     | Predicts a future outcome based on customer information.           |
| E. Summarising a research paper**                             | Generation     | Generates a shorter version of the original content.               |
| F. Identifying whether a transaction is fraudulent**          | Classification | Classifies the transaction as fraudulent or legitimate.            |
| G. Generating an image from a text description**              | Generation     | Creates a new image based on the text description.                 |
| H. Predicting the next word/token in a sentence**             | Prediction     | Predicts the most likely next token based on previous tokens.      |

 2. Why Is Next-Token Prediction Fundamental?

Next-token prediction is fundamental to modern language models because they generate text one token at a time. At each step, the model predicts the most likely next token based on the prompt and the tokens that have already been generated.

For example:

text
Prompt
  ↓
Predict next token
  ↓
Predict next token
  ↓
Predict next token
  ↓
Continue until response is complete


The same basic process can produce different applications:

- Writing → generates text token by token.
- Summarization → generates a shorter summary token by token.
- Coding → generates code token by token.
- Question answering** → generates the answer token by token.


Q10. Design Your Personal AI Verification Protocol

  1. Seven-Step AI Verification Protocol

   Step 1: Define the Problem

    Clearly identify the problem, requirements, inputs, constraints, and expected output.

Why: Ensures that the AI is solving the correct problem.
Catches: Misunderstood or incomplete requirements.

 Step 2: Inspect Assumptions

Check the assumptions, conditions, and reasoning used by the AI.

Why: AI may make assumptions that are not stated or are incorrect.
Catches: Hidden assumptions and logical errors.

 Step 3: Check Evidence and Sources
  Verify important technical claims using reliable documentation, standards, official sources, or trusted references.

Why: AI-generated information may be outdated or unsupported.
Catches: Hallucinations, incorrect facts, and outdated information.

 Step 4: Test the Result
  Run the code, calculations, simulations, or other appropriate tests.

Why: A result that looks correct may still fail when actually tested.
Catches: Bugs, incorrect outputs, runtime errors, and unexpected behavior.

 Step 5: Check Risks and Edge Cases
  Test unusual inputs and consider security, safety, and other possible failure conditions.

  Why: A solution may work in normal situations but fail in unusual cases.
  Catches: Security issues, unsafe behavior, and edge-case failures.

 Step 6: Review the Complete Result

Review the verified result and compare it with the original requirements.

Why: Ensures that all parts of the task have been correctly completed.
Catches: Remaining errors, missing requirements, or unnecessary content.

 Step 7: Accept, Revise, or Reject

 Make the final decision:

- Accept – The result is correct and sufficiently verified.
- Revise—Errors or weaknesses were found but can be corrected.
- Reject – The result is unreliable or fundamentally incorrect.

Why: Keeps the human responsible for the final decision.
Catches: Blind acceptance of AI-generated output.

 2. Worked Example: AI-Generated Python Code

 Task :
Ask an AI assistant to write Python code that calculates the average of numbers in a list.

 Applying the Protocol

Step 1 – Define the Problem:
The program should accept a list of numbers and correctly calculate the average.

Step 2 – Inspect Assumptions:
Check whether the AI assumes that the list is non-empty and whether it handles decimal numbers correctly.

Step 3 – Check Evidence and Sources:
Verify that the Python functions and syntax used are supported by reliable Python documentation.

Step 4 – Test the Result:
Run the code using normal numbers, decimal numbers, a single value, and an empty list.

Step 5 – Check Risks and Edge Cases:
Check what happens when the list is empty or contains unexpected input.

Step 6 – Review the Complete Result:
Confirm that the code is understandable, meets the original requirement, and produces the expected output.

Step 7 – Accept, Revise, or Reject:
If the code works correctly, accept it. If a small error is found, revise it. If the approach is fundamentally wrong, reject it.

 Simple Protocol Flow
   text
Define Problem
      ↓
Inspect Assumptions
      ↓
Check Evidence / Sources
      ↓
Test Result
      ↓
Check Risks / Edge Cases
      ↓
Review Result
      ↓
Accept / Revise / Reject


 3. Future Improvement
  At the end of the 16-week program, I will revisit this protocol and improve it based on what I have learned, including new verification methods, common AI errors, and    lessons from practical examples.

 Final Rule
 Use AI to assist, but verify its assumptions, evidence, and results before accepting its output for real engineering work.Revise—Errors











