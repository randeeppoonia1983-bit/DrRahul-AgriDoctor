
# 🌱 Agri Doctor

**Agri Doctor** is an AI-powered assistant designed to support farmers and agricultural stakeholders with real-time insights, crop guidance, and problem diagnosis. Built using modern LLM orchestration and enterprise-grade AI models, it delivers reliable, context-aware recommendations to improve agricultural productivity.

---

## 🚀 Features

* 🌾 **Crop Advisory** – Get personalized recommendations for crop selection, soil health, and seasonal planning
* 🐛 **Disease Diagnosis** – Identify plant diseases and receive actionable treatment suggestions
* 🌦️ **Weather-Aware Insights** – Contextual advice based on environmental conditions
* 💬 **Conversational Interface** – Simple chat-based interaction for ease of use
* 📊 **Data-Driven Decisions** – Leverages AI to provide accurate and explainable outputs

---

## 🧠 Tech Stack

This project is built using the following technologies:

* **Langflow** – For building and orchestrating LLM workflows visually
* **IBM Watsonx.AI** – For enterprise AI capabilities and model deployment
* **IBM Granite (granite-4h-small)** – Lightweight yet powerful language model for fast and efficient inference

---

## 🏗️ Architecture Overview

Agri Doctor uses a modular AI pipeline:

1. **User Input** → किसान (Farmer) provides query via chat interface
2. **Langflow Pipeline** → Processes and routes the query through defined nodes
3. **IBM Watsonx.AI** → Hosts and manages the AI model
4. **Granite Model** → Generates context-aware agricultural responses
5. **Response Output** → Delivered back to the user in natural language

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.8+
* Langflow installed
* IBM Cloud account with Watsonx.AI access

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/agri-doctor.git

# Navigate to project directory
cd agri-doctor

# Install dependencies
pip install -r requirements.txt

# Run Langflow
langflow run
```

---

## 🔧 Configuration

* Set up your **IBM Watsonx.AI API credentials**
* Configure the **Granite model (granite-4h-small)** endpoint
* Import the Langflow JSON workflow into your environment

---

## 📌 Usage

1. Start the Langflow server
2. Open the UI in your browser
3. Load the Agri Doctor workflow
4. Enter your query (e.g., *“Why are my tomato leaves turning yellow?”*)
5. Get instant AI-powered advice

---

## 🎯 Use Cases

* Small-scale and large-scale farmers
* Agricultural consultants
* Agri-tech startups
* Research and education in agriculture

---

## 📈 Future Enhancements

* 🌍 Multi-language support (Hindi, regional languages)
* 📷 Image-based disease detection
* 📡 IoT integration for real-time soil and weather data
* 📱 Mobile app deployment

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, create a new branch, and submit a pull request.

---


---

If you want, I can also tailor this README for **GitHub portfolio impact**, add **badges**, or make it more **resume-focused**.
