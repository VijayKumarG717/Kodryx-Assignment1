ASSIGNMENT-1
1Q)
i.  System prompt:
    it is a boss level command that is given by developers to create or set rules and boundaries to decide how a model should answer the user.
    example:
    knowledge cutoff: 2025 Nov
    current date: 13 Nov 2025
    Role:
    assume u are a film director.
    tone: 
    confident, caring ,friendly, tolerant ,patient, veteran 
    output format:
    short and simple
    Knowledge Boundaries or rule:
    Do not answer questions that are asked anything outside the film domain
ii. User prompt:
    it is a prompt given by user to obtain information or solutions within the limits and boundaries of system prompt.
    example:
    help me fix the errors in this given code
    tell abt api and api key

2Q)
    i.  LLM: it stands for large language model. its an Ai system which is trained on large data and perfrom certain tasks on the pretrained data.
    ii. API: it stands for Application programming interface. it acts a media for communication btw frontend and backend (like sending get requests or fetch requests).
    iii.inference: it is synonym for run 
    iv. Workflow(in context of n8n): it is an automated sequence of connected nodes that perform certain tasks step-by-step.

3Q)
    <img width="1918" height="1027" alt="image" src="https://github.com/user-attachments/assets/5888d270-dde9-4594-9bc7-1e7ee71122da" />
    i have dragged 3 nodes into the canvas (trigger manually, edit feild, and http request) and entered a message: 'hello' in message section
    and configured http request node.

4Q)
    Role-based prompting means giving a prompt to the Ai model to pretend as user desired role and giving answers accordingly.
    example:
    i.Act as an interviewer and ask me React questions.
    ii.Act as a senior web developer and review my code.
    iii.Act as a career coach and rewrite my resume.

5Q)
    ollama run gemma2:2b 
    ollama run deepseek-r1:1.5b

6Q)
  import ollama 
  response = ollama.chat(model="gemma2:2b",messages=[{"role": "user", "content": "Hello! Explain me abt llms?"})]
  print(response["message"]["content"])

7Q)
  The system role is an instruction that sets the AI's behavior, tone and rules before the conversation starts.
  It’s powerful because it shapes all future responses consistently, giving you predictable and controlled output.

8Q)
  <img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/7dc3418e-313c-462c-9e7b-e65cb6f336fa" />
  use case:
  we cane take test input and send to a test api

9Q)
  Act as a helpful assistant: first give step-by-step instructions that solve my request. 
  Keep steps concise and practical.

10)
  Llms answers or solutions might be wrong sometimes coz they might not understand the context or tasks we have given.
