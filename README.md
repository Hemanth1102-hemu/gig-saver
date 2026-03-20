AI-Powered Income Protection for Delivery Partners

Problem Statement :
Delivery partners are essential to urban life. They make sure that food, groceries, and other vital goods reach millions daily. However, their income is very vulnerable.  

Heavy rain  
Extreme heat  
Pollution  
Unexpected disruptions  
These factors can completely halt their work, leading to a 20 to 30 percent income loss each month. Yet, there is no organized financial protection for them.

A Real Story (Persona)  
Imagine this.  
It’s 9 PM.  
Heavy rain is pouring. Roads are flooded. Visibility is almost nonexistent.  

Ravi, a 26-year-old delivery partner, sits on his bike looking at his phone.  

He hasn't completed any orders today.  

If he stays home, he earns nothing.  
If he goes out, he risks:  

Road accidents  
Falling sick  
Dangerous working conditions  
But he chooses to go anyway. Missing even one day means:  

Less food for his family  
Difficulty paying rent  
Financial instability  
He earns about ₹800 a day. Missing just two or three days a week can significantly reduce his income.  
And today?  

There is no system in place to protect him from these unavoidable risks.

Our Solution  
We propose an AI-powered parametric insurance platform that:  
Detects unsafe working conditions  
Verifies whether the delivery partner is unable to work  
Automatically calculates income loss  
Instantly compensates eligible claims  
A system designed for people like Ravi.  

Weekly Premium Model (Dynamic but Fair)  
Delivery partners earn daily or weekly, not monthly. So our insurance model follows a weekly subscription cycle.  

Why Weekly?  
It matches the earning patterns of gig workers.  
It keeps premiums affordable.  
It allows for risk-based adjustments.  

How Premium is Calculated  
Weekly Premium = f(  
    Avg Weekly Income,  
    Location Risk,  
    Historical Weather Patterns,  
    AI Risk Score  
)  

Dynamic Pricing  
High-risk conditions mean a slightly higher premium.  
Low-risk conditions lead to a lower premium.  
Pricing adjusts intelligently to the environment.  

Premium Lock Mechanism (Very Important)  
Once a user pays the weekly premium, the price is locked for seven days.  

Mid-Week Risk Change Scenario  
Example:  
User pays premium on Monday.  
Heavy rain occurs on Wednesday.  
System behavior:  
The premium does not change mid-week.  
Coverage remains active.  
Claims are still allowed.  

When Does Premium Change?  
Premium is recalculated only at the start of the next week.  

Why This Approach?  
It ensures fairness.  
It builds trust.  
It prevents sudden price changes.  
It aligns with real-world insurance systems.  

Parametric Triggers (Core Innovation)  
What are Parametric Triggers?  
Automatic conditions that trigger payouts without manual claims.  

Triggers Used  
Rainfall exceeds a threshold.  
Temperature exceeds 42°C.  
AQI exceeds 300.  
External disruptions (curfews, outages).  

Problem with Traditional Parametric Models  
They assume "bad weather means no work."  
But in reality, some delivery agents still choose to work.  

Our Improved Approach  
We combine:  
Parametric Trigger and User Activity Validation.  

Final Claim Logic  
IF (Severe Condition Detected)  
AND (User Activity = Low or Zero),  
Then Trigger Claim.  

Why This Matters  
It prevents unnecessary payouts.  
It ensures fairness.  
It reduces fraud.  
It reflects real-world behavior.  

AI/ML Integration Plan  
Our system is designed to evolve into an intelligent decision-making platform.  
1. AI-Based Premium Calculation  
AI analyzes:  
Location risk  
Weather history  
Income patterns  
Disruption frequency  
Output: Personalized weekly premium.  
2. Risk Prediction Model  
Inputs:  
Weather forecasts  
Environmental data  
Outputs:  
Risk score (Low, Medium, High)  
Helps predict income loss, adjust pricing, and alert users.  
3. Fraud Detection  
AI detects:  
Fake inactivity  
GPS spoofing  
Duplicate claims  
Using:  
Behavioral analysis  
Activity tracking  
Location validation.  
4. Future Scope  
Predictive alerts (“High risk tomorrow”).  
Personalized insurance plans.  
Platform integrations (Swiggy/Zomato APIs).  

Why Web Platform?  
We chose a web-based platform because:  
No installation is required.  
Development is faster, making it ideal for this project .  
It is accessible across devices.  
Demonstrating it for judges is easy.  

Tech Stack  :
Frontend  
React.js  
Tailwind CSS  
Backend  
Node.js / Flask  
Database  
MongoDB / Firebase  
APIs  
Weather API (OpenWeather / mock)  
Traffic and platform APIs (simulated)  
Payments  
Razorpay Test Mode / Mock UI  

Development Plan (Phase 1)  
Core Features  
User Authentication  
Dashboard (income, risk, coverage)  
AI Risk Indicator (mock logic)  
Weekly Premium Calculation  
Activity Tracking (Active/Inactive)  
Parametric and Behavior-Based Claim Trigger  
Claim Simulation  
Basic Fraud Detection.  

Demo Features  
Simulate Rain  
Toggle Activity  
Auto claim trigger  
Instant payout.  

Payout Calculation  
Payout = Avg Daily Income × Affected Days × Coverage %  
Example:  
₹800/day  
2 days lost  
80% coverage  
Payout = ₹1280.  

Key Innovations  
Parametric and Behavioral Insurance Model  
Weekly subscription tailored for gig workers  
AI-driven pricing and fraud detection  
Instant claims with zero paperwork.  

Impact  
This solution is not just about insurance.  
It is about:  

Financial stability  
Worker safety  
Human dignity  
For millions of delivery partners who take risks every day.  

Demo Plan  
Show dashboard  
Simulate bad weather  
Keep user active → No payout  
Switch to inactive → Auto payout.  

Final Note :
The people who keep our lives running should not have to risk theirs just to earn a living.
