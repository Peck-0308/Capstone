# Our Solution
## Conversation Flow

Based on the Fabrikam IT Team scenario, we designed a structured interaction where the Copilot agent collects user information before forwarding it to IT support.

1. The user starts the conversation by typing:
   **"Submit a request"**

2. The Copilot agent responds by collecting required details:

   • What is your name?  
   → Response is stored in variable: `userName`

   • Which department are you in?  
   → Response is stored in variable: `department`

   • What type of issue are you experiencing?  
   → Response is stored in variable: `issueType`

3. After collecting all inputs, the agent generates a structured summary:

----------------------------------
IT SUPPORT REQUEST (Fabrikam)
----------------------------------
Name: {userName}  
Department: {department}  
Issue Type: {issueType}  
----------------------------------

4. The agent confirms that the request has been captured and is ready to be passed to the IT Team at Fabrikam.

This ensures that all support requests are complete, structured, and easy for the IT team to process.

<img width="1366" height="639" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/21f71c1e-48a8-49d4-9e6a-663e5b40da04" />

<img width="1366" height="641" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/20b96411-2249-4312-a9ce-15e2450eaad4" />

<img width="1366" height="637" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/ec3886d8-95dc-47e4-b965-1d5c53eb6ed1" />

<img width="1366" height="636" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/3a01f3eb-d12f-41d9-be86-e1cacb30c509" />
