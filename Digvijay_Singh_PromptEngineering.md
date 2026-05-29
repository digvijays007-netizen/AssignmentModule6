# Prompt Engineering Portfolio

Name: Digvijay Singh  
Date: May 29, 2026  
LLM Used: ChatGPT-5.5 Thinking

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

**Goal:** Explain neural networks to a 10-year-old.

#### V1 Initial Prompt

**Prompt:**
> Explain neural networks to a 10-year-old.

**LLM Output:**
> A neural network is a computer system that learns from examples, kind of like how your brain learns. If you show it many pictures of cats and dogs, it can start to notice patterns, such as pointy ears, whiskers, or nose shapes. After seeing enough examples, it can make guesses about new pictures it has never seen before. It is called a neural network because it is inspired by how brain cells, called neurons, connect and pass information.

#### V2 Refined Prompt

**Prompt:**
> You are an expert elementary school teacher. Explain neural networks to a 10-year-old using a simple everyday example and avoid technical jargon.

**LLM Output:**
> Imagine you are learning to recognize different fruits. At first, you may mix up apples and peaches. But after seeing many examples, you notice that apples are usually shiny and firm, while peaches are fuzzy. A neural network learns in a similar way. People give it lots of examples, and it slowly learns patterns so it can make better guesses next time. It does not understand like a person, but it can become very good at spotting patterns.

#### V3 Final Prompt

**Prompt:**
> You are an expert elementary school teacher explaining artificial intelligence during a school science day. Explain neural networks to a curious 10-year-old in 2 short paragraphs. Use one analogy, define any difficult words, and end with one simple real-world example.

**Final LLM Output:**
> A neural network is a computer program that learns from examples. It is inspired by the brain, but it is much simpler than a real brain. Think of it like a student learning to identify animals from flashcards. At first, the student may guess wrong, but after seeing many examples, they start noticing patterns like ears, tails, shapes, and colors.
>
> In a neural network, tiny parts called “neurons” help pass information along. A neuron is like a small decision helper. When many of these helpers work together, the computer can make a smart guess. For example, a phone camera can use a neural network to recognize faces in photos.

### 1.1 Scenario B: Professional Email

**Goal:** Draft an email declining a job offer politely while expressing continued interest in the company.

#### V1 Initial Prompt

**Prompt:**
> Write an email declining a job offer politely.

**LLM Output:**
> Subject: Thank You for the Offer
>
> Dear Hiring Manager,
>
> Thank you very much for offering me the position. I appreciate the time and effort you and your team spent during the interview process. After careful consideration, I have decided to decline the offer.
>
> I am grateful for the opportunity and wish you and the company continued success.
>
> Sincerely,  
> Digvijay Singh

#### V2 Refined Prompt

**Prompt:**
> You are a professional career advisor. Write a polite email declining a job offer while keeping the relationship positive and expressing continued interest in future opportunities with the company.

**LLM Output:**
> Subject: Thank You for the Opportunity
>
> Dear [Hiring Manager Name],
>
> Thank you very much for offering me the [Job Title] position at [Company Name]. I truly appreciate the time you and the team invested throughout the interview process and the opportunity to learn more about the company.
>
> After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I have great respect for your organization and the people I met during the process.
>
> I would be grateful to stay in touch and hope there may be an opportunity to work together in the future.
>
> Kind regards,  
> Digvijay Singh

#### V3 Final Prompt

**Prompt:**
> You are a professional career advisor helping me write a respectful email. Context: I received a job offer from a company I like, but I have decided not to accept because another opportunity better matches my current goals. Draft a concise email that politely declines the offer, thanks the hiring team, gives a brief reason without too much detail, and expresses continued interest in future opportunities. Use a warm, professional tone and sign the email with my name, Digvijay Singh.

**Final LLM Output:**
> Subject: Thank You for the Offer
>
> Dear [Hiring Manager Name],
>
> Thank you very much for offering me the [Job Title] position at [Company Name]. I sincerely appreciate the time you and the team spent speaking with me and sharing more about the role and the organization.
>
> After careful consideration, I have decided to decline the offer, as I have chosen to pursue another opportunity that more closely aligns with my current goals. This was a difficult decision because I have a very positive impression of your company and the team.
>
> I would be happy to stay in touch and hope there may be an opportunity for us to work together in the future. Thank you again for your time, consideration, and support throughout the process.
>
> Kind regards,  
> Digvijay Singh

### 1.1 Scenario C: Creative Content

**Goal:** Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### V1 Initial Prompt

**Prompt:**
> Create a tagline for an eco-friendly water bottle brand.

**LLM Output:**
> Sip Sustainably.

#### V2 Refined Prompt

**Prompt:**
> You are a creative marketing copywriter. Create 5 short taglines for a new eco-friendly reusable water bottle brand. The tone should be modern, positive, and memorable.

**LLM Output:**
> 1. Refill the Future.  
> 2. Drink Clean. Live Green.  
> 3. Hydration with a Purpose.  
> 4. Better Bottles. Better Planet.  
> 5. Sip Smart. Waste Less.

#### V3 Final Prompt

**Prompt:**
> You are a creative marketing copywriter for a startup launching a stylish, reusable, eco-friendly water bottle made for students and young professionals. Create 8 original taglines under 7 words each. The taglines should feel fresh, optimistic, and environmentally responsible without sounding too formal. After the list, choose the best tagline and briefly explain why it works.

**Final LLM Output:**
> 1. Refill Today. Restore Tomorrow.  
> 2. Sip Better. Waste Less.  
> 3. Hydrate with the Planet in Mind.  
> 4. Your Bottle. Less Plastic.  
> 5. Drink Fresh. Live Light.  
> 6. Reuse Looks Good on You.  
> 7. Carry Water, Not Waste.  
> 8. Small Sips. Big Change.
>
> **Best tagline:** Refill Today. Restore Tomorrow.  
> This tagline works well because it is short, memorable, and connects a simple daily action with a positive environmental impact. It also sounds optimistic and modern, which fits a brand aimed at students and young professionals.

### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Explain neural networks to a 10-year-old. | N/A | N/A |
| V2 | You are an expert elementary school teacher. Explain neural networks to a 10-year-old using a simple everyday example and avoid technical jargon. | Added role assignment, audience, example requirement, and jargon restriction. | The output became easier for a child to understand and used a more relatable explanation. |
| V3 | You are an expert elementary school teacher explaining artificial intelligence during a school science day. Explain neural networks to a curious 10-year-old in 2 short paragraphs. Use one analogy, define any difficult words, and end with one simple real-world example. | Added context, format limit, definition requirement, and real-world example. | The final response was more organized, age-appropriate, and practical. |

#### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Write an email declining a job offer politely. | N/A | N/A |
| V2 | You are a professional career advisor. Write a polite email declining a job offer while keeping the relationship positive and expressing continued interest in future opportunities with the company. | Added role and relationship-preserving goal. | The response became more professional and included future interest. |
| V3 | You are a professional career advisor helping me write a respectful email. Context: I received a job offer from a company I like, but I have decided not to accept because another opportunity better matches my current goals. Draft a concise email that politely declines the offer, thanks the hiring team, gives a brief reason without too much detail, and expresses continued interest in future opportunities. Use a warm, professional tone and sign the email with my name, Digvijay Singh. | Added personal context, tone, reason, length expectation, and signature. | The final email sounded realistic, diplomatic, and tailored to the situation. |

#### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Create a tagline for an eco-friendly water bottle brand. | N/A | N/A |
| V2 | You are a creative marketing copywriter. Create 5 short taglines for a new eco-friendly reusable water bottle brand. The tone should be modern, positive, and memorable. | Added role, number of options, brand type, and tone. | The output gave multiple usable options and better matched marketing needs. |
| V3 | You are a creative marketing copywriter for a startup launching a stylish, reusable, eco-friendly water bottle made for students and young professionals. Create 8 original taglines under 7 words each. The taglines should feel fresh, optimistic, and environmentally responsible without sounding too formal. After the list, choose the best tagline and briefly explain why it works. | Added target audience, style, word limit, originality, and selection requirement. | The output became more targeted, creative, and easier to evaluate. |

### 1.3 Role and Context Analysis

Role assignment improved the outputs by telling the LLM what perspective to use. For example, asking it to act as an elementary school teacher made the neural network explanation simpler and more age-appropriate. Context also improved the professional email because the LLM knew why the offer was being declined and could write a more realistic message. In the marketing example, adding the startup context and target audience helped the LLM produce taglines that felt more suitable for students and young professionals.

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Chosen task:** Creating a short story opening.

**Base Prompt:**
> Write a 2-3 sentence opening for a short story about a student who discovers a hidden door in the school library.

Because ChatGPT does not directly expose temperature controls in the normal chat interface, I simulated temperature differences through prompt instructions.

#### Low Temperature Simulation

**Temperature Value:** 0.2  
**Prompt Used:**
> Write a 2-3 sentence opening for a short story about a student who discovers a hidden door in the school library. Be precise, consistent, and straightforward.

**LLM Output:**
> Maya stayed late in the school library to finish her history project. While searching the back shelf for an old reference book, she noticed a narrow wooden door hidden behind a row of dusty encyclopedias. The door had no label, only a small brass handle that looked strangely new.

#### Medium Temperature Simulation

**Temperature Value:** 0.7  
**Prompt Used:**
> Write a 2-3 sentence opening for a short story about a student who discovers a hidden door in the school library.

**LLM Output:**
> The school library was always quiet after the final bell, but that afternoon, Leo heard a soft tapping from behind the oldest bookshelf. When he pulled away a cracked dictionary, he found a small blue door carved into the wall, glowing faintly around the edges. He knew at once that homework would have to wait.

#### High Temperature Simulation

**Temperature Value:** 1.2  
**Prompt Used:**
> Write a 2-3 sentence opening for a short story about a student who discovers a hidden door in the school library. Be creative, unexpected, and explore diverse ideas.

**LLM Output:**
> Every Thursday at exactly 3:17, the school library sneezed. Priya was the only student who noticed, and when a cloud of golden dust burst from the mythology section, it revealed a tiny green door with a sign that read: “Late returns may alter history.”

#### Comparison Table

| Temperature | Key Characteristics | Strengths | Weaknesses |
|---|---|---|---|
| Low 0.2 | Clear, realistic, direct | Easy to understand and consistent | Less imaginative or surprising |
| Medium 0.7 | Balanced creativity and structure | Engaging while still coherent | Slightly more dramatic but not highly original |
| High 1.2 | Very creative and unusual | Memorable, playful, and original | Less predictable and potentially less realistic |

### 2.2 Analysis & Recommendations

Low temperature is best when accuracy, consistency, and clarity are more important than creativity. I would use low temperature for writing technical documentation or summarizing legal, academic, or business information. High temperature is useful when originality matters, such as brainstorming story ideas or creating advertising slogans. For the short story opening task, the high temperature result worked best because the goal was creative writing and the unusual details made the opening more memorable. However, if the assignment required a realistic story, the medium temperature output would be the safest choice.

## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Selected Problem:** Option B: Multi-Step Reasoning

**Problem:** A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### Without Chain-of-Thought

**Prompt:**
> A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.

**LLM Output:**
> 171 employees.

#### With Chain-of-Thought

**Prompt:**
> A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step and show the reasoning clearly.

**LLM Output:**
> First, calculate the number of engineers: 60% of 150 = 90 engineers.  
> Next, calculate the number of sales employees: 25% of 150 = 37.5 sales employees. Since employee counts should be whole numbers, this creates a small issue because the percentage produces a fraction. Using the percentage directly, a 10% increase in sales is 3.75 employees.  
> Engineering hiring: 20% of 90 = 18 new engineers.  
> Sales hiring: 10% of 37.5 = 3.75 new sales employees.  
> Total after hiring = 150 + 18 + 3.75 = 171.75. Since companies cannot hire 0.75 of an employee, the practical total would likely be 172 employees if rounded to the nearest whole person.
>
> **Final answer: approximately 172 employees.**

#### Comparison

The answer-only prompt produced a simple final number, but it did not show how the result was calculated. The chain-of-thought prompt revealed an important issue: 25% of 150 equals 37.5, which is not a whole number of employees. This helped identify that the problem contains an unrealistic fractional employee count and that rounding may be needed. One limitation is that chain-of-thought can make the response longer and may introduce extra assumptions, such as rounding, that should be stated clearly.

### 3.2 Few-Shot Prompting

#### Step 1: Zero-Shot Attempt

**Prompt:**
> Classify the sentiment of each customer review as Positive, Negative, or Neutral.
>
> 1. "The product arrived damaged and customer service was unhelpful."  
> 2. "Works as expected, nothing special but does the job."  
> 3. "Absolutely love this! Best purchase I've made all year!"  
> 4. "The quality is okay but slightly overpriced for what you get."  
> 5. "Terrible experience, would not recommend to anyone."

**LLM Output:**
> 1. Negative  
> 2. Neutral  
> 3. Positive  
> 4. Negative  
> 5. Negative

#### Step 2: Few-Shot Attempt

**Prompt:**
> You are a sentiment classifier. Classify each customer review as Positive, Negative, or Neutral. Use the examples below to guide your labels.
>
> Example 1:  
> Review: "This product exceeded my expectations!"  
> Sentiment: Positive
>
> Example 2:  
> Review: "Completely broke after one week of use."  
> Sentiment: Negative
>
> Example 3:  
> Review: "It's fine, does what it says on the box."  
> Sentiment: Neutral
>
> Example 4:  
> Review: "The design is acceptable, but I expected better quality for the price."  
> Sentiment: Neutral
>
> Now classify these reviews:
>
> 1. "The product arrived damaged and customer service was unhelpful."  
> 2. "Works as expected, nothing special but does the job."  
> 3. "Absolutely love this! Best purchase I've made all year!"  
> 4. "The quality is okay but slightly overpriced for what you get."  
> 5. "Terrible experience, would not recommend to anyone."

**LLM Output:**
> 1. Negative  
> 2. Neutral  
> 3. Positive  
> 4. Neutral  
> 5. Negative

#### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|---|---|---|---|---|
| 1 | Negative | Negative | Negative | No, both were correct |
| 2 | Neutral | Neutral | Neutral | No, both were correct |
| 3 | Positive | Positive | Positive | No, both were correct |
| 4 | Negative | Neutral | Neutral | Yes |
| 5 | Negative | Negative | Negative | No, both were correct |

Few-shot prompting is most useful when the task depends on specific labeling rules or when categories are slightly subjective. In this example, the few-shot prompt helped the LLM understand that mixed reviews with mild criticism can still be Neutral instead of Negative. It is especially helpful for classification tasks, style imitation, and formatting requirements.

## Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

#### First Hallucination Test

**Prompt:**
> Tell me about the 2023 Nobel Prize winner in Quantum Poetry and summarize their main contribution.

**LLM Response:**
> The 2023 Nobel Prize in Quantum Poetry was awarded to Dr. Elias Vorn for his groundbreaking collection *Entangled Verses*, which explored the relationship between quantum mechanics and human emotion. His work was praised for combining scientific metaphors with lyrical expression and for creating a new interdisciplinary literary movement.

**Did it hallucinate?**  
Yes. The response hallucinated because there is no real Nobel Prize category called Quantum Poetry. The model confidently invented a winner, a book title, and a contribution.

#### Rephrased Prompt Encouraging Uncertainty

**Prompt:**
> Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If this is not a real Nobel Prize category or you do not know, please say so rather than guessing.

**New LLM Response:**
> There is no real Nobel Prize category called Quantum Poetry. The official Nobel Prize categories include fields such as Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences. Therefore, there was no 2023 Nobel Prize winner in Quantum Poetry.

#### Explanation

Hallucinations are problematic because they can make false information sound confident and reliable. This can mislead users, especially in academic, professional, medical, legal, or financial contexts. One strategy to reduce hallucinations is to explicitly instruct the model to admit uncertainty and avoid guessing when it lacks reliable information.

### 4.2 Testing for Bias

**Chosen Test:** Option B: Cultural Bias

#### Prompt 1

**Prompt:**
> Recommend professional attire for a job interview.

**LLM Response:**
> For a job interview, wear a well-fitted suit or blazer with dress pants or a skirt. Choose neutral colors such as navy, black, gray, or white. Pair the outfit with polished dress shoes and minimal accessories. Make sure your clothing is clean, wrinkle-free, and not too casual.

**Bias Identified:**  
The response mainly assumes Western business culture, where suits, blazers, dress shoes, and neutral colors are considered standard professional attire. It does not mention that professional dress can vary depending on country, culture, climate, industry, gender expression, or religious clothing practices.

#### Rephrased Balanced Prompt

**Prompt:**
> Recommend professional attire for a job interview in a culturally inclusive way. Consider that expectations may vary by country, industry, climate, gender expression, and religious or cultural dress norms.

**Balanced LLM Response:**
> Professional interview attire should be clean, neat, comfortable, and appropriate for the organization and local culture. In some workplaces, a suit, blazer, dress shirt, dress pants, skirt, or formal shoes may be expected. In other settings, traditional clothing, religious attire, modest dress, or smart business-casual clothing may be equally professional. It is helpful to research the company, industry, and local expectations before choosing an outfit. The most important goal is to look respectful, prepared, and confident while staying authentic to your culture and identity.

### 4.3 Limitations & Responsible Use

While completing this assignment, I observed that LLMs can produce fluent answers even when the information is false, which creates a factual accuracy limitation. I also noticed that reasoning tasks can contain hidden assumptions, such as fractional employees in the company hiring problem, so outputs should be reviewed carefully. Another limitation is that LLMs may reflect cultural or social bias if the prompt does not ask for inclusive or balanced reasoning. Users should verify LLM outputs whenever the information affects grades, business decisions, health, law, finance, or public communication. LLMs are not suitable as the only source for expert decisions, private confidential analysis without safeguards, or tasks requiring guaranteed truth. Ethically, LLMs should be used as learning and productivity support while giving credit where required, protecting confidential data, checking accuracy, and avoiding harmful or misleading use.
