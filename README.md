# Ex.No.5 – Comparative Analysis of Different Types of Prompting Patterns Across Various Test Scenarios

## DATE: 08-08-2026

## REGISTER NUMBER: 212223060068

---

# AIM

To test and compare how an AI language model (ChatGPT) responds to naïve (broad, unstructured) prompts versus basic (clear, refined, and well-structured) prompts across multiple test scenarios, and to analyse the resulting responses in terms of quality, accuracy, and depth.

---

# AI TOOLS REQUIRED

ChatGPT (OpenAI)

---

# PROCEDURE REPORT – Naïve vs Basic Prompting Analysis

# 1. Define the Two Prompt Types

**Naïve Prompt:** a short, broad, or unstructured instruction that gives the model little to no context, format, or constraints, leaving it to guess the intent.

**Basic Prompt:** a clear, detailed, and structured instruction that specifies the task, context, desired format, and constraints, guiding the model toward a focused response.

## Conceptual Flow

<img width="987" height="390" alt="image" src="https://github.com/user-attachments/assets/1dff1581-8993-4c46-97e3-6bf40bbea6c1" />


---

# 2. Prepare Multiple Test Scenarios

Four test scenarios were selected so that each pair of prompts (naïve and basic) targets the same underlying task but differs in the level of structure provided:

- Generating a creative story
- Answering a factual question
- Summarizing a concept
- Providing advice or recommendations

---

# 3. Main Objectives

- Compare the same task under naïve vs structured (basic) prompting
- Evaluate each response on Quality, Accuracy, and Depth
- Identify whether basic prompting consistently outperforms naïve prompting
- Derive best practices for structuring prompts for optimal results

---

# 4. Run Experiments and Record Responses

## Scenario 1 — Creative Story Generation

> **Naïve Prompt:** "Write a story."

**Generated Output (Naïve):**
Once upon a time, there was a girl who lived in a city. She built a robot to help people. The robot worked well and everyone was happy. The end.

> **Basic Prompt:** "Write a 150-word short story about a young inventor named Meera in a futuristic city who builds a robot to help her grandmother with daily chores, ending with a surprising twist."

**Generated Output (Basic):**
In the neon-lit city of Veyon, 17-year-old Meera spent her nights building ARIA, a small caretaker robot for her grandmother, whose knees no longer let her climb the stairs. ARIA fetched medicines, brewed ginger tea just the way her grandmother liked it, and hummed old lullabies at bedtime. Neighbours mocked Meera's cluttered workshop, calling ARIA a toy. Months later, a citywide blackout struck during a storm, trapping elderly residents in darkened apartments. While rescue drones battled the wind, ARIA switched to backup power and guided six neighbours down the stairwell using its built-in torch and voice prompts. When the lights returned, the same neighbours who once laughed now queued outside Meera's workshop — not to mock her, but to ask if she could build one for their families too. Meera smiled: her biggest invention wasn't ARIA. It was care, coded into steel.

<img width="1249" height="668" alt="image" src="https://github.com/user-attachments/assets/1c935518-3c07-4ef7-9b77-bb67039f2322" />


---

## Scenario 2 — Factual Question Answering

> **Naïve Prompt:** "Tell me about volcanoes."

**Generated Output (Naïve):**
Volcanoes are openings in the Earth's surface that release lava, ash, and gases. They can be dangerous and are found in many parts of the world, especially near tectonic plate boundaries.

> **Basic Prompt:** "Explain in exactly 3 labelled bullet points: (1) how volcanoes form, (2) the difference between active, dormant, and extinct volcanoes, (3) one real volcanic eruption that occurred after 2020."

**Generated Output (Basic):**
1. **Formation:** Volcanoes form when magma from the Earth's mantle rises through cracks in the crust, usually along tectonic plate boundaries, and erupts as lava, ash, or gas.
2. **Classification:** an active volcano has erupted recently or is expected to erupt again; a dormant volcano has not erupted in a long time but could reactivate; an extinct volcano is not expected to erupt again.
3. **Example:** the Hunga Tonga–Hunga Ha'apai submarine volcano erupted in January 2022, producing one of the most powerful eruptions recorded in decades.

<img width="1340" height="807" alt="image" src="https://github.com/user-attachments/assets/a4d418a7-865e-4f71-b9b2-e0ecaf8445d0" />


---

## Scenario 3 — Summarizing a Concept

> **Naïve Prompt:** "Summarize this."

**Generated Output (Naïve):**
I'd be happy to help — could you please share the text or article you would like summarized? I don't have any content to work with yet.

> **Basic Prompt:** "Summarize the following paragraph about IoT-based home automation in exactly 3 sentences, covering (a) the core idea, (b) one benefit, and (c) one limitation: 'IoT-based home automation connects household devices such as lights, fans, and door locks to a microcontroller like the ESP32, allowing users to monitor and control them remotely through a mobile app. This improves convenience and energy efficiency, since appliances can be scheduled or switched off automatically when not needed. However, such systems depend heavily on a stable Wi-Fi connection and can be vulnerable to security breaches if devices are not properly authenticated.'"

**Generated Output (Basic):**
IoT-based home automation links household devices, such as lights and door locks, to a microcontroller like the ESP32 so they can be monitored and controlled remotely through a mobile app. Its main benefit is improved convenience and energy efficiency, since appliances can be scheduled or automatically switched off when idle. Its key limitation is a dependence on stable Wi-Fi connectivity and exposure to security risks if devices are not properly authenticated.

---

## Scenario 4 — Providing Advice / Recommendations

> **Naïve Prompt:** "Give me advice."

**Generated Output (Naïve):**
It depends on what area of your life you need advice about — career, health, relationships, or something else. Generally, setting goals and staying consistent helps.

> **Basic Prompt:** "I'm a third-year ECE student aiming for an embedded systems / IoT placement in 8 months. Suggest exactly 3 focus areas for the next 2 months, and for each, give one specific resource or project idea."

**Generated Output (Basic):**
1. **RTOS fundamentals** — learn task scheduling and queues using FreeRTOS on an ESP32 board.
2. **Version control and collaboration** — practise Git/GitHub by pushing your existing ESP32 projects with proper commit history.
3. **A portfolio project** — build and document a sensor-based home automation system end-to-end, from circuit design to a working demo video, to showcase during placement interviews.

---

# 5. Comparative Evaluation Table


<img width="968" height="436" alt="image" src="https://github.com/user-attachments/assets/de5fbc36-16c7-4b7e-91c6-10f7ec5bd859" />


## Average Response Score (out of 3: Low=1, Medium=2, High=3)

<img width="944" height="502" alt="image" src="https://github.com/user-attachments/assets/b806bfc9-8ed3-4e7f-8615-3ef4392faed0" />


---

# 6. OBSERVATION

- Naïve prompts produced short, generic responses that often needed a follow-up prompt to become useful.
- Basic prompts consistently produced more specific, structured, and higher-depth responses across all four scenarios.
- The gap between naïve and basic prompting was largest for the creative-story and advice scenarios, where the naïve prompt gave the model almost no direction.
- For the summarization scenario, the naïve prompt failed outright — the model could not summarize without being given the source text, showing that structure can be a functional requirement, not just a quality improvement.
- Accuracy improved most when the basic prompt specified an exact output format (for example, "3 labelled bullet points") rather than only adding more words.

---

# 7. CONCLUSION

This experiment demonstrates that structured (basic) prompting consistently improves the quality, accuracy, and depth of ChatGPT's responses compared to naïve prompting, across creative, factual, summarization, and advisory tasks alike. The following prompting elements were shown to be effective:

- Naïve (Unstructured) Prompting — baseline for comparison
- Basic (Structured) Prompting — clear task, context, and constraints
- Format-Constrained Prompting — specifying bullet points, word counts, or sentence limits
- Role / Context Prompting — framing the request around a specific persona or situation

Overall, basic prompts did not merely produce longer answers — they produced answers that were more directly usable, better targeted to the stated need, and easier to evaluate for correctness.

---

# RESULT

Thus, the naïve and basic prompting patterns were tested across four different scenarios, and it was observed that basic (structured) prompts consistently produced more accurate, detailed, and higher-quality responses than naïve prompts. The prompt for the above experiment was executed successfully.
