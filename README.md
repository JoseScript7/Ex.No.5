# Ex.No.5 – Comparative Analysis of Different Prompting Patterns  
### DATE: 28.11.2025
### REGISTER NUMBER: 212224040269


<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/9d38359c-5582-41ec-8988-33691b242028" />




## Explanation
Prompt engineering plays a critical role in determining how effectively an AI model interprets and responds to user input.  
To analyze this effect, two prompt types were defined:

### Naïve Prompt  
Unstructured, brief, and lacking context.  
These prompts provide minimal guidance and allow the model to infer the requirements on its own.

### Basic Prompt  
Structured, detailed, and context-rich.  
These prompts specify instructions, constraints, and expectations clearly.

Multiple scenarios were created where each task was executed twice:  
once using a naïve prompt and once using a basic prompt.  
The responses were then evaluated using a rubric covering quality, accuracy, and depth.



# Test Scenarios and Comparative Prompts



## Scenario 1: Creative Story Generation

### Naïve Prompt  
"Write a story."

### Response (Naïve)  
A short and generic narrative with minimal structure.  
Characters and plot elements are vague and underdeveloped.

### Basic Prompt  
"Write a 150-word story about an engineer who discovers an unexpected malfunction in an AI system operating a future smart city. Include a defined beginning, a central conflict, and a concluding resolution."

### Response (Basic)  
A structured narrative with a clear storyline, identifiable characters, and a coherent plot.  
The conflict is well framed, and the resolution is logically consistent with the setup.



## Scenario 2: Factual Question Answering

### Naïve Prompt  
"Explain renewable energy."

### Response (Naïve)  
A short one-line explanation with no examples or elaboration.

### Basic Prompt  
"Explain renewable energy in 4–5 sentences. Include the main sources, the principle behind their sustainability, and one practical real-world application."

### Response (Basic)  
A well-articulated explanation covering solar, wind, and hydro energy, supported by a real-world example and clear conceptual detail.



## Scenario 3: Summarization

### Naïve Prompt  
"Summarize machine learning."

### Response (Naïve)  
A very general overview lacking structure and depth.

### Basic Prompt  
"Summarize the concept of machine learning in five bullet points, addressing definition, types, applications, advantages, and limitations."

### Response (Basic)  
A concise, structured summary that covers all major components of machine learning, offering significantly improved clarity and completeness.



## Scenario 4: Recommendations

### Naïve Prompt  
"Give some study tips."

### Response (Naïve)  
A set of basic suggestions without prioritization or context.

### Basic Prompt  
"Provide six practical study strategies for university students managing both coursework and project deadlines. Present them as short, actionable bullet points."

### Response (Basic)  
Clearly organized strategies including scheduling, prioritization, review cycles, and focused study sessions.  
The recommendations are relevant, specific, and aligned with higher education challenges.



# Evaluation of Response Quality

| Scenario                          | Naïve Prompt Output               | Basic Prompt Output                | Quality | Accuracy | Depth | Score (10) |
|----------------------------------|-----------------------------------|------------------------------------|---------|----------|-------|-------------|
| Creative Story Generation        | Generic and unstructured           | Coherent and engaging              | 2/5     | 3/5      | 4/5   | 7.3         |
| Factual Explanation              | Brief and incomplete               | Detailed and correct               | 3/5     | 5/5      | 4/5   | 8.6         |
| Summarization                    | Vague                              | Structured and comprehensive        | 2/5     | 4/5      | 4/5   | 8.0         |
| Recommendations                  | Basic suggestions                  | Contextual and actionable           | 3/5     | 4/5      | 4/5   | 8.0         |



# Analysis
The results demonstrate a consistent trend:  
the more structured and detailed the prompt, the more precise and meaningful the AI-generated response becomes.

### Observations  
1. Naïve prompts often result in generic or incomplete outputs, particularly in tasks that require structure, reasoning, or specificity.  
2. Basic prompts lead to significantly higher clarity and depth by providing context and constraints.  
3. The creative and advisory scenarios show the largest improvement under basic prompting due to the need for guided direction.  
4. Summarization results show that the AI responds more effectively when the required format is explicitly stated.

### Key Insight  
Prompt clarity directly controls the model’s ability to produce accurate and high-quality outputs.  
While naïve prompts may work for simple factual tasks, they are not suitable for detailed or structured outputs.



<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/0ffdbe65-1bb4-4731-b945-343238102e0c" />



## Result
The prompt for the above said problem was executed successfully, and the comparative analysis was completed.

