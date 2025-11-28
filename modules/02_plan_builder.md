> Change Log (2025-11-28)
> – Added simple guardrails for distance, theme diversity, budget, and travel-time buffers.
> – Added fallback rules for closed venues, bad weather, and missing lodging.
> – Updated day-building loop to include weather-safe and budget-aware choices.
> – Clarified output format for 4-block daily plans.

## **Module 2 — Plan Builder (Options → Days)**




Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:  
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event

Add simple guardrails:
- avoid long distances and repetitive themes  
- track daily budget; switch to free/low-cost if needed  
- insert realistic travel-time buffers  
- fallback rules: closed venues, bad weather, missing lodging → choose nearest viable alternative

Output: a clear 4-block day plan with notes on timing, cost, and travel.
---
