# Ai-whatsapp-sales-automation

PROJECT DETAILS
- Name: WhatsApp Sales Tracker
- One-line tagline: WhatsApp-to-Google-Sheets automation that extracts, categorises and logs team sales messages.
- Problem: SME sales teams often use WhatsApp groups to confirm sales to their managers. This makes sales hard to track, count and verify.
- Solution: The automation extracts incoming messages from the group, filters and categorises them by keyword, and logs them in an organised Google Sheet as "sales", "non-sales" or "waiting to be assessed".
- Tools used: Make.com, webhooks, Google Sheets, [add any others, e.g. JSON parsing, text parser, WhatsApp API provider, any LLM API]
- Scale or results: [e.g. ran 1,000 operations and processed 535 KB of data; add any real result such as time saved or number of messages processed]
- How the flow works, step by step: [e.g. 1. WhatsApp message arrives via webhook. 2. Text is parsed. 3. Keywords are matched. 4. Message is classified. 5. Row is added to the correct Google Sheet tab.]
- Keyword logic: [briefly describe how messages are classified, e.g. which words mean "sale" and what counts as "pending"]

STRUCTURE THE README WITH THESE SECTIONS
1. Title and one-line tagline
2. Overview: the problem it solves, in 2-3 sentences
3. How it works: a numbered step-by-step flow, plus a placeholder for a screenshot of the Make.com scenario canvas
4. Tech stack: a short list of the tools used
5. Example output: a placeholder for a screenshot of the Google Sheet with anonymised data
6. Results: scale, accuracy or time saved, only using the facts I provided above
7. Repository contents: explain the blueprint JSON file (how to import it into Make.com) and the screenshots folder
8. Future improvements: 3-4 realistic ideas that show engineering thinking, such as using an LLM to classify ambiguous messages instead of fixed keywords, adding error handling and logging, building a manager dashboard, or adding duplicate detection
9. Notes: a short line saying that all client data, webhook URLs and API keys have been removed or anonymised

RULES REGARDING THE PROMPT
- Keep it concise, clear and professional. No hype or filler.
- Do not invent features, results or numbers I haven't given you. Use [placeholders] for anything missing.
- Use plain British English.
- Use markdown formatting with headings, short bullet points and one numbered list.
  
<img width="1815" height="1010" alt="image" src="https://github.com/user-attachments/assets/2c765685-4409-413d-b7e8-2086fdcf6c35" />

# Link for Loom video and manager to see how the system works and where the data would be sent to #
https://www.loom.com/share/b7749f8972ec4a74ab7ca99919e22998

https://manager-dashboard-orcin.vercel.app/

Prompt skeleton:

[Order Ref]

[Full Address]

[Customer Name]

[Phone]

[Speed]mbps

price [Price]

DOI [DD/MM/YYYY] [am/pm]
