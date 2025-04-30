# Service Request Assistant

This project leverages Salesforce AgentForce to build an intelligent, conversational AI agent that automates service request handling from start to finish.

---

## Inspiration

In today's fast-paced world, everything has to be accessible 24/7 so that customers can get the information they need whenever they want. This requires companies to dedicate support personnel around the clock, which is a huge cost. By leveraging recent technological developments and the power of AI, they can provide the same human-like service with AI agents like AgentForce via Salesforce.

---

## What it does

Our agent helps customers or potential customers schedule, adjust, or even cancel a service request within minutes. It verifies customer existence, creates new customer records when needed, generates service requests, assigns field technicians based on availability and specialty, and provides estimated costs. It also offers updates on the request, allows changes to the technician or appointment time, logs service notes, and even collects customer feedback—all through an intuitive conversational interface.

---

## How we built it

We used Salesforce’s AgentForce framework to define Agent Actions and connected them to autolaunched flows. Each action triggers a flow that performs database operations like querying for existing customers, creating or updating service requests, assigning technicians, or retrieving historical logs. We also used decision elements and conditional logic in flows to handle various user scenarios, such as whether the customer is new or existing, or whether technicians are available at the desired time. Custom objects like `Customer__c`, `Service_Request__c`, `Field_Technician__c`, and `Service_Log__c` were used to structure the data model.

---

## Challenges we ran into

- Designing a conversational flow that feels natural yet is robust enough to handle various user inputs  
- Implementing technician assignment logic based on both availability and skill match  
- Ensuring real-time updates for technician availability and cost estimations  
- Handling edge cases such as duplicate customers, invalid inputs, or simultaneous service modifications

---

## Accomplishments that we're proud of

- Successfully automating end-to-end service request handling without human intervention  
- Creating a dynamic technician assignment logic that balances availability and skill set  
- Delivering a personalized experience for each customer through intelligent branching logic in AgentForce  
- Seamlessly integrating multiple flows into a single agent experience

---

## What we learned

- The power of combining declarative automation with conversational design using Salesforce AgentForce  
- Best practices for designing scalable and modular autolaunched flows  
- How to simulate real-world service operations in a digital assistant context  
- Importance of user experience in designing agent interactions

---

## What's next for Service Request Assistant

- Integrating calendar scheduling functionality for real-time appointment booking  
- Enhancing cost estimation logic with real-time pricing APIs  
- Enabling multilingual support for a broader customer base  
- Adding analytics to track agent usage and optimize flows based on common paths and drop-offs

🛠 Built with ❤️ using Salesforce DX, AgentForce, and Autolaunched Flows
