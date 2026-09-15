# AI Customer Support Assistant

A small AI-assisted workflow designed to help customer support teams analyze customer messages and create clear, empathetic, and actionable responses.

## Why I built this

I wanted to explore how AI could support a Customer Success workflow while keeping the human relationship with the customer at the center.

The goal is to help a support professional quickly:

- Understand the customer's main issue
- Identify sentiment and urgency
- Draft a clear and empathetic response
- Decide on the appropriate next step

The final response should always be reviewed by a human before being sent to the customer.

## How it works

The workflow uses a structured prompt to analyze an incoming customer message and return:

1. **Issue** — a short summary of the customer's problem
2. **Sentiment** — positive, neutral, frustrated, or urgent
3. **Priority** — low, medium, or high
4. **Suggested response** — a concise and empathetic customer-facing draft
5. **Next action** — a recommended action for the support professional

## Example

### Customer message

> I've tried resetting my password three times and I still can't log in. I need access for a meeting in an hour.

### AI-assisted analysis

**Issue:**  
Customer cannot access their account after multiple password reset attempts.

**Sentiment:**  
Frustrated / urgent

**Priority:**  
High

**Suggested response:**  
"I'm sorry you're having trouble getting back into your account, especially with a meeting coming up. Let's get this resolved as quickly as possible. Please confirm whether you're seeing an error message after the reset, and I'll help you with the next step."

**Next action:**  
Check the exact error message and escalate to the appropriate technical team if the standard recovery process does not resolve the issue.

## Core prompt

```text
You are a Customer Support Assistant.

Analyze the customer's message below and return:

1. Issue: summarize the problem in one sentence.
2. Sentiment: positive, neutral, frustrated, or urgent.
3. Priority: low, medium, or high.
4. Suggested response: write a concise, empathetic and professional response.
5. Next action: recommend the most useful next step for the support professional.

Rules:
- Do not invent company policies, refunds, timelines, or technical facts.
- If information is missing, clearly state what needs to be confirmed.
- Acknowledge the customer's concern before giving a solution.
- Keep the response human and easy to understand.
- Escalate safety, security, billing disputes, or specialist issues.

Customer message:
[PASTE CUSTOMER MESSAGE HERE]
```

## What I learned

This project helped me think about AI as more than a tool for generating text. I explored how clear instructions and structured outputs can turn AI into part of a repeatable customer support workflow.

I also learned the importance of keeping a human in the loop, especially when dealing with customer concerns where accuracy, empathy, and context matter.

## Future improvements

If I continued developing this project, I would:

- Connect the workflow to a ticketing system
- Add a customer support knowledge base
- Create more test scenarios
- Explore no-code automation
- Measure response quality and consistency

## Tools

- Generative AI
- Prompt design
- Customer Support workflow design
- Markdown
