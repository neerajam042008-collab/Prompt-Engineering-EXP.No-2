EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
ZERO SHOT PROMPTING: Question: explain the concept of machine learning CHATGPT: Concept of Machine Learning Machine Learning (ML) is a branch of Artificial Intelligence that allows computers to learn from data and improve their performance without being explicitly programmed. Instead of writing detailed instructions for every task, machine learning systems analyze data, find patterns, and make predictions or decisions automatically.

Simple Definition Machine learning is a technique that enables computers to learn from past data and use that knowledge to make predictions or decisions about new data.

How Machine Learning Works Machine learning generally follows these steps:

Data Collection – Gather relevant data from different sources.
Data Training – The algorithm learns patterns from the training data.
Model Building – A model is created based on the learned patterns.
Prediction/Decision – The model uses new data to make predictions or decisions.
Improvement – The system improves its accuracy as more data is provided.
Types of Machine Learning

Supervised Learning o The model learns from labeled data (data with correct answers). o Example: Email spam detection.
Unsupervised Learning o The model finds hidden patterns in unlabeled data. o Example: Customer grouping in marketing.
Reinforcement Learning o The model learns through trial and error using rewards and penalties. o Example: Game-playing AI systems.
Applications of Machine Learning Machine learning is used in many real-world applications such as: • Recommendation systems (Netflix, YouTube suggestions) • Speech recognition (voice assistants) • Image recognition (face detection in photos) • Fraud detection in banking • Self-driving cars

Advantages • Can analyze large amounts of data quickly. • Improves performance over time with more data. • Helps in automation and intelligent decision making.

In short: Machine learning enables computers to learn from data, identify patterns, and make predictions without being directly programmed for every task. COPILOT: Machine learning is a branch of Artificial Intelligence (AI) where computers learn patterns from data and improve performance on tasks without being explicitly programmed. It is widely used in applications like speech recognition, fraud detection, recommendation systems, and autonomous vehicles.

🔑 Core Concept of Machine Learning • Definition: Machine learning (ML) is about building algorithms that can learn from data and make predictions or decisions without needing explicit instructions for every scenario. • Goal: To enable systems to adapt and improve automatically as they are exposed to more data. • Foundation: ML relies on statistics, probability, and optimization to identify patterns and relationships in datasets.

📂 Types of Machine Learning Type How It Works Examples Supervised Learning Learns from labeled data (input-output pairs). The model predicts outcomes for new, unseen data. Spam email detection, predicting house prices Unsupervised Learning Works with unlabeled data, finding hidden structures or groupings. Customer segmentation, market basket analysis Reinforcement Learning Learns by trial and error, receiving rewards or penalties for actions. Game-playing AI, robotics navigation

⚙️ Key Components • Data: The fuel for ML. Quality and quantity of data directly affect performance. • Features: Measurable properties or inputs used by the model. • Model: The mathematical representation that learns from data. • Training: The process of feeding data to the model to adjust parameters. • Evaluation: Testing the model on unseen data to measure accuracy and reliability.

📌 Real-World Applications • Healthcare: Disease prediction, medical image analysis. • Finance: Fraud detection, credit scoring. • Retail: Personalized recommendations, demand forecasting. • Transportation: Self-driving cars, traffic prediction. • Education: Adaptive learning platforms, plagiarism detection.

⚠️ Challenges & Considerations • Data Quality: Poor or biased data leads to inaccurate models. • Overfitting: When a model memorizes training data instead of generalizing. • Interpretability: Complex models (like deep learning) can be hard to explain. • Ethics: Bias, fairness, and privacy concerns must be addressed.

🧠 Quick Analogy Think of ML like teaching a child: • Supervised Learning: Showing examples with answers (e.g., “This is a cat, this is a dog”). • Unsupervised Learning: Letting the child group things on their own. • Reinforcement Learning: Rewarding or penalizing behavior until they learn the best strategy. GEMINI Think of Machine Learning (ML) as the shift from giving a computer a recipe to giving it a tongue and a kitchen. In traditional programming, you write specific "if-then" rules. In Machine Learning, you provide data and the desired outcome, and the computer figures out the patterns to bridge the gap itself. It "learns" from experience, much like a person does.

How It Works: The Core Process At its heart, ML is about finding a mathematical function that maps inputs to outputs. The process generally follows these steps:

Data Collection: Gathering examples (e.g., thousands of photos of cats and dogs).
Feature Extraction: Identifying what matters (e.g., ear shape, whisker length).
Training: The model makes a guess, checks how wrong it was (the "loss"), and adjusts its internal parameters to be more accurate next time.
Evaluation: Testing the model on data it has never seen before to ensure it actually learned and didn't just memorize the answers.
The Three Main Types of Learning Machine learning isn't a single tool; it’s a toolbox with different approaches depending on the goal: • Supervised Learning: The "Teacher" method. You give the AI labeled data (e.g., "This image is a cat"). It learns to associate specific features with that label. • Unsupervised Learning: The "Pattern Finder." You give the AI raw data with no labels. It looks for hidden structures or clusters (e.g., grouping customers by similar shopping habits). • Reinforcement Learning: The "Trial and Error" method. An agent performs actions in an environment and receives rewards or penalties (e.g., an AI learning to play chess or drive a car).

Why It Matters Now While the math behind ML has existed for decades, we’ve hit a "perfect storm" that made it explode recently: • Big Data: We finally have enough digital info to feed these hungry algorithms. • Computing Power: Modern GPUs (Graphics Processing Units) can handle the massive number of simultaneous calculations required. • Better Algorithms: We've refined the "Neural Network" models that mimic how human brains process information.

Real-World Examples • Recommendation Engines: Netflix or Spotify suggesting your next favorite binge. • Computer Vision: Your phone unlocking with your face. • Natural Language Processing: Translation apps and chatbots understanding the nuances of human speech. A quick myth-bust: Machine Learning isn't "magic" or "sentience." It’s high-speed statistics and optimization. It doesn't "understand" what a cat is in a philosophical sense; it just knows which pixel patterns are 99% likely to be associated with the label "cat."

Few-Shot Prompt QUESTION: Sentence: Close the door. → Command Sentence: What is your name? → Question Sentence: The sun rises in the east. → ?

CHATGPT Answer: Statement Explanation: • Close the door. → Command (gives an order) • What is your name? → Question (asks something) • The sun rises in the east. → Statement (gives information or a fact) So the correct completion is: Sentence: The sun rises in the east. → Statement COPILOT The sentence “The sun rises in the east.” is a Statement (or Declarative Sentence). 📝 Breakdown of the examples: • Close the door. → Command (Imperative Sentence) • What is your name? → Question (Interrogative Sentence) • The sun rises in the east. → Statement (Declarative Sentence) ✨ Quick Guide to Sentence Types Sentence Type Function Close the door. Command (Imperative) Gives an instruction What is your name? Question (Interrogative) Asks for information The sun rises in the east. Statement (Declarative) Provides information GEMINI Sentence: The sun rises in the east. → Statement (or Declarative)

Why this fits: In linguistics, sentences are categorized by their purpose or mood: • Commands (Imperative): Give an order or request. • Questions (Interrogative): Seek information. • Statements (Declarative): Relay information or state a fact. Would you like me to generate a few more examples for you to classify, or perhaps explain the fourth type, the Exclamatory sentence? Chain-of-Thought Prompt Question: Anita is 5 years older than Rahul. Rahul is 10 years old. How old is Anita? Explain the steps.

CHATGPT Step-by-step solution:

Rahul’s age = 10 years.
Anita is 5 years older than Rahul.
So we add 5 to Rahul’s age. Calculation: 10 + 5 = 15 ✅ Final Answer: Anita is 15 years old.
GEMINI To find out how old Anita is, we can follow these simple steps:

Identify Rahul's current age: From the information given, we know Rahul is 10 years old.
Identify the age difference: The problem states that Anita is 5 years older than Rahul.
Perform the addition: To find Anita's age, add the age difference to Rahul's age. 
10
+
5
=
15
 Conclusion: Anita is 15 years old.
COPILOT Let’s solve this step by step:

🧮 Problem: • Anita is 5 years older than Rahul. • Rahul is 10 years old. • We need to find Anita’s age.

✨ Steps:

Identify Rahul’s age: Rahul = 10 years.
Relationship given: Anita = Rahul’s age + 5 years.
Substitute Rahul’s age: Anita = 10 + 5.
Calculate: Anita = 15 years.
✅ Final Answer: Anita is 15 years old.

Role-Based Prompt QUESTION: Act as a software engineer and explain how a computer program works.

CHATGPT Alright, I’ll answer from a software engineer’s perspective.

As a software engineer, I’d explain that a computer program is a set of instructions written in a programming language that tells a computer what tasks to perform and how to perform them.

Writing the Program First, a programmer writes instructions using a programming language like C (programming language), Python (programming language), or Java (programming language). These instructions define the logic of the task. Example (simple idea): • Take input from the user • Process the input • Display the result
Compilation or Interpretation Computers cannot directly understand human-readable code. So the code must be translated into machine language (binary: 0s and 1s). This happens using tools such as: • Compiler – converts the whole program at once. • Interpreter – converts and runs the program line by line.
Execution by the Computer Once translated, the computer’s processor executes the instructions step by step. The processor performs operations such as: • Calculations • Data storage • Decision making (if/else conditions) • Repeating tasks (loops)
Input → Process → Output Most programs follow this basic model: Input: Data given by the user Process: The program performs calculations or logic Output: The result is shown to the user Example: If you enter 5 + 3 in a calculator app: • Input: 5 and 3 • Process: Addition operation • Output: 8
✅ In simple terms: A computer program works by taking input, processing it through coded instructions, and producing an output, all executed by the computer’s processor.

GEMINI Think of a computer program as a highly detailed instruction manual written for a very fast, but very literal, assistant. Computers don't actually "understand" concepts; they just execute a sequence of tiny electrical shifts at incredible speeds. Here is the engineering breakdown of how we get from a human idea to a running application.

The Source Code (Human-Readable) As engineers, we write code in "High-Level Languages" like Python, Java, or C++. These languages use English-like words and logic. At this stage, the program is just a text file. • Example: print("Hello World") tells the computer to display text.
The Translation (Compilation or Interpretation) The computer’s processor (CPU) cannot read your text file. It only understands Binary (1s and 0s), which represent "on" or "off" states for billions of tiny switches called transistors. To bridge this gap, we use a translator: • Compiler: Translates the entire program into a "machine code" file all at once (like translating a whole book before reading it). • Interpreter: Translates and executes the code line-by-line (like a live speech translator).
Loading into Memory (RAM) When you "run" the program, the Operating System (OS) copies that machine code from your slow permanent storage (Hard Drive/SSD) into the RAM (Random Access Memory). RAM is much faster, allowing the CPU to access instructions instantly.
The Fetch-Decode-Execute Cycle This is the heartbeat of a program. The CPU performs this cycle billions of times per second:
Fetch: The CPU retrieves the next instruction from RAM.
Decode: The Control Unit figures out what the 1s and 0s actually want (e.g., "Add these two numbers" or "Move this data").
Execute: The ALU (Arithmetic Logic Unit) performs the actual math or logic.
Getty Images

Input and Output (I/O) Most programs aren't just doing math in a vacuum; they interact with the world. • Input: The program waits for signals from your keyboard, mouse, or a sensor. • Output: The program sends signals to your monitor (to light up specific pixels) or your speakers (to create sound waves). Summary: The Layered Stack If you look at it as a sandwich, it looks like this: • Top: User Interface (What you see). • Middle: Application Logic (The code we wrote). • Bottom: Hardware (The physical silicon chips moving electrons). A Pro-Tip: Most "bugs" in software happen because the computer did exactly what the programmer told it to do, rather than what the programmer intended it to do. Computers are perfectly obedient, but they have zero intuition.
COPILOT As a software engineer, let me break down how a computer program works in a way that connects both the technical process and the logic behind it:

🖥️ What is a Computer Program? A computer program is essentially a set of instructions written in a programming language that tells the computer what tasks to perform. Think of it as a recipe: the program specifies the steps, and the computer executes them precisely.

⚙️ How It Works – Step by Step

Source Code o The program starts as human-readable code (e.g., written in C, Python, or Java). o Example: o print("Hello, World!")
Compilation / Interpretation o Compiled languages (like C, C++) are translated into machine code by a compiler before execution. o Interpreted languages (like Python, JavaScript) are executed line by line by an interpreter.
Machine Code Execution o The CPU only understands binary (0s and 1s). o The compiler/interpreter converts your code into instructions the CPU can process.
Memory Management o Programs use RAM to store variables, data structures, and temporary results. o The operating system allocates and frees memory as needed.
Input/Output (I/O) o Programs interact with the outside world through input (keyboard, sensors, files) and output (screen, speakers, network).
Control Flow o Logic structures (loops, conditionals, functions) determine how the program reacts to different situations. o Example: o if (temperature > 100) { o printf("Warning: Overheating!\n"); o }
Execution Cycle o The CPU fetches an instruction → decodes it → executes it → stores the result. o This cycle repeats millions of times per second.
🔄 Analogy Imagine a factory: • The source code is the blueprint. • The compiler/interpreter is the engineer translating the blueprint into machine instructions. • The CPU is the worker executing tasks. • Memory is the warehouse storing materials. • I/O devices are the loading docks where goods enter and leave.

📌 Connection to Your Coursework Since you’re currently studying Prompt Engineering and Zero-shot prompting, here’s the link: • A prompt is like source code for an AI model. • The model (like GPT) interprets the prompt, much like an interpreter runs a program. • The output is the program’s result — in this case, the AI’s response. • Just as a program’s behavior depends on its instructions, an AI’s behavior depends on the structure and clarity of the prompt.

Here’s a clean table like the one in your image, with the same ratings and a calculated result. AI Tools Comparison Table Goal / Criteria ChatGPT Microsoft Copilot Google Gemini Accuracy 5 4 4 Coherence 4 5 4 Simplicity 4 4 5 Speed 4 4 4 User Experience 5 3 4 Total Score 22 20 21 Average Rating 4.4 4.0 4.2

RESULT:
The experiment was conducted to evaluate and compare different AI tools such as ChatGPT, Google Gemini, and Microsoft Copilot based on several performance criteria including accuracy, coherence, simplicity, speed, and user experience. From the observations, it was found that each AI tool demonstrated different strengths in the evaluation process. ChatGPT showed higher performance in terms of accuracy and user experience, producing responses that were detailed, well-structured, and easy for users to understand. The interaction with ChatGPT was smooth and the responses were generally more consistent. Gemini also performed well in several aspects. It showed good simplicity and balanced performance across most parameters. The responses were generally clear and easy to understand, although in some cases the explanations were slightly shorter compared to ChatGPT. Copilot demonstrated strong coherence, meaning that the responses were logically organized and structured. However, the user experience score was slightly lower compared to the other tools, which affected its overall evaluation score. In terms of speed, all three AI tools performed similarly and generated responses quickly without noticeable delay. This indicates that the platforms are efficient in processing prompts and delivering outputs. Overall, based on the ratings across all criteria, ChatGPT achieved the highest total score, followed by Gemini and then Copilot. This shows that ChatGPT provides slightly better overall performance in terms of accuracy, clarity, and user experience, while Gemini and Copilot also provide reliable and effective results. Therefore, the comparison highlights that although all three AI platforms are capable and useful, ChatGPT demonstrates the most balanced and effective performance among the evaluated tools based on the given criteria.
