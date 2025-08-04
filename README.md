# Eco-Lifestyle-Agent-IBMCloud
An intelligent AI-powered chatbot built with IBM Watson Assistant and Cloud Object Storage that empowers users to adopt a greener lifestyle through personalized, actionable suggestions. Ask about eco-friendly habits, plastic alternatives, local recycling tips, and more and get instant guidance to live sustainably.

**An IBM Watson Assistant-powered chatbot promoting digital sustainability and eco-friendly habits**

> A submission for the IBM SkillsBuild + Edunet Foundation AI and Cloud Internship
> 📁 Problem Statement:Eco Lifestyle Agent  
The Challenge – An Eco Lifestyle Agent, powered by RAG (Retrieval-Augmented Generation), empowers 
users to adopt a greener lifestyle through personalized, practical suggestions. 
It retrieves sustainable living tips, eco-friendly product recommendations, local recycling guidelines, and 
government schemes from trusted environmental sources. 
Users can ask natural language questions such as “How can I reduce plastic use at home?” or “What are 
eco-friendly travel options in my city?” and receive instant, actionable guidance. 
The agent promotes small daily actions with big environmental impact, making sustainability easy and 
accessible. 
This AI-driven assistant fosters eco-conscious decisions, raises awareness, and helps build a more 
sustainable future. 

🔍 Project Overview

**Eco Lifestyle AI Agent** is an interactive chatbot built using IBM Watson Assistant and IBM Cloud services.
Its mission: **help users adopt greener habits** through conversational guidance, based on real-life, verified eco-friendly practices.

🧠 Powered by:
* **IBM Watson Assistant** (for NLP + conversation)
* **IBM Cloud Object Storage** (for dataset and project files)

💬 What Can It Do?

The AI Agent answers key sustainability-related questions like:

* "How can I reduce plastic use?"
* "What are eco-friendly travel options?"
* "Where can I recycle near me?"
* "Suggest green alternatives to plastic products"

Each answer is curated from verified eco-awareness tips, public resources, and behavior change science.


## 🗂️ Folder Structure

```
.
├── assets/                      # Screenshots of Watson Assistant setup                 
├── datasets/                    #csv dataset of intents and responses             
├── watsonx/
│   └── (empty or export.json)   # For future integration with Watsonx or RAG models
├── README.md                  
```
✅ Setup on IBM Watson Assistant

1. **Create Intents**
   * Example: `#reduce_plastic`, `#eco_travel`, `#recycle_info`, `#green_products`

2. **Dialog Nodes**
   * Match user input to intents
   * Return a friendly, structured response

3. **Fallback Node (Optional)**
   * To guide users if input isn't recognized
For step-by-step screenshots


📊 Dataset

Available in `datasets.csv`, the dataset includes:

📸 Screenshots
<img width="1919" height="923" alt="Screenshot 2025-08-04 172211" src="https://github.com/user-attachments/assets/8008f061-3a44-436a-aff4-3e6aba0ce3bf" />
<img width="1919" height="901" alt="Screenshot 2025-08-04 172309" src="https://github.com/user-attachments/assets/396aca6b-c616-4cb3-9e79-d04916f1a8a3" />
<img width="1919" height="900" alt="Screenshot 2025-08-04 172334" src="https://github.com/user-attachments/assets/f345fac7-e32b-4146-b820-44ec5be58a33" />
<img width="1919" height="903" alt="Screenshot 2025-08-04 172413" src="https://github.com/user-attachments/assets/fc8acd34-5999-4bd1-88e3-32c5ce5a7cb2" />
<img width="1919" height="888" alt="Screenshot 2025-08-04 172610" src="https://github.com/user-attachments/assets/f5e95379-b822-4c52-864e-ee7ffe79416d" />
<img width="1919" height="894" alt="Screenshot 2025-08-04 172704" src="https://github.com/user-attachments/assets/53b90885-277b-404f-9a58-36c78563fe73" />


🙋‍♀️ Made By
**Deepanshi Sharma**
BCA (Cybersecurity)
Sharda University Agra

“Technology for a greener life, one habit at a time.”
