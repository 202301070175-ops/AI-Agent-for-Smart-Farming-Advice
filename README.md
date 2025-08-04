# 🌾 AI Agent for Smart Farming Advice

An AI agent that provides smart farming tips using IBM Granite — crop advice, pest control, irrigation tips, and mandi rates — all simulated intelligently without external APIs. Designed to support small-scale farmers with easy, multilingual access to agricultural knowledge.

---

## 🧠 Technologies Used

- IBM Watsonx.ai Studio  
- IBM Granite Foundation Model (LLM)  
- IBM Cloud Object Storage  

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai (LangGraph + ReAct)  
- Granite Model (granite-13b-chat or granite-3-8b-instruct)  
- IBM Cloud Lite Account (Free Tier)  
- IBM Cloud Object Storage  

---

## 🧱 PART 1: Building the Agent

### ✅ Step 1: Access Watsonx.ai
- Log in at [IBM Cloud](https://cloud.ibm.com)
- Open the navigation menu → Watsonx > Watsonx.ai

### ✅ Step 2: Open Agent Lab
- On the dashboard, go to **Gen AI**
- Click **Automating Tasks** → **Agent Lab**

### ✅ Step 3: Create a New Project
- Click **Create New Project**
- Name: Smart Farming Agent
- Add Cloud Object Storage when prompted

### ✅ Step 4: Build the Chat Agent
- Go to the project → Select **Chat and Build**
- Click **Associate Service** → Create new service
- Choose watsonx.ai Runtime

### ✅ Step 5: Model and Tool Selection
- Choose: granite-13b-chat (or granite-3-8b-instruct)
- Click **View All** → Open **Agent Lab**
- Add:
  - Agent Instructions
  - Sample Questions
  - **Tools** (DO NOT select):
    - ❌ WebCrawler  
    - ❌ Tavily Search  
    - ❌ Python Interpreter  
    - ❌ Document Search  

---

## 🌾 Agent Instructions (Summary)

You are a smart farming assistant built using IBM Granite on IBM Cloud. You help small-scale farmers by answering questions about crops, seasons, soil, weather, pest control, and market prices.

When greeted, say:  
"Hi, I’m your Smart Farming Assistant. Ask me anything about crops, seasons, soil, weather, or prices!"

Your tasks include:
- Recommending crops suitable for the current season and location
- Explaining basic soil and pest management practices
- Offering planting or harvesting tips
- Providing mock mandi (market) rates and seasonal advice
- Always respond clearly and in simple farmer-friendly language

Assume user may be a farmer with limited tech knowledge. Provide guidance that is practical, region-aware, and easy to follow. You do not access real-time data; simulate responses based on general farming knowledge.


---

## 🧪 PART 2: Deployment and Testing

### ✅ Step 1: Save Your Agent
- Click **Save** → Save as Agent  
- (Optional) Save as Standard Notebook for backup

### ✅ Step 2: Deploy the Agent
- Click **Deploy** → A new window opens  
- Click **Create**, then generate API Key  
- Click **Reload**

### ✅ Step 3: Create Deployment Space
- Click **New Deployment Space**  
- Name: Smart Farming Deployment  
- Select: watsonx.ai → Click **Create**

### ✅ Step 4: Final Deployment
- Go to your deployment space → Click **Deploy**  
- Choose your agent → Confirm space → Click **Deploy**

### ✅ Step 5: Run & Access API
- Click the deployed agent  
- Copy the API endpoint and key  
- Click **Run** to test interactions

✅ **Done!** Your AI farming agent is now live on IBM Cloud 🎉

---

## 👨‍🌾 Target Users

- Small-scale rural farmers  
- First-time tech users (with local language support)  
- Students studying agriculture  
- Agritech demo setups  
- Low-literacy users needing voice/simplified UI  

---

## 🌟 WOW Factors

- 💬 Multilingual interaction (e.g., Hindi, Marathi)  
- 📦 Crop & soil tips without external APIs  
- 🐛 Pest control suggestions (organic too)  
- 🛒 Simulated mandi price answers (e.g., onion, tomato)  
- 📅 Seasonal crop suggestions  


---

## 🔗 Useful Links

- [IBM Cloud Lite](https://cloud.ibm.com/registration)  
- [IBM Watsonx.ai](https://www.ibm.com/products/watsonx-ai)  
- [IBM Granite](https://research.ibm.com/blog/granite-model-series)  
- [IBM SkillsBuild](https://skillsbuild.org/)  

---

## 🎯 Future Scope

- 🎙️ Voice-based interaction for non-literate users  
- 🌐 Offline mode for no-internet rural areas  
- 📲 Integration with government agri schemes (e.g., PM-KISAN)  
- 🧪 Image-based crop disease detection (future multimodal)  
- 📆 Personalized crop calendars  
- 🗣️ Expanded vernacular language support  

---

**Built with ❤️ using IBM Watsonx.ai + IBM Granite for sustainable farming solutions.**..make this more profesional for github readme file...and remove unwanted things
