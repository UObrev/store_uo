
# 📍 Retail.AI Booth -- at the store frontline

## CS Zone: First Point of Contact  
At the **Customer Service entry point**, this booth becomes the launchpad for the in-store customer journey—contributing to engagement, upsell opportunities, and long-term satisfaction.

---

## 🧩 Challenges at the Customer Service Frontline

- **Lack of Journey Planning Tools**  
  Customers with complex shopping lists often seek optimized in-store routes. Currently, CS staff can only give general directions, not a tailored route.

- **Upsell Opportunities Missed**  
  While managers possess deep upselling experience, CS staff may lack tools to leverage that knowledge. With smart prompts, early-trip upsell engagement can generate qualified leads, increase revenue, and improve customer outcomes.

- **Q&A Bottlenecks**  
  With lean or flex staffing, CS staff are often pulled into product Q&A roles. Incorrect or incomplete answers risk revenue loss and customer dissatisfaction.

---

![retail.ai booth](schematic_line_drawing.png)

## 🤖 What is the Retail.AI Booth?

A compact AI-powered station designed to enhance staff-customer interaction at the start of the shopping experience.

### Features:
- Touchscreen computer + keyboard  
- Guest Wi-Fi connection only  
- Local printer (for Route Maps)  

---

## 🛠️ Staff Usage Prompt (Example)

```
Hi there! Want to see how our AI can map out the best solution for your project—right here in the store?
```

---

## 🏪 Store Customization

Settings are configured by store leadership to reflect local context:

- Weekly promotional focus  
- Local building code rules  
- Weather-based suggestions (e.g., wildfire prep)  
- Region-specific upsell strategies  

#### Example (Store_Settings.json):
```json
{
  "weekly_promos": [
    {"sku": "100123456", "name": "4x4x8 Pressure-Treated Wood"},
    {"sku": "100456789", "name": "RYOBI 18V Cordless Drill Kit"}
  ],
  "weather_profile": {
    "condition": "hot_dry",
    "tips": ["UV-resistant stain", "corrosion-proof fasteners"]
  },
  "building_codes": {
    "fence_rules": "No permit for fences ≤ 6 ft unless in utility easement"
  },
  "upsell_prompts": [
    "Need help with solar lighting ideas?",
    "Looking for pro installers for your backyard fence?"
  ]
}
```

---

## 🧠 Prompt Wizard

- **Goal**: Help CS staff create optimized prompts for RetailAI (powered by LLMs like GPT-5).
- **How It Works**:
  - Chrome Extension interface  
  - Uses local settings for relevance  
  - Step-by-step UI for project workflows  
  - Generates AI-ready prompts

---

## 🗺️ From Text to Route Map

RetailAI generates detailed solutions. The assistant reformats them into printable **Route Maps**.

### Examples:
- [RouteMap--Fence Replacement](RouteMap_FenceReplace.md)  
- [RouteMap--Deck Build](RouteMap_DeckBuild.md)

💡 Optional: Offer booth visitors discount coupons with printed maps.

---

## 🧭 CS Staff Workflow

1. **Select Use Case**  
   - Type: New Build / Replacement / Renovation  
   - Category: Appliances, Garden, Patio, etc.

2. **Measure**  
   - Capture key dimensions and quantities.

3. **Text Input**  
   - List materials, structures to keep/remove, reuse options.

4. **Generate Prompt**  
   - Feed prompt to RetailAI system.

5. **Print & Review**  
   - Go over solution with customer  
   - Print Route Map and optional coupon

---

## 👤 Simon Chen — User Onboarding (UO) Program Specialist  
<img src="https://media.licdn.com/dms/image/v2/C5603AQH27wV2BY9YMA/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1636338982903?e=1756339200&v=beta&t=ZMYnUHe4BygYpMFHdyjttsYB0ZEifyZQawYvj3raww0" width="300" align="right">

career focus: Customer Engagement SaaS | UO Strategy

**Clients:** Pfizer, Roche, J&J, Eisai-Biogen  

📞 (858) 733-1029  
📧 presenter.simon@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hsienchen/) 

<br>
<br>
<br>

## 🎯 Past UO Works

🔗 DFC Website – Patient Recruitment

🔗 Lunch Bag CME – Physician Engagement