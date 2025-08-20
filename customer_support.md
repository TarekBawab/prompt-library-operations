# Customer Support — Ready-to-Use Prompts

## Variables (replace these before using)
- {{customer_name}}
- {{date_time}}
- {{item}}
- {{order_number}}
- {{refund_amount}}

---

## Style Guide
- Tone: Warm, calm, plain language  
- Length: 80–120 words  
- Approach: Apologize → Confirm Issue → Provide Solution → Invite Back  
- Avoid: Corporate jargon, defensive wording, over-explaining  

---

## 1) Reply to an unhappy customer (refund offered)

**Prompt**
“Act as a support rep. Draft a reply to a customer whose order was missing {{item}} on {{date_time}}. Keep it under 120 words, include an apology, confirm refund of {{refund_amount}}, and offer a replacement on next visit.”

**Example Output**
Hi {{customer_name}},  
I’m so sorry your {{item}} was missing from your order on {{date_time}}. I’ve processed a refund of {{refund_amount}} to your card. On your next visit, please mention this message and we’ll gladly replace the item. Thank you for letting us make it right.  

---

## 2) Turn a 1-star review into a re-visit

**Prompt**
“Write a friendly 3-sentence response inviting {{customer_name}} to DM their order number {{order_number}}. Offer a comped meal on their next visit. Keep tone warm, no corporate jargon.”

**Example Output**
Hi {{customer_name}},  
We’re sorry your experience wasn’t what you expected. If you could DM us your order number ({{order_number}}), we’ll make sure to credit your next visit with a complimentary meal. We’d love a chance to welcome you back.  

---

## 3) Daily inbox triage (summaries + tags)

**Prompt**
“Summarize today’s 25 customer emails into a table with columns: Topic, Urgency (High/Med/Low), Action Owner, Due Date, Suggested Reply Template.”

**Example Output**
| Topic             | Urgency | Action Owner | Due Date | Suggested Reply         |
|-------------------|---------|--------------|----------|-------------------------|
| Missing order     | High    | Shift Lead   | Today    | Refund + apology        |
| Late delivery     | Med     | Ops Manager  | Tomorrow | Credit + reassurance    |
| Compliment staff  | Low     | Team Lead    | This week| Thank-you response      |

---

## Do / Don’t
**Do:**  
- Apologize clearly  
- Confirm what action was taken (refund, credit, replacement)  
- Keep responses short and respectful  
- Invite customer to return  

**Don’t:**  
- Shift blame to the customer  
- Make promises you can’t keep  
- Use robotic or corporate phrases (“valued guest,” “sincerely regret the inconvenience”)  

---

## Tags
#refund #review_reply #customer_support #operations #templates
