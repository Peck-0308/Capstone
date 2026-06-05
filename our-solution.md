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

