# Note on DPO

Training **Direct Preference Optimization (DPO)** on the **Vietnamese Alpaca Preference** dataset using **LLaMA 3.2 1B Instruct** (QLoRA 4-bit).  

DPO optimizes the model to prefer “chosen” responses over “rejected” ones **without** using a separate reward model or PPO.  

**Pipeline:**  
1. Supervised Fine-tuning (SFT)  
2. Convert to preference format  
3. DPO fine-tuning  
4. Save & push to Hugging Face  

---

### 📄 References & Resources
- **PDF Guide:** [AI VIETNAM](https://www.facebook.com/share/16UN8WJ5Qu/)  
- **Source Code:** [https://github.com/ThuanNaN/aio2024-chatbot-llm-rlhf](https://github.com/ThuanNaN/aio2024-chatbot-llm-rlhf/tree/main/notebooks)  
- **Reference Reading:** [Medium Article](https://medium.com/@lmpo/direct-preference-optimization-a-novel-approach-to-language-model-alignment-1f829d4ac306), [Blog](https://chanys.github.io/dpo)  
- **Step-by-step DPO Implementation:** [https://github.com/0xallam/Direct-Preference-Optimization](https://github.com/0xallam/Direct-Preference-Optimization)  
