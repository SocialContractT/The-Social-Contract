# Social Contract App

The **Social Contract App** is a platform where users create "contracts" with friends to achieve goals together. Each contract functions like a **group chat** and a **checklist**, where users must complete tasks by submitting proof (e.g., a photo or video). Proof verification may be automated using **visual AI**, and task completion is recorded on **Solana** (non-monetary, no crypto mining).

## Features
- 📝 **Create Contracts** – Users define group challenges with deadlines.
- 📩 **Messaging System** – Each contract has a built-in group chat.
- ✅ **Task Completion Tracking** – Users submit proof to mark tasks as complete.
- 🤖 **AI Verification (Limited)** – Automate proof validation.
- 🔗 **Solana Integration (In Progress)** – Track completed tasks on-chain.

---

## 🚀 Scalability Roadmap

### **Phase 1: MVP (Current Stage)**
- Basic contracts with group chat and checklist functionality.
- Limited AI task verification.
- Local Flask-based database storage.

### **Phase 2: User Growth**
- Implement email-based authentication.
- Enable contract sharing via invite links.
- Optimize database for increased user activity.
- Share links on targeted social media posts relating to self-improvement and motivation.
- Ads on TikTok, Instagram, YouTube and X.

### **Phase 3: Monetisation**
- Ads & affiliate marketing targeting contract names (for privacy).
- Merchandised sales related to popular contracts.
- Freemium model offering advanced features like an AI personal life coach and ad-free user experience.
- Branded public contracts - where sponsor's contract gets promoted to a wider audience.

---

## 📊 Impact Assessment

### **Potential Benefits**
✔ Encourages **accountability** in goal setting.  
✔ Provides a **gamified** approach to personal & team productivity.  
✔ Uses **blockchain transparency** to prevent disputes.  
✔ Supports **community-driven motivation**.

### ** Market Opportunity

The global personal development market is growing. This means more people are looking for ways to stay committed to their goals. Many are dissatisfied with the traditional social media, seeking more authentic ways to connect. Our network is not about showcasing glamorous lifestyles. It’s about revealing the real effort it takes to achieve them. 

### **Challenges & Considerations**
⚠ **AI Verification Accuracy** – Ensuring reliable proof validation.  
⚠ **Scalability** – Managing database & blockchain integration at scale.  
⚠ **User Retention** – Keeping users engaged long-term.

---

## 🛠 Tech Stack
- **Backend**: Flask, Python  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite (MVP), PostgreSQL (future)  
- **Blockchain**: Solana  

---

## 🚀 Getting Started

Note: use the 'master' branch, not the default 'experimental' branch.

### **1. Clone the Repo**
```sh
git clone https://github.com/SocialContractT/The-Social-Contract.git
cd The-Social-Contract
```

### **2. Install Requirements**
```sh
pip install -r requirements.txt
```

### **3. Run on a Gunicorn server**
```sh
gunicorn -k eventlet -w 1 -b 0.0.0.0:8080 run:gunicorn_app
```

