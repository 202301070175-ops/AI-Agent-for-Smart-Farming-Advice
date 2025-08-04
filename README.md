# AI-Agent-for-Smart-Farming-Advice
AI agent gives smart farming tips using IBM Granite—crop advice, pest control, and mandi rates

SMART-FARMING-ADVICE-AI-AGENT
An AI Agent for Smart Farming Advice, powered by IBM Watsonx.ai and Granite (LLM), helps small-scale farmers receive localized, intelligent agricultural guidance. This AI assistant recommends crops, pest control practices, irrigation tips, and mock mandi prices by simulating real-world expertise — all without using real-time APIs. It supports multilingual interaction and empowers farmers with simple, relevant, and timely decisions to boost yield and income.

🧠 Technologies Used
IBM Watsonx.ai Studio
IBM Granite Foundation Model (LLM)
IBM Cloud Object Storage

☁️ IBM Cloud Services Used
IBM Watsonx.ai (LangGraph + ReAct)
IBM Granite (granite-13b-chat or 8b-instruct)
IBM Cloud Lite Account (free tier)
IBM Cloud Object Storage

🚜 IBM Watsonx.ai Agent Lab – Build, Deploy & Test (Part-1)
🧱 PART 1: Building the Agent
✅ Step 1: Access Watsonx.ai

Log in to your IBM Cloud account: https://cloud.ibm.com
Open the navigation menu → Go to Watsonx > Watsonx.ai
✅ Step 2: Open Agent Lab
On the dashboard, go to Gen AI
Choose Automating Tasks → Click Agent Lab
✅ Step 3: Create a New Project
From the Watsonx homepage, click Create New Project
Name: Smart Farming Agent
Add Cloud Object Storage when prompted
Click Create
✅ Step 4: Build Your Chat Agent
Inside the project, select Chat and Build
Click Associate Service → Create new service
Select watsonx.ai Runtime
✅ Step 5: Model and Tool Selection
Choose model: granite-13b-chat (or granite-3-8b-instruct)
Go to View All → Open Agent Lab
Add:
Custom Instructions
Sample Questions
Select tools (DO NOT select):
❌ WebCrawler
❌ Tavily Search
❌ Python Interpreter
❌ Document Search

🌾 Agent Instructions (Summary)
You are a smart farming assistant. Suggest crops, pest control, soil tips, and mandi rates based on user inputs.
Keep language simple. Ask for clarification if input is incomplete.

🧪 PART 2: Deployment and Testing
✅ Step 1: Save Your Agent
Click Save → then Save as Agent
Also Save as Standard Notebook (optional backup)
✅ Step 2: Deploy the Agent
Click Deploy → New window appears
Click Create to begin deployment
Generate a new API Key → Click Reload
✅ Step 3: Create Deployment Space
Click New Deployment Space
Name: Smart Farming Deployment
Select Watsonx.ai
Click Create
✅ Step 4: Final Deployment
In your deployment space, click Deploy
Select the saved agent → Choose deployment space
Click Deploy
✅ Step 5: Run & Access API
Once deployed → Click the agent
Copy the API endpoint + key
Click Run to test interaction
✅ Done! 🎉 Your AI farming agent is now live on IBM Cloud.
👨‍🌾 Target Users
Small-scale rural farmers needing basic crop and soil guidance
First-time tech users seeking local-language support
Students in agriculture using AI for simulated planning
Agritech demo setups for training and awareness
Low-literacy users needing audio or simplified interaction
🌟 WOW Factors
💬 Multilingual interaction (e.g., English, Hindi, Marathi)
📦 Crop and soil tips without external data
🐛 Pest control advice, organic methods
🛒 Mock mandi rate answers (tomato, onion, wheat, etc.)
📅 Seasonal suggestions based on user location

🖼️ Screenshots
Setting up
<img width="1909" height="921" alt="image" src="https://github.com/user-attachments/assets/4ad8d717-e5d7-44a3-8e4d-332d3ff70c58" />
Agent Instructions
<img width="1767" height="794" alt="image" src="https://github.com/user-attachments/assets/497cbcb8-d424-4f9a-aec3-7fa4615b588c" />
<img width="1912" height="849" alt="image" src="https://github.com/user-attachments/assets/cb8ba48b-3196-4a22-8763-2297303de268" />
Sample Quesions
<img width="1917" height="840" alt="image" src="https://github.com/user-attachments/assets/9c95f258-ce46-4be9-875e-b0cebe4761c9" />
Used Tools and Testing
<img width="1918" height="895" alt="image" src="https://github.com/user-attachments/assets/735df535-8805-4c93-a341-28d688eb3a99" />
Deployment
<img width="1913" height="883" alt="image" src="https://github.com/user-attachments/assets/ad8a997e-0c44-411c-bb4a-4acc97a47fbe" />
API References after Deployment
<img width="1912" height="892" alt="image" src="https://github.com/user-attachments/assets/41458869-874f-441e-8d29-be5d7237774e" />

🔗 Useful Links
IBM Cloud Lite – https://cloud.ibm.com/registration
IBM Watsonx.ai – https://www.ibm.com/products/watsonx-ai
IBM Granite – https://research.ibm.com/blog/granite-model-series
IBM SkillsBuild – https://skillsbuild.org/

🎯 Future Scope
🎙 Voice-based queries (for non-literate farmers)
🌐 Offline chatbot for no-internet rural zones
📲 Integration with Agri Gov schemes (e.g., PM-KISAN)
📊 Image-based crop disease detection (future multimodal)
🧩 Personalized crop calendar
🗣️ Vernacular language expansion










