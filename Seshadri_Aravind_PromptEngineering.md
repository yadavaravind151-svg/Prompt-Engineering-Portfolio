## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

**Goal:** Explain Artificial Intelligence (AI) to a 10-year-old child.

#### Initial Prompt (V1)

> Explain artificial intelligence.

#### LLM Output (V1)

> Artificial Intelligence (AI) is the simulation of human intelligence in machines. It enables computers to perform tasks such as learning, problem-solving, and decision-making.

#### Refined Prompt (V2)

> Explain artificial intelligence to a 10-year-old child using simple language and a real-life example. Avoid technical jargon.

#### LLM Output (V2)

> Artificial Intelligence is when computers learn how to do things that usually require human thinking. For example, when a video app suggests videos you might like, AI helps decide which videos to recommend based on what you have watched before.

#### Final Prompt (V3)

> You are a friendly elementary school teacher. Explain Artificial Intelligence (AI) to a 10-year-old child. Use simple words, include a fun analogy, provide one real-life example, keep the explanation under 150 words, and end with an encouraging question.

#### Final LLM Output (V3)

> Imagine you have a robot friend who learns from experience just like you learn in school. At first, the robot does not know much, but every time it sees examples, it becomes smarter. Artificial Intelligence, or AI, works in a similar way. It helps computers learn patterns and make helpful decisions. For example, when your phone suggests the next word while you are typing, AI is helping behind the scenes. AI is like a super-fast student that can learn from millions of examples. What exciting thing would you teach your own AI robot to do?

---

### 1.1 Scenario B: Professional Email

**Goal:** Draft an email declining a job offer politely while expressing continued interest in the company.

#### Initial Prompt (V1)

> Write an email declining a job offer but saying I like the company.

#### LLM Output (V1)

> Dear Hiring Manager,
>
> Thank you for the offer. I cannot accept the position at this time. I appreciate the opportunity and hope we can stay in touch.
>
> Regards,
>
> Seshadri Aravind

#### Refined Prompt (V2)

> Write a professional email declining a Data Analyst job offer because I accepted another opportunity that better matches my current goals. Thank the company and maintain a positive relationship.

#### LLM Output (V2)

> Dear Hiring Manager,
>
> Thank you very much for offering me the Data Analyst position. After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals.
>
> I sincerely appreciate the time and effort invested throughout the hiring process. I have great respect for your organization and hope our paths cross again in the future.
>
> Best regards,
>
> Seshadri Aravind

#### Final Prompt (V3)

> You are an experienced corporate communications professional. Write a polished and professional email declining a Data Analyst job offer from InnovateTech. Mention that I accepted another opportunity, express sincere gratitude, compliment the company’s growth and culture, and indicate my interest in staying connected through LinkedIn for future opportunities.

#### Final LLM Output (V3)

> Subject: Thank You for the Opportunity
>
> Dear InnovateTech Hiring Team,
>
> Thank you sincerely for offering me the Data Analyst position. I am grateful for the time and consideration you invested throughout the recruitment process.
>
> After careful consideration, I have decided to accept another opportunity that aligns more closely with my immediate career goals. Therefore, I must respectfully decline your offer.
>
> I have been particularly impressed by InnovateTech’s recent growth and collaborative culture. I truly appreciate the positive experience I had throughout the interview process.
>
> I would be delighted to stay connected through LinkedIn and hope there may be opportunities to collaborate in the future.
>
> Thank you again for your understanding and support.
>
> Warm regards,
>
> Seshadri Aravind

---

### 1.1 Scenario C: Creative Content

**Goal:** Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt (V1)

> Give me a tagline for an eco-friendly water bottle.

#### LLM Output (V1)

> Save the planet, drink water.

#### Refined Prompt (V2)

> Act as a professional marketing copywriter. Create five catchy taglines for a premium eco-friendly reusable water bottle brand targeted at Gen Z customers. Focus on sustainability and style.

#### LLM Output (V2)

> 1. Hydrate with Purpose.
>
> 2. Style Meets Sustainability.
>
> 3. Refill. Refresh. Repeat.
>
> 4. Drink Smart. Live Green.
>
> 5. Carry Change Everywhere.

#### Final Prompt (V3)

> You are an award-winning advertising director. Create one powerful marketing tagline for a luxury eco-friendly water bottle brand named “Aura.” The tagline must be fewer than six words and combine sustainability with premium lifestyle branding.

#### Final LLM Output (V3)

> Aura: Pure Luxury, Zero Footprint.

---

### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt                                                 | What Changed?                             | Why This Improved the Output                             |
| ------- | ------------------------------------------------------ | ----------------------------------------- | -------------------------------------------------------- |
| V1      | Explain artificial intelligence.                       | Initial prompt.                           | Produced a generic technical definition.                 |
| V2      | Added age group and example requirement.               | Simplified language and added context.    | Made the explanation easier for children to understand.  |
| V3      | Added teacher role, analogy, word limit, and question. | Defined audience and communication style. | Produced a more engaging and child-friendly explanation. |

#### Scenario B: Professional Email

| Version | Prompt                                                                                   | What Changed?                                      | Why This Improved the Output                                        |
| ------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------- |
| V1      | Write an email declining a job offer.                                                    | Initial prompt.                                    | Produced a short generic email.                                     |
| V2      | Added reason for declining and gratitude.                                                | Included context and professionalism.              | Generated a more realistic business email.                          |
| V3      | Added expert role, company details, LinkedIn networking, and praise for company culture. | Increased specificity and strategic communication. | Produced a polished professional email suitable for real-world use. |

#### Scenario C: Creative Content

| Version | Prompt                                                                                    | What Changed?                      | Why This Improved the Output                   |
| ------- | ----------------------------------------------------------------------------------------- | ---------------------------------- | ---------------------------------------------- |
| V1      | Give me a tagline for an eco-friendly water bottle.                                       | Initial prompt.                    | Produced a basic slogan.                       |
| V2      | Added marketing role, target audience, and multiple outputs.                              | Improved creativity and relevance. | Generated stronger and more targeted taglines. |
| V3      | Added brand name, strict word limit, luxury positioning, and sustainability requirements. | Added strong branding constraints. | Produced a memorable, market-ready tagline.    |

---

### 1.3 Role and Context Analysis

Role assignment significantly improved the quality of responses throughout the prompt refinement process. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler vocabulary, analogies, and an engaging tone appropriate for children. In Scenario B, assigning the role of a corporate communications professional resulted in a more polished and professional email structure.

Context setting was equally important. By providing details such as the reason for declining the job offer and the desire to maintain future connections, the generated email became more realistic and personalized. Similarly, specifying the target audience and brand positioning in Scenario C helped create a tagline that aligned closely with marketing objectives. These examples demonstrate how role and context reduce ambiguity and improve output quality.




## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Task Chosen:** Explaining a technical concept (Neural Networks)

**Base Prompt:** Explain what a neural network is in simple terms.

**Note:** Since Gemini Free Tier does not provide direct temperature controls, temperature behavior was simulated by modifying prompt instructions according to the assignment guidelines.

---

#### Low Temperature (0.2)

**Prompt Used:** Explain what a neural network is in simple terms. Be precise and consistent.

**Output:**

> A neural network is a method in artificial intelligence that teaches computers to process data in a way inspired by the human brain. It uses interconnected nodes or neurons in a layered structure, resembling a biological network. These networks can learn from input data to recognize patterns, classify information, and solve complex problems consistently.

---

#### Medium Temperature (0.7)

**Prompt Used:** Explain what a neural network is in simple terms.

**Output:**

> A neural network is a type of machine learning software that mimics how the human brain works. It is built out of layers of interconnected points called nodes. When you feed data into the network, it passes information through these layers to spot deep patterns. This structure allows the AI to do smart things like recognize your face in photos or translate languages automatically.

---

#### High Temperature (1.2)

**Prompt Used:** Explain what a neural network is in simple terms. Be creative and explore diverse ideas.

**Output:**

> Think of a neural network as an entire stadium filled with millions of fans doing "the wave" in perfect harmony. Each fan passes a small clue to the next person. By the time the message reaches the other side of the stadium, a massive mathematical picture comes to life. It is nature's complex web replicated in computer code, dreaming up patterns from chaotic numbers.

---

### Comparison Table

| Temperature      | Style               | Creativity | Accuracy  | Characteristics                                                                |
| :--------------- | :------------------ | :--------- | :-------- | :----------------------------------------------------------------------------- |
| **0.2 (Low)**    | Formal and factual  | Low        | Very High | Highly predictable, literal, direct, and structured.                           |
| **0.7 (Medium)** | Balanced and clear  | Moderate   | High      | Highly readable, using accessible real-world examples.                         |
| **1.2 (High)**   | Abstract and poetic | High       | Moderate  | Relies heavily on loose analogies and risks drifting from technical realities. |

---

### 2.2 Analysis & Recommendations

Low temperature settings are ideal when factual accuracy, structural consistency, and precision are important. Two specific use cases include generating software code and creating corporate financial reports. High temperature settings are most useful when creativity and originality are required, such as brainstorming marketing campaigns or writing fictional stories. For this task, the medium temperature setting (0.7) performed best because it balanced technical accuracy with readability. The low temperature output was highly precise but somewhat rigid, while the high temperature output was imaginative but less technically grounded. Therefore, the medium setting provided the most effective explanation for a general audience.




## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Selected Problem:** Option B – Multi-Step Reasoning

**Problem:** A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

#### Without Chain-of-Thought

**Prompt:**

> A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.

**LLM Output:**

> 172 employees.

---

#### With Chain-of-Thought

**Prompt:**

> A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step.

**LLM Output:**

> Total employees = 150
>
> Engineering employees = 60% of 150 = 90
>
> Sales employees = 25% of 150 = 37.5
>
> Additional engineering hires = 20% of 90 = 18
>
> Additional sales hires = 10% of 37.5 = 3.75
>
> Total new hires = 18 + 3.75 = 21.75
>
> Total employees after hiring = 150 + 21.75 = 171.75
>
> Rounded to the nearest whole employee, the company will have **172 employees**.

---

#### Comparison

The output without Chain-of-Thought provided only the final answer, making it difficult to understand how the result was calculated. The Chain-of-Thought approach broke the problem into smaller steps and showed the reasoning process used to reach the answer. This improves transparency and makes it easier to verify calculations. One limitation is that the model treated employees as fractional values, which is mathematically correct but unrealistic in a real-world business setting.

---

### 3.2 Few-Shot Prompting

#### Step 1: Zero-Shot Attempt

**Prompt:**

> Classify the sentiment of each review as Positive, Negative, or Neutral.

**Results:**

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 2: Few-Shot Attempt

**Prompt:**

> Review: "This product exceeded my expectations!"
> Sentiment: Positive
>
> Review: "Completely broke after one week of use."
> Sentiment: Negative
>
> Review: "It's fine, does what it says on the box."
> Sentiment: Neutral
>
> Review: "Amazing quality and excellent value."
> Sentiment: Positive
>
> Review: "Customer support never responded."
> Sentiment: Negative
>
> Now classify the sentiment of the following reviews as Positive, Negative, or Neutral.

**Results:**

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

Few-shot prompting is most useful when a task requires a specific output format, classification style, or domain-specific interpretation. By providing examples, the model learns the expected pattern and produces more consistent results. Although both approaches produced identical results in this experiment, few-shot prompting generally improves reliability when dealing with more complex or ambiguous inputs.


