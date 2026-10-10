# AI Readiness 360 — V7 scoring review

Source: actual Version 7 HTML scoring code. Review copy; not a revised assessment.

## How scores are calculated

- Questions 1–5: profile only. They receive **no points**, and do not influence the readiness score. They may personalize guidance.
- Questions 6–25: 20 scored questions. For each, the **first displayed option earns 0**, then **1.25, 2.50, 3.75, 5.00** points in displayed order. This is **not a shuffled answer key**.
- Overall score displayed: **round(sum of the 20 question points)**. Maximum is **100/100**. JavaScript rounding rounds nonnegative halves up.
- Category percentage displayed: **round(category points / (number of category questions × 5) × 100)**.

## Categories (as coded)

| Category | Questions | Maximum points | Share of overall score |
|---|---:|---:|---:|
| AI understanding | 5 | 25 | 25% |
| Practical use | 7 | 35 | 35% |
| Safety & judgment | 5 | 25 | 25% |
| Building & automation | 3 | 15 | 15% |

**Important:** Categories are *not* equally weighted. “Practical use” contributes up to 35 points; “Building & automation” contributes up to 15 points. This is what Version 7 currently does.

## Readiness level cutoffs

| Rounded overall score | Level |
|---|---|
| 0–35 | Getting Started |
| 36–60 | Explorer |
| 61–80 | Practitioner |
| 81–100 | Advanced Explorer |

## Learning-resource / roadmap band (separate cutoffs)

- Raw rounded score **0–35**: beginner roadmap
- **36–75**: intermediate roadmap
- **76–100**: advanced roadmap

**Review flag:** A score of 76–80 produces the **Practitioner** level but the **advanced** roadmap; this is currently intentional in code or a threshold mismatch worth reviewing.

## Exact questions and option points

### Q1. Which description fits you best?
*Category: Profile — not scored*

1. Student / job seeker — **— (not scored)**
2. Teacher / educator — **— (not scored)**
3. Business owner / freelancer — **— (not scored)**
4. Employee / government professional — **— (not scored)**
5. IT / technology professional — **— (not scored)**
6. Everyday learner / other — **— (not scored)**

### Q2. Where did your AI journey begin?
*Category: Profile — not scored*

1. I have not tried AI yet — **— (not scored)**
2. Curiosity or asking questions — **— (not scored)**
3. Photos, greetings or social media — **— (not scored)**
4. Studying or learning — **— (not scored)**
5. Emails, documents or work — **— (not scored)**
6. Coding, automation or creating something — **— (not scored)**

### Q3. How often do you use AI today?
*Category: Profile — not scored*

1. Not yet — **— (not scored)**
2. Less than once a month — **— (not scored)**
3. A few times a month — **— (not scored)**
4. A few times a week — **— (not scored)**
5. Almost every day — **— (not scored)**
6. Several times each day — **— (not scored)**

### Q4. Where are you using AI? (Choose all that apply)
*Category: Profile — not scored*

1. Personal life — **— (not scored)**
2. Education / learning — **— (not scored)**
3. Work and office documents — **— (not scored)**
4. Creative content — **— (not scored)**
5. Business and customers — **— (not scored)**
6. Coding / technical projects — **— (not scored)**
7. Not using it yet — **— (not scored)**

### Q5. How have you learned AI so far?
*Category: Profile — not scored*

1. I have not started — **— (not scored)**
2. Exploring on my own — **— (not scored)**
3. YouTube, articles or tutorials — **— (not scored)**
4. Short beginner course — **— (not scored)**
5. Certification or structured training — **— (not scored)**
6. Projects and hands-on practice — **— (not scored)**

### Q6. You want an AI assistant to help with something new. What do you do first?
*Category: AI understanding*

1. I would avoid it entirely — **0.00 points**
2. Ask a very vague question and stop — **1.25 points**
3. Explain the task briefly — **2.50 points**
4. Include my goal and some context — **3.75 points**
5. Include my goal, context, constraints and desired output — **5.00 points**

### Q7. An AI answer sounds convincing. How do you treat it?
*Category: AI understanding*

1. Assume it is always correct — **0.00 points**
2. Share it without checking — **1.25 points**
3. Check only if something looks unusual — **2.50 points**
4. Verify important claims with reliable sources — **3.75 points**
5. Verify high-impact claims with primary sources and acknowledge uncertainty — **5.00 points**

### Q8. You need a recent price or announcement. What would you do?
*Category: AI understanding*

1. Trust whatever a chatbot remembers — **0.00 points**
2. Ask AI without checking the date — **1.25 points**
3. Ask AI for an estimate — **2.50 points**
4. Use a source with current information — **3.75 points**
5. Check the date and original source, comparing important details — **5.00 points**

### Q9. You are about to share a private document with an AI tool. What is your first step?
*Category: AI understanding*

1. Upload everything immediately — **0.00 points**
2. Assume every tool is private — **1.25 points**
3. Remove my name but keep other sensitive details — **2.50 points**
4. Check the tool’s privacy rules and remove sensitive information — **3.75 points**
5. Check organizational permission, privacy terms and minimize or redact information — **5.00 points**

### Q10. An AI tool gives you a result you do not understand. How do you respond?
*Category: AI understanding*

1. Use it anyway — **0.00 points**
2. Give up instantly — **1.25 points**
3. Ask it to repeat the answer — **2.50 points**
4. Ask for a simpler explanation and an example — **3.75 points**
5. Ask for an explanation, test the example, and verify understanding — **5.00 points**

### Q11. You want to create a birthday greeting or social post. Which approach sounds most like yours?
*Category: Practical use*

1. I would never try AI — **0.00 points**
2. Ask AI to make anything and post it — **1.25 points**
3. Describe the occasion and audience — **2.50 points**
4. Ask for several versions and customize one — **3.75 points**
5. Create drafts, personalize them, and check details before sharing — **5.00 points**

### Q12. You want to learn how to do something unfamiliar at home. What would you do?
*Category: Practical use*

1. Not attempt to learn — **0.00 points**
2. Follow the first AI answer exactly — **1.25 points**
3. Ask AI for basic instructions — **2.50 points**
4. Ask for clear steps and any precautions — **3.75 points**
5. Ask for steps, verify safety-critical advice and adapt to my situation — **5.00 points**

### Q13. You need to improve an email or document. What would you do?
*Category: Practical use*

1. Avoid using AI — **0.00 points**
2. Ask AI to write it with no context — **1.25 points**
3. Give AI the topic — **2.50 points**
4. Specify audience, purpose and tone and then edit — **3.75 points**
5. Specify audience and constraints, revise the draft, and verify facts — **5.00 points**

### Q14. You photograph an unfamiliar product and ask AI about it. What next?
*Category: Practical use*

1. Purchase based only on its response — **0.00 points**
2. Assume its identification is correct — **1.25 points**
3. Ask it for possible product names — **2.50 points**
4. Check model identifiers and compare reviews — **3.75 points**
5. Verify product identity, compare independent reviews, and assess tradeoffs — **5.00 points**

### Q15. An AI response does not solve your problem. What do you do?
*Category: Practical use*

1. Accept that it cannot be solved — **0.00 points**
2. Repeat the same question unchanged — **1.25 points**
3. Try a different wording — **2.50 points**
4. Add missing context and ask for another approach — **3.75 points**
5. Break down the problem, provide feedback, and test the proposed solution — **5.00 points**

### Q16. You want AI to help prepare for a job interview or presentation. What would you do?
*Category: Practical use*

1. Copy a complete AI script — **0.00 points**
2. Memorize AI answers word for word — **1.25 points**
3. Request common questions or topics — **2.50 points**
4. Practice with AI and improve answers using feedback — **3.75 points**
5. Run practice rounds, check accuracy, and adapt answers to real experience — **5.00 points**

### Q17. You use AI to summarize a long article or file. What next?
*Category: Practical use*

1. Treat the summary as the whole truth — **0.00 points**
2. Share it without reading — **1.25 points**
3. Skim the summary — **2.50 points**
4. Check key points against the original — **3.75 points**
5. Cross-check important passages, missing context, and any numerical claims — **5.00 points**

### Q18. AI gives different answers to the same important question. What do you do?
*Category: Safety & judgment*

1. Choose the most confident one — **0.00 points**
2. Pick the first answer — **1.25 points**
3. Ask which one is correct — **2.50 points**
4. Compare the evidence and check a reliable source — **3.75 points**
5. Identify what is uncertain and verify with authoritative information — **5.00 points**

### Q19. A generated image or message looks realistic but suspicious. What is safest?
*Category: Safety & judgment*

1. Immediately forward it — **0.00 points**
2. Assume realistic means genuine — **1.25 points**
3. Ask AI if it is real — **2.50 points**
4. Check its origin before sharing — **3.75 points**
5. Verify provenance using trusted sources and do not spread unverified claims — **5.00 points**

### Q20. AI suggests a shortcut that could expose someone else’s private data. What do you do?
*Category: Safety & judgment*

1. Use it if it is faster — **0.00 points**
2. Try it once without telling anyone — **1.25 points**
3. Ask AI whether it is allowed — **2.50 points**
4. Avoid exposing the data and seek a safe approach — **3.75 points**
5. Reject unauthorized exposure, use approved methods and protect affected people — **5.00 points**

### Q21. You want to use AI output in an important decision. What is your approach?
*Category: Safety & judgment*

1. Let AI decide for me — **0.00 points**
2. Follow it if it sounds smart — **1.25 points**
3. Ask AI for a second opinion — **2.50 points**
4. Use it as one input and check key facts — **3.75 points**
5. Check evidence, risks and expert guidance where appropriate; retain human responsibility — **5.00 points**

### Q22. You are teaching someone else to use AI. What advice matters most?
*Category: Safety & judgment*

1. Trust the chatbot completely — **0.00 points**
2. Always paste full personal details — **1.25 points**
3. Use the first answer unchanged — **2.50 points**
4. Give clear instructions and check results — **3.75 points**
5. Protect private data, validate important results and explain limitations — **5.00 points**

### Q23. You perform the same digital task every week. What would you try?
*Category: Building & automation*

1. Keep doing everything manually even if repetitive — **0.00 points**
2. Ask AI to describe automation — **1.25 points**
3. Save a reusable prompt — **2.50 points**
4. Create a repeatable template or no-code workflow — **3.75 points**
5. Design a workflow with checks, error handling and human review — **5.00 points**

### Q24. You have an idea for an AI-powered service. How would you begin?
*Category: Building & automation*

1. Build a complex product immediately — **0.00 points**
2. Copy an existing product without checking needs — **1.25 points**
3. Ask AI to generate a product idea — **2.50 points**
4. Talk with potential users and build a tiny prototype — **3.75 points**
5. Validate the problem, test an MVP with users, and assess risks and cost — **5.00 points**

### Q25. You want to launch an AI workflow others will rely on. What is essential?
*Category: Building & automation*

1. Publish it after one successful test — **0.00 points**
2. Assume AI never fails — **1.25 points**
3. Test it a few times — **2.50 points**
4. Test common cases, permissions and costs — **3.75 points**
5. Evaluate edge cases, privacy, monitoring, reliability, cost and recovery — **5.00 points**

## Notes before publishing

- The scoring assumes later answer options always represent increasing readiness; examine each question for appropriateness and fairness.
- The totals and category percentages are self-assessment indicators, not validated measures of skills or professional certification.
- No sign-up or collection of personal answers is needed for a static website.