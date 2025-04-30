# Service Request Assistant 🚀

An AI-powered Salesforce agent that handles customer service requests from start to finish—without human intervention.

---

## 💡 Inspiration

In today's fast-paced world, customers expect 24/7 accessibility. Maintaining human support around the clock is costly. Leveraging Salesforce AgentForce and AI, businesses can now deliver human-like support experiences—without the cost.

---

## 🛠️ What It Does

- 📅 Schedule, update, or cancel service requests via conversation
- 👤 Create new or verify existing customer records
- 🔧 Assign technicians based on availability & skill
- 💰 Provide cost estimates
- 📬 Update users on request status
- 🔁 Reschedule or switch technicians
- 📝 Log service notes & collect feedback

All powered through a conversational, intuitive interface!

---

## 🧱 How We Built It

- **AgentForce Framework** to define Agent Actions
- **Autolaunched Flows** for backend automation
- **Decision Logic** to handle new vs existing customers, available vs unavailable technicians
- **Custom Objects:**
  - `Customer__c`
  - `Service_Request__c`
  - `Field_Technician__c`
  - `Service_Log__c`

---

## 🚧 Challenges We Faced

- Designing natural yet robust conversational flows
- Technician assignment logic (availability + skill)
- Real-time data updates
- Handling edge cases (duplicates, invalid data, simultaneous requests)

---

## 🎉 Accomplishments

- Fully automated end-to-end service flow
- Smart technician assignment engine
- Personalized user experience with dynamic logic
- Smooth multi-flow integration into AgentForce

---

## 📚 What We Learned

- How to blend **declarative automation + conversational AI**
- Building scalable modular flows
- Simulating real-life operations digitally
- UX best practices in agent design

---

## 🔮 What's Next

- 🗓️ Real-time calendar scheduling integration
- 💸 Live cost estimation with pricing APIs
- 🌍 Multilingual agent support
- 📊 Analytics tracking for optimization

---

🛠 Built with ❤️ using Salesforce DX, AgentForce, and Autolaunched Flows
