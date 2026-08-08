# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS
## DATE : 8/8/26
## REG NO : 212223060095 
# AIM

To test and compare how ChatGPT responds to different types of prompts, especially simple or unstructured prompts and clear, detailed, and refined prompts. The experiment focuses on analyzing the difference in the generated responses based on **quality, accuracy, clarity, and depth**.

---

# AI TOOLS REQUIRED

* ChatGPT
* Web Browser
---

# EXPLANATION

## 1. Define the Two Prompt Types

For this experiment, two different types of prompts are used.

### A. Naive Prompt

A naïve prompt is a simple prompt where the user gives only the basic requirement without providing much context, instructions, examples, or output format.

Example:

> "tell me about cloud computing"

This type of prompt is quick to write, but the AI has to decide what information to include and how to present it.

---

### B. Basic / Refined Prompt

A basic or refined prompt gives the AI more information about what the user actually needs. It can contain the topic, purpose, audience, expected length, important points, and the format in which the answer should be given.

Example:

> "I'm preparing a short explanation about cloud computing for a college presentation. Explain what cloud computing is in simple student-friendly language, mention its main types and give 2 or 3 real-life examples. Keep it around 250 words and don't use very complicated technical terms."

This type of prompt gives the AI a much clearer idea about the expected response.

---

# 2. PREPARE MULTIPLE TEST SCENARIOS

Five different scenarios are selected for testing:

1. Creative Story Generation
2. Factual Question
3. Concept Summarization
4. Recommendation
5. Problem-Solving / Technical Explanation

For every scenario, both a naïve prompt and a refined prompt are given to ChatGPT. The generated responses are then compared.

---

# SCENARIO 1 – CREATIVE STORY GENERATION

## Naive Prompt

> "write a story about a student who finds a robot"

### Expected Observation

The prompt gives only the main idea. ChatGPT has to decide the story length, characters, setting, conflict, and ending by itself.

---

## Refined Prompt

> "I want you to write a short interesting story about a college student who finds a small robot inside an old laboratory. Make the story around 500 words and keep the language simple and natural. The robot should have a secret that the student slowly discovers. Add some suspense in the middle and give the story a meaningful ending. Make it feel like something that could actually happen rather than making it too complicated."

### Expected Observation

The refined prompt gives ChatGPT information about:

* Main character
* Location
* Approximate length
* Story style
* Main conflict
* Ending
* Language level

Therefore, the generated story is expected to be more focused and complete.

---

# SCENARIO 2 – ANSWERING A FACTUAL QUESTION

## Naive Prompt

> "what is blockchain"

### Generated Response – Naïve Prompt

Blockchain is a distributed digital ledger that records transactions across multiple computers. It provides transparency, security, and makes it difficult to alter previously recorded information. Blockchain is commonly associated with cryptocurrencies such as Bitcoin.

---

## Refined Prompt

> "I'm a college student and I need to explain blockchain technology in my class. Explain what blockchain is in very simple words first, then explain how a transaction gets added to a blockchain. Also mention the role of blocks, hashing, and distributed networks. Give me one simple real-life example at the end so I can understand it easily. Keep the explanation around 250 to 300 words."

### Generated Response – Refined Prompt

Blockchain is a method of storing information in a shared digital record that is maintained by many computers instead of one central computer. The information is grouped into blocks, and each block is connected to the previous block using a cryptographic hash.

When a transaction is created, it is checked by the participating computers in the network. Once it is verified, the transaction can be added to a new block. The block is then connected to the existing chain.

Hashing helps protect the information because changing data inside an earlier block would affect its hash and the connection between blocks.

For example, imagine a group of students maintaining a common notebook where everyone has a copy. If one student tries to secretly change an old entry, the other copies will show that the information is different. This is similar to how a distributed blockchain network helps maintain trust.

---

# SCENARIO 3 – SUMMARIZING A CONCEPT

## Naive Prompt

> "summarize machine learning"

### Generated Response – Naïve Prompt

Machine Learning is a branch of Artificial Intelligence that allows computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every task. It is used in applications such as recommendation systems, fraud detection, image recognition, and voice assistants.

---

## Refined Prompt

> "I have to study Machine Learning for my college exam, so summarize the concept for me in an easy way. Start with a one-line definition, then explain how machine learning works in simple steps. After that, briefly explain supervised, unsupervised, and reinforcement learning with one example for each. Finish with 5 common real-world applications. Keep the whole answer short enough that I can revise it quickly."

### Generated Response – Refined Prompt

**Definition:**
Machine Learning is a branch of AI where computers learn patterns from data and use those patterns to make predictions or decisions.

**How it works:**

1. Data is collected.
2. The data is prepared and cleaned.
3. A machine learning model learns patterns from the data.
4. The model is tested using new data.
5. The trained model is used to make predictions.

**Main Types:**

| Type                   | Meaning                            | Example              |
| ---------------------- | ---------------------------------- | -------------------- |
| Supervised Learning    | Learns from labeled data           | Spam email detection |
| Unsupervised Learning  | Finds patterns in unlabeled data   | Customer grouping    |
| Reinforcement Learning | Learns using rewards and penalties | Game-playing AI      |

**Applications:**

* Recommendation systems
* Fraud detection
* Face recognition
* Medical diagnosis
* Voice assistants

---

# SCENARIO 4 – PROVIDING A RECOMMENDATION

## Naive Prompt

> "which programming language should I learn"

### Generated Response – Naïve Prompt

Python is a good programming language for beginners because it has simple syntax and is widely used in areas such as web development, data science, artificial intelligence, and automation. However, the best language depends on your career goals.

---

## Refined Prompt

> "I'm an engineering student and I want to choose one programming language to focus on for the next few months. I already know basic programming concepts but I'm not very strong yet. I'm interested in AI, data science, and software development, so compare Python, Java, and C++ based on learning difficulty, job opportunities, AI/data science usage, performance, and how useful they are for projects. At the end, tell me which one you would recommend for my situation and explain why."

### Generated Response – Refined Prompt

| Factor               | Python    | Java      | C++       |
| -------------------- | --------- | --------- | --------- |
| Learning Difficulty  | Easy      | Moderate  | Difficult |
| AI/Data Science      | Excellent | Moderate  | Moderate  |
| Software Development | Excellent | Excellent | Excellent |
| Performance          | Good      | Very Good | Excellent |
| Beginner Friendly    | Excellent | Good      | Moderate  |

**Recommendation:** Python would be the most suitable choice for this situation because it has a relatively simple syntax and is heavily used in Artificial Intelligence, Machine Learning, and Data Science. It also has a large collection of libraries and frameworks that make project development easier.

---

# SCENARIO 5 – TECHNICAL PROBLEM SOLVING

## Naive Prompt

> "my wifi is slow what should i do"

### Generated Response – Naïve Prompt

If your Wi-Fi is slow, restart your router, check your internet speed, move closer to the router, disconnect unused devices, and contact your internet provider if the problem continues.

---

## Refined Prompt

> "My Wi-Fi has suddenly become very slow compared with its normal speed. I mainly use it for browsing, online classes, and downloading files. I don't know much about networking, so give me a simple step-by-step troubleshooting process that I can follow myself. Start with the easiest checks first and then move to more advanced checks. Also explain what each step is supposed to identify, and tell me when I should contact my internet service provider."

### Generated Response – Refined Prompt

**Step 1 – Check other devices**

Connect another phone or laptop to the same Wi-Fi. If every device is slow, the issue may be with the router or internet connection.

**Step 2 – Restart the router**

Turn off the router, wait for a short period, and turn it on again. This can resolve temporary network problems.

**Step 3 – Check your distance**

Move closer to the router and check whether the speed improves. A weak wireless signal can reduce performance.

**Step 4 – Check connected devices**

Disconnect devices that are not currently being used because multiple active devices can consume bandwidth.

**Step 5 – Test the connection**

Use an internet speed test and compare the result with the speed provided by your internet plan.

**Step 6 – Contact the provider**

If multiple devices remain slow even after basic troubleshooting, contact the Internet Service Provider because the issue may be related to the external connection.

---

# 3. COMPARISON OF NAÏVE AND REFINED PROMPTS

| Scenario          | Naïve Prompt     | Refined Prompt                                     | Quality   | Accuracy  | Depth     |
| ----------------- | ---------------- | -------------------------------------------------- | --------- | --------- | --------- |
| Creative Story    | Basic idea only  | Characters, setting, length and plot given         | Good      | Good      | High      |
| Factual Question  | General question | Audience, topics and example specified             | Very Good | Excellent | High      |
| Summarization     | Topic only       | Format, audience and required points specified     | Excellent | Excellent | High      |
| Recommendation    | General question | User requirements and comparison factors specified | Excellent | Very Good | High      |
| Technical Problem | Basic problem    | Situation and step-by-step requirements given      | Excellent | Excellent | Very High |

---

# 4. RESPONSE QUALITY ANALYSIS

## Quality

The refined prompts generally produced better-organized responses because the AI was given specific instructions about the expected output.

## Accuracy

Both prompt types can produce correct information, especially for simple factual questions. However, refined prompts make it easier to specify exactly which aspects need to be covered.

## Depth

The refined prompts produced deeper responses because they explicitly requested explanations, examples, comparisons, or step-by-step information.

## Clarity

Naïve prompts sometimes resulted in broad answers because the AI had to make assumptions about what the user wanted. Refined prompts reduced these assumptions.

## User Experience

The refined responses were generally more useful because they were closer to the user's actual requirement and required less follow-up prompting.

---

# 5. OBSERVATION

The experiment showed that the way a prompt is written has a direct effect on the response generated by ChatGPT.

Naïve prompts are useful when the user wants a quick and general answer. They are also faster to write and can work well for simple questions.

Refined prompts are more useful when the user has a specific goal. By including context, audience, length, format, examples, and expected output, the generated response becomes more relevant and detailed.

It was also observed that a naïve prompt does not always produce a poor response. For simple questions such as basic definitions, the output can be sufficient. However, for complex tasks such as recommendations, technical explanations, and creative writing, refined prompts provide more control over the final result.

---

# 6. KEY FINDINGS

* Clear prompts generally produce more relevant responses.
* Adding context helps the AI understand the user's actual requirement.
* Specifying the audience improves the language and explanation level.
* Giving an expected format makes the output easier to read.
* Asking for examples can improve understanding of technical concepts.
* Refined prompts are especially useful for complex tasks.
* Naïve prompts are still effective for simple questions.
* Better prompts reduce the need for repeated follow-up questions.

---

# 7. CONCLUSION

This experiment demonstrates that prompt quality has a significant effect on the quality of AI-generated responses. Naïve prompts are short and convenient but often leave important decisions to the AI. Refined prompts provide additional context, instructions, and expected output details, resulting in responses that are generally more accurate, structured, and useful.

The experiment also shows that there is no need to make every prompt extremely complicated. For simple tasks, a short prompt may be enough. For tasks involving creativity, recommendations, technical explanations, or detailed analysis, adding relevant context and clear instructions produces better results.

Therefore, understanding how to convert a simple request into a well-structured prompt is an important skill for getting useful and consistent results from AI tools.

---

# RESULT

Thus, the different naïve and refined prompts were successfully executed using ChatGPT across multiple test scenarios. The generated responses were compared based on quality, accuracy, clarity, and depth. The experiment confirmed that providing clear context and specific instructions generally improves the usefulness and relevance of AI-generated responses.
