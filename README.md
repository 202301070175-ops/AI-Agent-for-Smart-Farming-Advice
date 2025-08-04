🌾 AI Agent for Smart Farming Advice
An AI agent that provides smart farming tips using IBM Granite — crop advice, pest control, irrigation tips, and mandi rates — all simulated intelligently without external APIs. Designed to support small-scale farmers with easy, multilingual access to agricultural knowledge.

🧠 Technologies Used
IBM Watsonx.ai Studio

IBM Granite Foundation Model (LLM)

IBM Cloud Object Storage

☁️ IBM Cloud Services Used
Watsonx.ai (LangGraph + ReAct)

Granite Model (granite-13b-chat or granite-3-8b-instruct)

IBM Cloud Lite Account

IBM Cloud Object Storage

🧱 Part 1: Building the Agent
✅ Step 1: Access Watsonx.ai
Log in at IBM Cloud

Navigate: Menu → Watsonx → Watsonx.ai

✅ Step 2: Open Agent Lab
Go to Gen AI

Click Automating Tasks → Agent Lab

✅ Step 3: Create a New Project
Click Create New Project

Name: Smart Farming Agent

Add Cloud Object Storage

✅ Step 4: Build the Chat Agent
Inside the project: Chat and Build → Associate Service

Create & select watsonx.ai Runtime

✅ Step 5: Model and Tool Selection
Choose: granite-13b-chat or granite-3-8b-instruct

Open Agent Lab → Add:

Agent Instructions

Sample Questions

Tools (DO NOT select):

❌ WebCrawler

❌ Tavily Search

❌ Python Interpreter

❌ Document Search

🌾 Agent Instructions (Summary)
You are a smart farming assistant built using IBM Granite on IBM Cloud. You help small-scale farmers by answering questions about crops, seasons, soil, weather, pest control, and market prices.

When greeted, say:
"Hi, I’m your Smart Farming Assistant. Ask me anything about crops, seasons, soil, weather, or prices!"

Your responsibilities:

Recommend crops for the season and soil

Give pest & soil management advice

Provide simulated mandi prices

Offer practical, localized, simple advice

Do not use real-time data—respond based on general farming knowledge

🧪 Part 2: Deployment and Testing
✅ Step 1: Save Your Agent
Click Save → Save as Agent

(Optional: Save as Standard Notebook)

✅ Step 2: Deploy the Agent
Click Deploy → Create → Generate API Key → Reload

✅ Step 3: Create Deployment Space
Click New Deployment Space → Name: Smart Farming Deployment

Select: watsonx.ai → Click Create

✅ Step 4: Final Deployment
Open the space → Click Deploy

Select your agent → Confirm deployment

✅ Step 5: Run & Access API
Copy API endpoint + key

Click Run to test your deployed agent

✅ Done! Your AI Farming Agent is now live on IBM Cloud 🎉

👨‍🌾 Target Users
Small-scale farmers

First-time tech users (multilingual)

Students in agriculture

Agritech demos & training

Low-literacy users needing simplified UI

🌟 WOW Factors
💬 Multilingual support (e.g., Hindi, Marathi)

📦 Crop & soil guidance without external APIs

🐛 Organic pest control tips

🛒 Simulated mandi price responses

📅 Seasonal suggestions by region

🔗 Useful Links
IBM Cloud Lite

IBM Watsonx.ai

IBM Granite

IBM SkillsBuild

🎯 Future Scope
🎙️ Voice-based interaction

🌐 Offline support for rural regions

📷 Image-based crop disease detection

📲 Integration with PM-KISAN, soil card schemes

📆 Personalized crop calendars

🗣️ More regional language support

Built with ❤️ using IBM Watsonx.ai + IBM Granite for sustainable agriculture.
