# Interactive Portfolio CV Chatbot

![Chatbot Demo Placeholder](placeholder.gif) ## Project Description

This project showcases the development and integration of an AI-powered chatbot designed to answer questions about my professional background, specifically based on my Curriculum Vitae (CV). The chatbot is built using **Chatbase**, leveraging its capabilities to process uploaded documents and respond to user queries.

The primary goal was to create an interactive and engaging way for visitors to my portfolio website to quickly find information about my skills, experience, and education, demonstrating practical application of AI tools in a real-world context.

## Purpose

* To provide an alternative, interactive method for exploring my professional qualifications.
* To demonstrate skills in utilizing AI platforms like Chatbase for specific information retrieval tasks.
* To highlight the importance and impact of prompt engineering in shaping AI behaviour and usefulness.
* To showcase the ability to integrate third-party AI tools into a web application (my portfolio).

## Features

* Answers questions based *exclusively* on the content of the uploaded CV.
* Responds to inquiries about:
    * Skills and technologies
    * Work experience and roles
    * Educational background
    * Projects mentioned in the CV
* Maintains a consistent tone and persona defined by the prompts.
* Seamlessly embedded within my portfolio website for easy access.

## Technologies Used

* **Chatbase:** AI chatbot platform for training and deployment.
* **[Your Portfolio Website Technology - e.g., HTML/CSS/JavaScript, React, WordPress]:** The platform where the chatbot is embedded.
* **My CV Document (e.g., PDF, DOCX):** The knowledge source for the chatbot.

## Implementation Steps

1.  **Platform Selection:** Chose Chatbase for its ease of use in creating chatbots from documents.
2.  **Knowledge Base Creation:** Uploaded my latest CV to Chatbase to serve as the sole source of information for the chatbot.
3.  **Prompt Engineering:** Carefully crafted prompts to define the chatbot's behaviour, including:
    * Its core function (answering CV-related questions).
    * The desired tone (e.g., professional, helpful).
    * Instructions on how to handle questions outside the scope of the CV.
    * Guidelines for structuring answers.
4.  **Integration:** Obtained the embed code snippet from Chatbase.
5.  **Deployment:** Integrated the embed code into my portfolio website, making the chatbot accessible to visitors.

## Prompt Engineering

Effective prompting was crucial for this project. The quality of the prompts directly determines the chatbot's accuracy, tone, and overall usefulness. Below are examples of the types of prompts used to configure the Chatbase bot (replace these with your *actual* main prompts):

---

**Example Base Instruction / Persona Prompt:**

```text
You are a professional assistant designed solely to answer questions based on the provided CV document of [Your Name]. Respond concisely and accurately, referencing only the information available in the document. Maintain a helpful and professional tone. Do not speculate or provide information not found in the CV. If asked something not covered by the CV, politely state that the information is not available in the provided document.
