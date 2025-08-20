# Scheduling — Ready-to-Use Prompts

## Variables
- {{employee_availability}}
- {{shift_time}}
- {{coverage_gap}}
- {{forecast_sales}}

---

## Style Guide
- Tone: Neutral, planning-oriented  
- Output: Tables or short text templates  
- Goal: Fairness + coverage + efficiency  

---

## 1) Build a fair schedule from availability

**Prompt**
“Create a weekly schedule from this availability: {{employee_availability}}. Balance hours, avoid clopens, ensure 2 closers nightly. Output as a table.”

**Example Output**
| Employee | Mon | Tue | Wed | Thu | Fri | Sat | Sun | Hours |
|----------|-----|-----|-----|-----|-----|-----|-----|-------|
| Alice    | 9-5 | Off | 9-5 | Off | 9-5 | 12-8| Off | 32    |
| Bob      | Off | 12-8| Off | 12-8| 12-8| Off | 12-8| 32    |

---

## 2) Call-out coverage text templates

**Prompt**
“Draft 3 SMS templates to quickly find coverage for {{shift_time}}. Keep short, friendly, yes/no reply.”

**Example Output**
1. “Hey team, need coverage tonight {{shift_time}}. Anyone available? Reply YES.”  
2. “Last minute call-out for {{shift_time}}. Can someone pick it up? Reply YES if free.”  
3. “Coverage needed {{shift_time}}. Overtime eligible. Reply YES to confirm.”  

---

## 3) Forecast-based staffing hint

**Prompt**
“Given {{forecast_sales}}, suggest ideal # of cashiers, cooks, and runners per daypart. Output in table.”

**Example Output**
| Daypart   | Cashiers | Cooks | Runners |
|-----------|----------|-------|---------|
| Breakfast | 1        | 1     | 0       |
| Lunch     | 2        | 2     | 1       |
| Dinner    | 2        | 3     | 1       |

---

## Do / Don’t
**Do:**  
- Balance fairness and coverage  
- Provide clear tables  
- Keep text templates short  

**Don’t:**  
- Schedule clopens (close + open next day)  
- Overload the same employee every weekend  
- Write long text messages  

---

## Tags
#scheduling #coverage #forecast #operations #templates
