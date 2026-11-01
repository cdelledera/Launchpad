# **Project Title:** Launchpad
**Team Members:** Christian, Jordan, Nick, Jerry  
**Category:** Social Media / Creator Tools  

---

## **1. PROBLEM STATEMENT**
Many aspiring content creators struggle to figure out what actually makes a video go viral on platforms like TikTok and YouTube Shorts. Because they lack clear data on what hooks and pacing work best, they end up guessing, which leads to wasted production time and inconsistent audience growth.

## **2. SOLUTION**
Launchpad is an analytics app that evaluates video concepts and past successes to generate an actionable **"Viral Score."** Instead of just showing stats after a video is posted, it helps creators plan their next move. The core MVP features are the Viral Score, a Content Organizer, and a Script Analyzer. To comply with platform API terms, Launchpad will not scrape public data. Instead, it acts as a coach for the creator's own channel. Users will securely connect their channels via OAuth to pull their own real retention data.

## **3. TARGET MARKET**
Aspiring and mid-tier content creators on YouTube and TikTok. While there are millions of amateur creators globally, our initial target is a cross-section of active amateur creators. [Add Citation here] However, because only 4% of roughly 50 million creators earn over $100K a year (Goldman Sachs), most of our users will be highly price-sensitive. Therefore, our immediate testing target is 5 active campus creators who will consent to connect their channels, providing the historical data needed to train the algorithm.

## **4. WHY IT IS VALUABLE**
Launchpad takes the guesswork out of content creation. By analyzing what works before a creator spends hours filming and editing, we save them significant research time. More successful videos mean faster channel growth and better potential ad revenue.

## **5. HOW YOU WILL MAKE MONEY**
We will use a **freemium monthly subscription model** with two premium tiers. The free tier allows a few basic video analyses per month. The **Basic Tier ($5/month)** unlocks unlimited Viral Scores and standard analytics. The **Pro Tier ($10/month)** adds advanced cross-platform trend tracking and bulk video analysis. 

**Initial Market Math:** If we capture just **2%** of our 100,000 cross-niche target, that gives us **2,000 active premium users**. Assuming a realistic split of 70% on the Basic tier (1,400 users x $5 = $7,000) and 30% on the Pro tier (600 users x $10 = $6,000), that generates **$13,000 in monthly recurring revenue**.

## **6. MVP FEATURES**
- **Viral Score:** An algorithm that scores a draft video concept against the creator's own historical median views.
- **Content Organizer:** A workspace where creators can plan and track video ideas.
- **Script Analyzer:** Evaluates uploaded text scripts for hook length and time-to-payoff to highlight structural weaknesses before filming.
  
## **7. TIMELINE AND DIVISION OF WORK**
**Week 1:** 
- **Christian:** Research YouTube Analytics API OAuth flow and set up backend structure.
- **Jordan:** Recruit 5 campus creators to connect their channels (consent/data plan).
- **Nick:** Draft the baseline algorithm and logic for the scoring system.
- **Jerry:** Wireframe the initial UI and dashboard layout.

**Week 2:** 
- **Christian:** Build the backend logic for the Content Organizer.
- **Jordan:** Backtest the Viral Score against the creators' last 30 videos.
- **Nick:** Refine the scoring math based on the results of Jordan's testing.
- **Jerry:** Code the front-end (HTML/CSS) for the Content Organizer.

**Week 3:** 
- **Christian:** Integrate the Script Analyzer backend with the front-end UI.
- **Jordan:** Test the overall user flow and polish the user experience.
- **Nick:** Debug the backend scoring code and handle edge cases.
- **Jerry:** Design the visual output for how the Viral Score is displayed to the user.


## **8. TEAM ROLES AND RESPONSIBILITIES**

**Christian, Lead Programmer**
- Design the initial architecture. Program the OAuth data pulling and handle backend debugging.
- Program the API data pulling and handle backend debugging.
- *Estimated share of the codebase: 30%*

**Jordan, QA Tester and Data Lead**
- Manage creator onboarding and OAuth consent. Test the integration and backtest score accuracy against historical video data.
- Test the integration and validate the score accuracy against real videos.
- *Estimated share of the codebase: 30%*

**Nick, Researcher and Algorithm Design**
- Research current virality trends on short-form platforms.
- Design the backend logic and weighting for the scoring algorithm using statistical backtesting.
- *Estimated share of the codebase: 20%*

**Jerry, UI/UX Designer**
- Design the app's visual layout and navigation.
- Code the front-end implementation and ensure interface efficiency.
- *Estimated share of the codebase: 20%*

*(30 + 30 + 20 + 20 = 100%)*

## **9. VIABILITY: HOW WE WILL PROVE THIS WORKS**

**User Testing:**
- We will recruit 5 campus creators who will connect their channels via OAuth. Their consent is our data plan.
- **Ask:** "Does this score accurately reflect your past analytics? Which premium tier ($5 or $10) would you subscribe to?"
- Backtest: We will test if our score ranks a creator's last 30 videos better than chance, reporting the correlation coefficient (Spearman's ρ).

**Competitive Analysis (Checked October 2026):**
- Tools like **VidIQ ($19.99/mo)** and **TubeBuddy ($15/mo)** are strictly focused on YouTube SEO. OpusClip offers a generalized 'Virality Score' (0-99). Native analytics only show data after publication.
- Native **YouTube** and **TikTok** analytics only show data *after* a video is published.
- **Our difference:** Launchpad stands out because it does not claim to predict global virality. Instead, it evaluates a creator's draft against their own historical performance using retention data they own.
  
## **10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS**

**Phase 1 (This semester):** 
- **Goal:** MVP desktop/web app with 3 to 5 early users (campus creators) and 3 core features.
- **Technical:** OAuth integration and local file/simple database storage.
- **Revenue:** Free, to build a base and train the scoring algorithm.

**Phase 2 (6 months out):** 
- **Goal:** Expand to **5,000 to 10,000 users** by marketing broadly across all popular content categories.
- **Technical:** Move to a hosted cloud database and expand official YouTube Analytics API usage.
- **Revenue:** Launch the $5 and $10 premium tiers to establish monthly recurring revenue.

**Phase 3 (12 months out):** 
- **Goal:** Scale to **50,000 to 100,000+ users** by capturing a larger share of the global creator economy and launching mobile clients.
- **Technical:** Dedicated servers for heavier AI processing and automated trend alerts.
- **Revenue:** Introduce one-time token packs for bulk creators and agency tiers.

## **11. SOURCES AND REFERENCES**
- **Goldman Sachs Creator Economy Report:** Projecting $480B by 2027 (and the 4% earning over $100K stat).

- **YouTube Analytics API Documentation:** For OAuth and retention data rules.

- **OpusClip & VidIQ/TubeBuddy Pricing Pages:** Checked October 2026 for competitor feature/pricing baselines.

- **Salganik, Dodds and Watts, Science (2006):** 14,341-person experiment showing that social influence makes hits less predictable, supporting our pivot away from "global virality prediction.

