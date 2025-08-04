🌾 AI Agent for Smart Farming Advice
An AI-powered assistant built using IBM Watsonx.ai and Granite LLM to provide smart, simulated farming guidance. Designed for small-scale farmers, the agent suggests suitable crops, offers pest control tips, irrigation guidance, and simulated mandi (market) prices—all without requiring real-time API integration.

🧠 Technologies Used
IBM Watsonx.ai Studio

IBM Granite Foundation Model (granite-13b-chat or granite-3-8b-instruct)

IBM Cloud Object Storage

☁️ IBM Cloud Services
Watsonx.ai (LangGraph + ReAct)

IBM Cloud Lite Account (Free Tier)

IBM Cloud Object Storage

⚙️ Project Workflow
1. Build the Agent
Log in to IBM Cloud → Watsonx.ai → Gen AI → Automating Tasks → Agent Lab

Create a new project and add Cloud Object Storage

Select Chat and Build

Associate Watsonx.ai Runtime service

Choose model: granite-13b-chat or granite-3-8b-instruct

Add agent instructions and sample questions

Exclude tools:

❌ WebCrawler

❌ Tavily Search

❌ Python Interpreter

❌ Document Search

2. Agent Instructions
The agent should:

Suggest seasonal crops based on region

Offer pest and soil management tips

Simulate mandi rates and weather-related advice

Use simple, practical language suitable for farmers

Avoid real-time data calls—simulate based on general agricultural knowledge

Greeting Example:
“Hi, I’m your Smart Farming Assistant. Ask me anything about crops, soil, pests, irrigation, or prices!”

3. Deployment Steps
Save the agent → Deploy

Create and configure a new deployment space

Deploy the saved agent to the new space

Retrieve the API endpoint and key for integration or testing

✅ Agent is now live and testable via API on IBM Cloud

👤 Target Users
Small and marginal farmers

Students of agriculture

Agritech training setups

First-time tech adopters

Low-literacy and multilingual user groups

🌟 Features
Multilingual support (e.g., Hindi, Marathi)

Simulated mandi prices for key crops

Seasonal crop recommendations

Organic pest control suggestions

Farmer-friendly, easy-to-understand replies

🛠️ Sample Questions
txt
Copy
Edit
- What crop is best to grow in August in Maharashtra?
- How can I get rid of whiteflies on tomato plants?
- What is the mandi price for onions in Pune?
- Which fertilizer is best for increasing soil nitrogen?
- गहू साठी योग्य खत कोणते आहे? (Marathi)
🔗 Helpful Resources
IBM Cloud Lite

IBM Watsonx.ai

IBM Granite

IBM SkillsBuild

🚀 Future Scope
Voice-based interaction for non-literate users

Offline chatbot support for low-connectivity areas

Crop disease detection using image inputs (future multimodal support)

Integration with government schemes (e.g., PM-KISAN)

Personalized crop calendars and schedules

Expanded vernacular language models

Built with IBM Watsonx.ai + IBM Granite to empower rural farming with accessible AI.
