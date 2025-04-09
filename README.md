# LLM Finetuning and Pretraining with Unsloth AI  
This repository contains a comprehensive set of Colab notebooks demonstrating the fine-tuning, continued pretraining, reward modeling, and reasoning of various open-weight LLMs using **Unsloth AI**. The project covers multiple use cases, including coding, chat, mental health chatbots, and exporting to Ollama.  

---

## 🚀 **Why This Project is Important**  
Large Language Models (LLMs) have become a foundational technology for a wide range of applications, including natural language processing, conversational AI, and coding assistance. However, deploying and optimizing these models for real-world scenarios requires **fine-tuning** and **continued pretraining** to adapt them to specific tasks and datasets.  

This project leverages **Unsloth AI** to simplify and accelerate the process of fine-tuning and pretraining LLMs. Unsloth AI provides a lightweight, efficient framework for working with LLMs, reducing memory consumption and speeding up the training process. The use cases in this repository cover a diverse range of applications, including:  
- Code generation  
- Conversational AI  
- Multi-language adaptation  
- Mental health assistance  
- Reward modeling and preference optimization  
- Reasoning and complex problem solving  
- Efficient inference and deployment  

By following the included Colab notebooks, you'll learn how to:  
✅ Fine-tune models using lightweight LoRA (Low-Rank Adaptation)  
✅ Continue pretraining on new datasets  
✅ Optimize reward signals using ORPO (Online Reward Policy Optimization) and DPO (Direct Preference Optimization)  
✅ Export models to **Ollama** for production-ready inference  
✅ Extend context size and improve model reasoning  

---

## ✅ **Assignment Breakdown**  

### **Part A: Finetuning**  
You will finetune various open-weight LLMs using **Unsloth AI** for different tasks:

1. **Llama 3.1 (8B)** – Fine-tuning for a coding task  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1bcsOZAALB913w-lSvDlv-5Rw9BBqgtm4?usp=sharing)  
   **Use Case:** Code generation and debugging assistance  

2. **Mistral NeMo (12B)** – Fine-tuning for a chat task  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1EWi81KzuE3REnubLd6Bbh0VtKJaRUFbh?usp=sharing)    
   **Use Case:** Creating intelligent chatbots for customer support  

3. **Gemma 2 (9B)** – Fine-tuning for a conversational AI task  
   - 📄 [Colab Link](https://colab.research.google.com/drive/17heHe_YVtSZOpZKIJ6LUeTr1HvXc4xnu?usp=sharing)   
   **Use Case:** Natural and human-like dialogue generation  

4. **Phi-3 (medium)** – Fine-tuning for a reasoning task  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1bFIMewTHxRauOgakbNhLCqd4dw78ktEp?usp=sharing)  
   **Use Case:** Math-based problem-solving and logical reasoning

    🎥 [YouTube Video](https://www.youtube.com/watch?v=JkULRhRLeCY)  

---

### **Part B: Continued Pretraining**  
You will use **Unsloth AI** to continue pretraining a model on a new language. This enables the model to:  
✅ Understand new vocabulary and syntax  
✅ Improve language translation and understanding  
✅ Adapt to industry-specific terminology  

- 📄 [Colab Link](https://colab.research.google.com/drive/1kInOc1hr-zTG3HTVFEr7ctRBeTZ4qgBg?usp=sharing)  
- 🎥 [YouTube Video](https://youtu.be/ZckjmHWT_HU)  
**Use Case:** Training a model to understand domain-specific language (e.g., medical terms, financial language)  

---

### **Part C: Chat Templates**  
Predefined templates for creating various chatbot use cases:  

1. **Classification Chat** – Build a chatbot that can classify user input into predefined categories.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/12Mv12hho7L4MKBxd4WOTkdFCwfNjL-IR?usp=sharing)  
   **Use Case:** Customer query classification  

2. **Conversational Chat** – Develop a chatbot for natural, multi-turn conversations.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1rEQybJxgRsmy5SJvkfa8e_3TeLbK15c_?usp=sharing)  
   **Use Case:** Virtual assistant for customer support  

3. **Context Extension with TinyLlama** – Extend the context size of TinyLlama for handling long conversations or documents.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1Z-_nAj5be_eKRAdlC1qpI6Az7_hgXxm5?usp=sharing)  
   **Use Case:** Long document summarization  

4. **Multi-dataset Single Finetuning** – Finetune on multiple datasets simultaneously for enhanced versatility.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/1g1dgGF9X9Xg-Q-SBEt5qJaRHxlH1SGRu?usp=sharing)   
   **Use Case:** Cross-domain understanding and adaptation

    🎥 [YouTube Video](https://youtu.be/-El6rybTkcU) 

---

### **Part D: Reward Modeling**  
Learn how to train LLMs using feedback-based reward models:  

1. **ORPO (Online Reward Policy Optimization)** – Optimize responses in real-time based on user feedback.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/18_ivMr6eReTjRgO15a-aZJ8WSmTAjHfO?usp=sharing)  
   **Use Case:** Customer satisfaction feedback loops  

2. **DPO (Direct Preference Optimization)** – Optimize for direct user preferences to enhance response quality.  
   - 📄 [Colab Link](https://colab.research.google.com/drive/13Ux2G79VSiugjj_YtJ7Q4FzmF_qCWbX1?usp=sharing)  
   **Use Case:** Personalization for content recommendations

      🎥 [YouTube Video](https://youtu.be/xVSEy25AvZ0)  

---

### **Part E: Continued Fine-Tuning from a Custom Checkpoint**  
Finetune from a custom checkpoint using Unsloth AI.  
- 📄 [Colab Link](https://colab.research.google.com/drive/1lJyRbYRgEltUUboMRqZtZopbMsGfpRBH?usp=sharing)
- 📄 [Colab Link](https://colab.research.google.com/drive/1sqg01DP0xiB9AsG9iaDjAmrawSC7nEME?usp=sharing)
- 🎥 [YouTube Video](https://youtu.be/Q5jwUVbhnEI)  
**Use Case:** Custom model adaptation for specialized tasks  

---

### **Part F: Mental Health Development Chatbot**  
Finetune **Phi-3** using Unsloth AI to create a mental health chatbot.  
- 📄 [Colab Link](https://colab.research.google.com/drive/1kSWtZxndUHpVV7tw91v6voyY-sW8Nt09?usp=sharing)  
- 🎥 [YouTube Video](https://youtu.be/o5eF92TeAxA)  
**Use Case:** Mental health support and therapy chatbot  

---

### **Part G: Export to Ollama**  
Finetune a model using Unsloth AI and export it to Ollama for efficient inference.  
- 📄 [Colab Link](https://colab.research.google.com/drive/1KPp8Qvff9Lucx2ErPDFR8297Db-IwfI8?usp=sharing)  
- 🎥 [YouTube Video](https://youtu.be/ShKHcOsWbzc)  
**Use Case:** Fast and scalable model deployment  

---

## 🌟 **Why This Matters**  
✅ Speed up training and inference with Unsloth AI  
✅ Deploy custom models for real-world applications  
✅ Improve LLM performance with targeted fine-tuning  
✅ Build production-ready AI systems with scalable deployment options  

**⭐️ If you found this helpful, give this repository a star!**  
