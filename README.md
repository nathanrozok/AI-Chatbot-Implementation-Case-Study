# AI Chatbot Use Case – Jimmy's Auto LLC

## 🧠 Problem  
Jimmy’s Auto LLC needed to reduce customer service overhead while ensuring reliable support for a nationwide auto parts operation.

## 🎯 Goal  
Reduce customer service staffing by 27% within 6 months, save $565K in salaries, and expand online support coverage without compromising response quality.

## 💡 Solution  
Implemented an AI-powered chatbot trained on the most frequently requested 1,000 parts across 85 vehicle models. A human fallback system remained in place for complex or non-standard queries to preserve trust and accuracy.

## 🛠️ Scope & Feasibility
- Projected 100K chatbot inquiries annually.  
- Leveraged off-the-shelf NLP platform for rapid deployment.  
- Development + testing completed in 6–8 weeks.  
- Infrastructure scaled to support 1,000+ concurrent sessions.  

## 💰 Cost Breakdown
| Phase                      | Estimated Cost |
|---------------------------|----------------|
| Pre-Implementation        | $11,500        |
| Implementation            | $158,000       |
| Year 1 Operational Costs  | $162,000–$215,000 |

## 💵 Results (90 Days Post-Launch)
- $73K/month in realized salary savings by Month 3.  
- $94K/month in savings by Month 4 (full staffing adjustment).  
- 4% increase in sales attributed to accurate, immediate responses.  
- 40% of new customer inquiries routed through chatbot.  

## 🔍 Responsible AI Practices
- Limited chatbot scope to common, low-risk queries.  
- Real-time monitoring for hallucination and fallback triggers.  
- Weekly analysis of chat logs for continuous improvement.  
- Human agents retained for escalation, legal, and nuanced queries.  

## 🧠 PM Insights
- Prioritized gradual rollout to reduce operational risk.  
- Scoped feature set around business-critical use cases only.  
- Selected COTS (Commercial Off-The-Shelf) tech for speed, scalability, and reliability.  
- Continuous feedback loop through satisfaction surveys and support logs.  

## 📈 Scalability
Load-tested to handle >1,000 concurrent sessions. Stable performance observed during peak traffic and campaign pushes.

## 🔁 Chatbot Escalation Flow

graph TD

    A[Incoming Inquiry] --> B{Is it about a supported part?}
    
    B -- Yes --> C[NLP Classification]
    
    B -- No --> D[Escalate to Human]
    
    C --> E{Confidence > 80%?}
    
    E -- Yes --> F[Respond with Answer]
    
    E -- No --> G[Escalate]

This diagram illustrates the logic flow of the chatbot, from initial inquiry through classification, 
confidence scoring, and fallback to human support when needed. It helps ensure responsible, 
accurate AI responses while safeguarding edge cases.

📄 [Full Use Case Document](AI Chatbot Use Case Full Analysis)

---

📌 *Generic Case Study Summary for educational purposes developed by Nathan Rozok — AI Product Manager focused on building ethical, scalable AI solutions.*
