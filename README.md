 🩸 LifeFlow — Expiry-Aware Blood Allocation Network

> A Real-Time Coordination Engine for Life-Saving Resources  
> Built for India's Medical Infrastructure | Powered by Trust


🌐 Live Demo: https://life-flow-pied.vercel.app/



  The Problem
Every year, thousands of units of blood expire in storage while 
patients in nearby hospitals desperately need them. Meanwhile, 
emergency requests go unmatched due to poor coordination between 
blood banks, donors, and hospitals.

LifeFlow solves this.



✨ Features

| Feature | Description |
|---|---|
| 🧠 Expiry-Aware Allocation | Prioritizes blood units closest to expiry first |
| 📍 Geolocation Routing | Matches donors/banks to patients by proximity |
| ⚡ Real-Time Coordination | Live updates across hospitals and blood banks |
| 🤖 Gemini AI Integration | AI-powered insights and smart recommendations |
| 🏥 Hospital Network | Seamless integration with medical infrastructure |
| 🔔 Instant Notifications | Alerts for nearby requests and urgent needs |
| 🏆 Donor Rewards | Points system — redeem for badges and perks |
| 👤 Role-Based Access | Donor, Patient, Hospital, Admin dashboards |



 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI | Google Gemini API |
| Location | Geolocation API |
| Hosting | Vercel / Cloud Run |



 Getting Started

### 1. Clone the repository
git clone https://github.com/PUSHPANJALI021/lifeflow.git
cd lifeflow

2. Install dependencies
npm install

 3. Configure .env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
APP_URL=http://localhost:3000

4. Run the app
npm run dev



 🧠 How Expiry-Aware Allocation Works
1. Every blood unit is tagged with its **collection date & expiry**
2. When a request comes in, the system ranks available units by:
   -  Blood type compatibility
   -  Proximity (geolocation)
   -  Expiry urgency (FIFO — first to expire, first to go)
3. The nearest matching unit is **auto-allocated and routed**
4. Gemini AI assists with demand forecasting and recommendations




 🌐 Deployment
- Frontend + API: **Vercel**
- AI Runtime: **Google Cloud Run**
- Database: **MongoDB Atlas**

