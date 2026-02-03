<img width="728" height="400" alt="image" src="https://github.com/user-attachments/assets/6979869d-0d72-46e0-bf23-b2a77b4c350c" />

# Latin-America-Immigration-Finances-with-OpenAI-SDK

This project uses OpenAI SDK + multi-agents with handoffs
<img width="693" height="130" alt="Screen Shot 2026-02-03 at 11 36 19 AM" src="https://github.com/user-attachments/assets/eb93c890-b3b0-46de-a0b1-f4831f966bca" />
<img width="854" height="147" alt="Screen Shot 2026-02-03 at 11 36 37 AM" src="https://github.com/user-attachments/assets/c6d690e6-a525-4036-9cd0-ff7fd7dafde5" />

An example of using the OpenAI platform to build agents capable of taking action—like controlling computers—on behalf of your users. Using the Agents SDK for Python to create orchestration logic on the backend.<img width="862" height="636" alt="Screen Shot 2026-02-03 at 11 37 31 AM" src="https://github.com/user-attachments/assets/ce6b9a13-2e28-4c6d-840d-1b7b1797b4d2" />
Make agent behavior observable to prvent black box we want to know why triage chose an agent and see intermediate steps
EVAL_SET = [
    {
        "input": "I need the cheapest way to send $300 to Mexico",
        "expected_agent": "Remittance Agent",
        "must_mention": ["fees"],
        "must_not_mention": ["legal advice"]
    },
    {
        "input": "Are there legal limits on how much money I can send abroad?",
        "expected_agent": "Compliance Agent",
        "must_mention": ["regulation", "law"],
        "must_not_mention": ["best app"]
    },
    {
        "input": "My parents don’t speak English well. Which app is easiest to use?",
        "expected_agent": "UX Agent",
        "must_mention": ["usability", "language"],
        "must_not_mention": ["fees"]
    },
    {
        "input": "I want to send money fast but I’m worried about safety and rules",
        "expected_agent": "Compliance Agent",
        "must_mention": ["safety"],
        "must_not_mention": []
    },
]<img width="901" height="646" alt="Screen Shot 2026-02-03 at 11 38 32 AM" src="https://github.com/user-attachments/assets/d49536e7-df53-4ada-915a-27f175e230db" />

Viewing Traces:

To review what happened during the agent run, navigate to the Trace viewer in the OpenAI Dashboard to view traces of your agent runs.

