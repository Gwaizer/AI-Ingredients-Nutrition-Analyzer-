# AI Ingredients & Nutrition Analyzer

## Introduction
This project was built during the **KAUST Summer Camp (2024/2025) AI Program**.  
Special thanks to our mentor **Dr. Salah Abdeljabar** for guiding us throughout our two months in the program with valuable insights and direction.  

The project aims to help users make sense of ingredients and nutritional facts in consumable products—highlighting health benefits, risks, and allergens.  
Users simply take a picture of the product, and it goes through our pipeline:  
1. OCR extracts raw text.  
2. Data Cleaning improves accuracy.  
3. LLM interprets and enriches the text with trusted databases.  
4. Flutter App renders the structured output in a clean, user-friendly interface.  

---

## Who We Are
We are a team of software engineering and AI students selected for the **KAUST Stage-4 Summer AI Program**, one of the most competitive programs in the region.  

- **Naif Almalik** – Team Leader, OCR Developer  
  Email: naifalmalikk@gmail.com  

- **Ahmad Algwaiz** – Idea Proposer, App Engineer & Developer  
  Email: Ahmadf605@hotmail.com  

- **Mohammed Alabdulmuhsin** – LLM Developer  
  Email: Mm.alabdulmuhsin@gmail.com  

- **Ibrahim Alshayea** – LLM Developer  
  Email: ibrahimalshaya5@gmail.com  

- **Faisal Alwadie** – OCR Developer  
  Email: faisal11bander@gmail.com  

**Mentor:** Dr. Salah Abdeljabar (KAUST)  

This program provided us with the resources, mentorship, and collaborative environment to bring this project from concept to working prototype.  

---

## Our Project
**AI Ingredients & Nutrition Analyzer** is an AI-powered framework that extracts and analyzes information from food product labels.  

- Capture: User snaps a picture of a food label.  
- OCR: State-of-the-art Optical Character Recognition extracts ingredients & nutrition text.  
- LLM: An AI model interprets the text, adds warnings/allergen info, and enriches with external knowledge.  
- App: The results are presented through a Flutter mobile app with a smooth and user-friendly design.  

The system increases transparency and helps consumers make healthier, informed decisions in their daily lives.  

---

## The Problem
Food labels are often:  
- Complex, inconsistent, and filled with jargon.  
- Difficult to interpret without calculations.  
- Missing clear warnings about allergens, additives, or risks.  

According to the **International Food Information Council (IFIC) 2021 Survey**:  
- Only 9% of consumers fully understand food labels.  
- 6 out of 10 consumers want healthier products but struggle due to confusing labels.  

This lack of clarity can lead to poor decision-making and health risks.  
Our project directly addresses this problem by making label information clear, structured, and actionable.  

---

## Acknowledgements
We would like to express our gratitude to:  
- **Dr. Salah Abdeljabar (KAUST)** – for his mentorship, guidance, and continuous feedback.  
- **KAUST Academy** – for selecting us among ~100 students from 10,000+ applicants and providing this unique learning opportunity.  
- Our peers and program organizers – for creating a collaborative and motivating environment.  

---

## Future Work
One of the main limitations we faced was the lack of public datasets to fine-tune or train an Optical Character Recognition (OCR) model, as well as the absence of reliable datasets for refining a Large Language Model (LLM). This limitation led us to adopt cloud-based solutions. Additionally, we found no comprehensive and reliable public database that could be used to enrich ingredient information during analysis.  

For future work, we aim to:  
- Build a dedicated dataset to improve OCR performance.  
- Train a YOLO-based text extractor to enhance OCR results.  
- Fine-tune an LLM on a food products dataset.  
- Construct a specialized ingredients database that can provide accurate and consistent information for the LLM to reference, making the system more robust and reliable. 
