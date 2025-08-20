# Inventory Checks — Ready-to-Use Prompts

## Variables
- {{date_range}}
- {{item_name}}
- {{variance_percent}}
- {{supplier_name}}

---

## Style Guide
- Tone: Professional but simple (for staff use)  
- Output: Clear tables or bullet points  
- Focus: Action steps (Count, Waste Log, Supplier Follow-up)  

---

## 1) Daily variance scan (CSV → actions)

**Prompt**
“From this CSV of inventory vs sales for {{date_range}}, flag any item with >{{variance_percent}} variance. Output a list with: Item, Variance %, Suspected Cause, Action (Count / Waste Log / Supplier).”

**Example Output**
| Item           | Variance % | Suspected Cause | Action      |
|----------------|------------|-----------------|-------------|
| Burger Buns    | 12%        | Over-portioning | Count       |
| Cheese Slices  | 10%        | Waste           | Waste Log   |
| Soda Syrup     | 9%         | Supplier Error  | Supplier    |

---

## 2) Weekly supplier message

**Prompt**
“Draft a concise email to {{supplier_name}} summarizing shortages, quality issues, and delivery timing. Use bullet points, request adjustments for next order.”

**Example Output**
Hi {{supplier_name}},  

Quick update on this week’s deliveries:  
- 3 cases of buns short (8/15)  
- Cheese blocks arrived damaged (8/17)  
- Soda syrup delayed by 1 day  

Please adjust and confirm resolution for the next shipment.  
Thank you.  

---

## 3) Waste pattern analysis

**Prompt**
“Analyze the last {{date_range}} waste logs. Identify top 3 items by dollar loss and suggest one operational change per item.”

**Example Output**
1. Fries — $120 loss → Reduce batch size during slow hours  
2. Nuggets — $95 loss → Check fryer timers; consistent overcooking  
3. Lettuce — $60 loss → Store at correct humidity, rotate daily  

---

## Do / Don’t
**Do:**  
- Always output in tables or clear lists  
- Suggest specific, small fixes  
- Call out supplier errors separately  

**Don’t:**  
- Give vague advice (“be more careful”)  
- Ignore dollar impact  
- Blame staff without suggesting training  

---

## Tags
#inventory #waste #supplier #operations #templates
