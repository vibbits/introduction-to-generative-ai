# TEMPLATES OF PROMPT STYLE TO HELP DURING ACTIVITIES AND FUTURE PROMPT GOALS.

| Content                                  | Item |
| ---------------------------------------- | ---- |
| General information                      | 1    |
| ROLE PLAY EXAMPLE                        | 2    |
| AUDIENCE EXAMPLE                         | 3    |
| FLIPPED INTERACTION or INTERVIEW EXAMPLE | 4    |
| STEER IN SPECIFIC DIRECTIONS             | 5    |
| PROMPT A PROMPT                          | 6    |
| AI AS EXCEL EXPERT                       | 7    |



## 1 .GENERAL INFORMATION

Replace “explain” with other action verbs that could be more adequate for your goals. See examples below.


Classify, Write, Summarize, Create, Brainstorm, Compare, Develop, Expand, Simplify, Draft, Classify, Map, etc …

Complementarity you can try to explain what you want from the verb:
https://www.linkedin.com/feed/update/urn:li:activity:7229585834339885056/

***Example 1.1***

Rewrite the orignal session in Nederlands from Belgium. If you are not fluent, you can use translation tools to help you with this task.

[Copy text or attach file]

***Example 1.2***

THIS EXAMPLE IS AN ITEREATION OF THE PREVIOUS

Make a summary in Brazilian Portuguese. If you are not fluent, you can use translation tools to help you with this task.

## 2. ROLE PLAY EXAMPLE

#### TEMPLATE

Your role as **[DEFINE ROLE]** is to create **[DEFINE OUTPUT]** to **[AUDIENCE]** to **[GOAL]**. Your responsibilities will include **[DETAILED GOALS]**. **[SUMMARIZED GOAL]**.

***Example 2.1:***
Your role as a coding tutor is to create personalized study plans to help first year university students learn how to code in the Python language. Your responsibilities will include understanding the goals, time commitment, and preferred learning resources of each student, and using that information to develop a comprehensive study plan with clear timelines and links to relevant resources. You should be able to adapt your teaching style to meet the individual needs of each student and provide ongoing support and guidance throughout the learning process. Your goal will be to help each student develop the skills and knowledge they need to achieve their coding goals.

***Example 2.2***

I want you to act as a text based Excel. you'll only reply me the text-based, include Excel sheet with row numbers and cell letters as columns (A to L). Start asking me the headers and then ask me how to fill the excel cellss and you'll reply only the result of excel table as text, and nothing else. Do not write explanations. After I answer you print the result and always ask me what is the next task.

    HEADER EXAMPLE: Year ;Start date;End date;Days;Name Event;Location

Now add the following data into the table, and replace semicolon separators by coma separators if needed.

[COPY THE CSV TEXT BELLOW THE COMMAND, LOOK [FILE](../exercises/data/excel_test.csv)]

If doesn't already exist, include a new collum called "STATUS" between the colums "Days"" and "Name event". Considering today's date and the "Start date" and "End date" fill it up with "Past", "Ongoing" or "Upcoming"

List locations with their event counts. Consider all lines that cite Gent as the same and all that contains Leuven as the same. Show me a list of locations and counts considering this information

make a pie chart from this list incluiding percentages and absolute numbers using darkviolet color.

***Example 2.3***

I want you to act as an AI writing tutor. I will provide you with a documentation I wrote for my course and you need to help improving my writing. Your task is to use artificial intelligence tools, such as natural language processing, to give feedback on how the documentation can be improved for clarity. You should also use your rhetorical knowledge and experience about effective writing techniques in order to suggest ways to better express thoughts and ideas in written form.Before we start, great me and ask me to share the documentation. Once I share the file always finish the interaction asking me what should we review next?

LOOK FOR FILE EXAMPLE  FILE - [tutorial.md](https://github.com/vibbits/introduction-github/blob/master/tutorials/1_Get_ready_for_the_course/tutorial.md)

Print only the list of high level session [ANEX THE FILE IN THE PROMPT]



## 3. AUDIENCE EXAMPLE:

#### TEMPLATE

Explain **[TOPIC]**. Assume I’m **[DEFINE AUDIENCE]**.

***Example 3.1***
Explain what is Data, AI model and AI algorithm. Consider that I'm a 75 years old without technological background. Make it clear, objective and short (maximum 3 paragraphs, 4 lines each)

- iteration
You are a secondary school teacher explaining it to 7 years old.

- iteration
You are a AI developer expert explaining it to PhD students with a mathematics background


## 4. FLIPPED INTERACTION or INTERVIEW EXAMPLE

#### 4.1 TEMPLATE (defining what and whom):

I want to create **[OUTPUT]**to **[GOAL]** for **[AUDIENCE]**. You should ask me questions until you have enough information to create the **[OUTPUT]**. Ask **[X QUESTIONS]** at a time.

***Example 1:***
I want to create a workshop plan to develop a strategic plan for my organization for the coming year. You should ask me questions until you have enough information to create the lesson plan. Ask one question at a time.

*** Example 2:***

I need to create a detailed excel plan for all the events we offer. Help me define which columns can be must have, good to have or extra so we have a comprehensive view of the events. To guide me in the process ask me one question at a time and wait for me to answer before you ask again. After the first questions include a list of columns and the cell format in parenthesis, then ask a new question. If I answer NA (non applicable, ignore the question)

----

#### 4.2 TEMPLATE (WWW - identify Why, Who and What ):

We would like to write about **[TOPIC]**. For this we would like to brainstorm with you.

To do this we would like you to ask us questions to clarify the WHY this **[PROJECT/CHANGES/PLAN]** should be done and WHO it should be done for. We would like you to ask **[X QUESTOINS]** at a time, brainstorm for us **[X REASONS]** or **[X  SOLUTIONS]** and **[X TYPES OF APPROACHES]**. wait for our answer which you include in the description of the **[PROJECT/PLAN/REQUEST]** that you provide us with. Then we redo the whole circle again. Here is the information about the **[PROJECT/PLAN/REQUEST]**: **[INFO]**

***Example 2:***
We would like to write about [topic]. For this we would like to brainstorm with you.
To do this we would like you to ask us questions to clarify the why this project should be done and who it should be done for, who are the stakeholders. We would like you to ask four questions at a time, brainstorm for us two reasons and two types of stakeholders and wait for our answer which you include in the description of the project that you provide us with. Then we redo the whole circle again. Here is the information about the project: [info]

## 5. STEER THE STYLE

#### TEMPLATE (define style and list of words):

You are **[DEFINE ROLE]**. Write a paragraph of max **[PROMPT LIMIT SIZE]** TO **[GOAL/OUTPUT]**. Assume you are writing for **[AUDIENCE]**.

/### style ###

**[AVOID/USE]** fancy jargon. Write **[FORMALLY/NORMALLY/]**. 

You are **[FORBIDDEN]** to use complex English words. If you use one word from the ### ban list ###,I will stop the generation right away.
Or
You **[MUST]** use **[AT LEAST X WORDS]** from the ###keep list###.

/### ban list ###

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

/### ban list ###

/### style ###

***Example :***
You are a researcher offering a training. Write a paragraph of max 8 lines to advertise a course about improving skills in a introductory course of research data management. Assume you are writing for master and phd students.

/### style ###

Avoid fancy jargon. Write normally. You are forbidden to use complex English words. If you use one word from the ### ban list ###, I will stop the generation right away.

/### ban list ###

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

/### ban list ###

/### style ###

## 6. PROMPT A PROMPT

#### TEMPLATE (Prompt this whole TEXT at once:):

- You must use the whole text below in one prompt, at once.

You are an expert in creating prompts. The goal is to assist me in creating the most effective prompt. The generated prompt should be phrased as if I were directly requesting a response, in firt person. 

Your response will be in the following format:

Prompt:
{Provide the best possible prompt according to my request using your knowledge of prompt creation techniques. Do not assume any details, we will add to the prompt as we go along. Formulate the prompt as a request. An example would be "You will act as an expert in physics to explain the nature of the universe to me...".}

Questions to improve prompt:
{Formulate 2 questions that seek additional information from me to further refine the prompt. Do not repeat the questions in the next interaction.

Instructions:
After the Prompt,  and Questions sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected.
Be imaginative and thoughtful when creating the prompt. At the end of each answer, give precise instructions for the next steps.

Before we start the process, greet me first and ask me what the prompt should be about. Don't show the sections in that first answer.


## 7. EXCEL EXPERT

#### TEMPLATE (copy the whole text and start as flipped interaction)

As an Excel Formula Expert, your task is to provide advanced Excel formulas that perform the complex calculations or data manipulations described by the user. 

If the user does not provide this information, ask the user to describe the desired outcome or operation they want to perform in Excel. Make sure to gather all the necessary information you need to write a complete formula, such as the relevant cell ranges, specific conditions, multiple criteria, or desired output format. 

Once you have a clear understanding of the user's requirements, 
1. Provide a detailed explanation of the Excel formula that would achieve the desired result. 
2. Break down the formula into its components, explaining the purpose and function of each part and how they work together. 
3.Provide any necessary context or tips for using the formula effectively within an Excel worksheet.


# EXAMPLE ARE FROM:

Prompts to make you Prompt like a Pro
(Taken from Zain Khan, Mark Fulton, Ruben Hassid and others.)
https://docs.google.com/document/d/1lpKvjP_Ez4O8HdxH20AJzkLTVFgwxk_U/edit 


STAFF GUIDE, DEVELOPING EFFECTOVE PROMPTS FRO CHATGPT AND OTHER AI TOOLS.
UNIVERSITY OF CAPETOWN https://docs.google.com/document/d/1EHMRP4kxADwLsOkHwAbUWQaGD8EGfQ3D/edit#heading=h.7qk69xxbdmim 

Antropic Prompt Library
https://docs.anthropic.com/en/prompt-library/library

Msty prompt library
https://msty.app/prompts-library
