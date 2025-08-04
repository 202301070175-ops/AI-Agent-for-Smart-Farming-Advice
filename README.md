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
- Granite Model (`granite-13b-chat` or `granite-3-8b-instruct`)  
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
- Name: `Smart Farming Agent`
- Add Cloud Object Storage when prompted

### ✅ Step 4: Build the Chat Agent
- Go to the project → Select **Chat and Build**
- Click **Associate Service** → Create new service
- Choose `watsonx.ai Runtime`

### ✅ Step 5: Model and Tool Selection
- Choose: `granite-13b-chat` (or `granite-3-8b-instruct`)
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

> You are a smart farming assistant. Suggest crops, pest control, soil tips, and mandi rates based on user input.  
> Keep the language simple. Ask for clarification if input is incomplete.

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
- Name: `Smart Farming Deployment`  
- Select: `watsonx.ai` → Click **Create**

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

## 🖼️ Screenshots

### 🔧 Setting Up
![Setup](https://github.com/user-attachments/assets/4ad8d717-e5d7-44a3-8e4d-332d3ff70c58)

### 📋 Agent Instructions
![Instructions 1](https://github.com/user-attachments/assets/497cbcb8-d424-4f9a-aec3-7fa4615b588c)  
![Instructions 2](https://github.com/user-attachments/assets/cb8ba48b-3196-4a22-8763-2297303de268)

### ❓ Sample Questions
![Sample Questions](https://github.com/user-attachments/assets/9c95f258-ce46-4be9-875e-b0cebe4761c9)

### 🔧 Tools & Testing
![Tools](https://github.com/user-attachments/assets/735df535-8805-4c93-a341-28d688eb3a99)

### 🚀 Deployment
![Deployment](https://github.com/user-attachments/assets/ad8a997e-0c44-411c-bb4a-4acc97a47fbe)

### 🔑 API Access
![API](https://github.com/user-attachments/assets/41458869-874f-441e-8d29-be5d7237774e)

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

**Built with ❤️ using IBM Watsonx.ai + IBM Granite for sustainable farming solutions.**
