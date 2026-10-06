# **Project Title:** Launchpad
**Team Members:** Christian, Jordan, Nick, Jerry  
**Category:** Social Media / Creator Tools  

---

## **1. PROBLEM STATEMENT**
Many aspiring content creators struggle to figure out what actually makes a video go viral on platforms like TikTok and YouTube Shorts. Because they lack clear data on what hooks and pacing work best, they end up guessing, which leads to wasted production time and inconsistent audience growth.

## **2. SOLUTION**
Launchpad is an analytics app that evaluates video concepts and past successes to generate an actionable **"Viral Score."** Instead of just showing stats after a video is posted, it helps creators plan their next move. The core MVP features are the Viral Score, a Content Organizer, and a Video Analyzer.

## **3. TARGET MARKET**
Aspiring and mid-tier content creators on YouTube and TikTok. While there are millions of amateur creators globally, our initial target is a cross-section of about **100,000 active amateur creators** spanning all niches (such as lifestyle, comedy, gaming, and education) who are actively trying to reach platform monetization thresholds.

## **4. WHY IT IS VALUABLE**
Launchpad takes the guesswork out of content creation. By analyzing what works before a creator spends hours filming and editing, we save them significant research time. More successful videos mean faster channel growth and better potential ad revenue.

## **5. HOW YOU WILL MAKE MONEY**
We will use a **freemium monthly subscription model** with two premium tiers. The free tier allows a few basic video analyses per month. The **Basic Tier ($5/month)** unlocks unlimited Viral Scores and standard analytics. The **Pro Tier ($10/month)** adds advanced cross-platform trend tracking and bulk video analysis. 

**Initial Market Math:** If we capture just **2%** of our 100,000 cross-niche target, that gives us **2,000 active premium users**. Assuming a realistic split of 70% on the Basic tier (1,400 users x $5 = $7,000) and 30% on the Pro tier (600 users x $10 = $6,000), that generates **$13,000 in monthly recurring revenue**.

## **6. MVP FEATURES**
- **Viral Score:** An algorithm that scores a video link or concept based on current platform trends.
- **Content Organizer:** A workspace where creators can plan and track video ideas.
- **Video Analyzer:** Extracts basic stats (like pacing and keyword usage) from successful videos to highlight why they performed well.

## **7. TIMELINE AND DIVISION OF WORK**
**Week 1:** 
- **Christian:** Research YouTube/TikTok API data pulling and set up backend structure.
- **Jordan:** Define the specific social media metrics needed for the Viral Score.
- **Nick:** Draft the baseline algorithm and logic for the scoring system.
- **Jerry:** Wireframe the initial UI and dashboard layout.

**Week 2:** 
- **Christian:** Build the backend logic for the Content Organizer.
- **Jordan:** Test the Viral Score manually against 50 real YouTube Shorts and TikToks.
- **Nick:** Refine the scoring math based on the results of Jordan's testing.
- **Jerry:** Code the front-end (HTML/CSS) for the Content Organizer.

**Week 3:** 
- **Christian:** Integrate the Video Analyzer backend with the front-end UI.
- **Jordan:** Test the overall user flow and polish the user experience.
- **Nick:** Debug the backend scoring code and handle edge cases.
- **Jerry:** Design the visual output for how the Viral Score is displayed to the user.


## **8. TEAM ROLES AND RESPONSIBILITIES**

**Christian, Lead Programmer**
- Design the initial architecture and AI integration for the main features.
- Program the API data pulling and handle backend debugging.
- *Estimated share of the codebase: 30%*

**Jordan, QA Tester and Data Lead**
- Research data collection limits on YouTube and TikTok.
- Test the integration and validate the score accuracy against real videos.
- *Estimated share of the codebase: 30%*

**Nick, Researcher and Algorithm Design**
- Research current virality trends on short-form platforms.
- Design the backend logic and weighting for the scoring algorithm.
- *Estimated share of the codebase: 20%*

**Jerry, UI/UX Designer**
- Design the app's visual layout and navigation.
- Code the front-end implementation and ensure interface efficiency.
- *Estimated share of the codebase: 20%*

*(30 + 30 + 20 + 20 = 100%)*

## **9. VIABILITY: HOW WE WILL PROVE THIS WORKS**

**User Testing:**
- We will interview 3 fellow Pace University students who actively create YouTube and TikTok content across different genres.
- **Ask:** "Does this score accurately reflect your past analytics? Which premium tier ($5 or $10) would you subscribe to?"
- We will run their past videos through our system to see if our Viral Score accurately predicts which ones actually performed best.

**Competitive Analysis (Checked October 2026):**
- Tools like **VidIQ** and **TubeBuddy** are powerful, but their paid tiers cost $30+ a month and are strictly focused on YouTube SEO (keywords and tags).
- Native **YouTube** and **TikTok** analytics only show data *after* a video is published.
- **Our difference:** Most existing tools rely heavily on search keywords, which only helps specific search-based niches (like tech tutorials). Launchpad stands out because it evaluates universal engagement metrics, like visual pacing, script structure, and hook strength. This means it can accurately predict virality for any niche based on audience psychology rather than just SEO tags.

## **10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS**

**Phase 1 (This semester):** 
- **Goal:** MVP desktop/web app with **100 to 500 early users** and 3 core features.
- **Technical:** Basic web scraping and local file/simple database storage.
- **Revenue:** Free, to build a base and train the scoring algorithm.

**Phase 2 (6 months out):** 
- **Goal:** Expand to **5,000 to 10,000 users** by marketing broadly across all popular content categories.
- **Technical:** Move to a hosted cloud database and implement official YouTube/TikTok APIs.
- **Revenue:** Launch the $5 and $10 premium tiers to establish monthly recurring revenue.

**Phase 3 (12 months out):** 
- **Goal:** Scale to **50,000 to 100,000+ users** by capturing a larger share of the global creator economy and launching mobile clients.
- **Technical:** Dedicated servers for heavier AI processing and automated trend alerts.
- **Revenue:** Introduce one-time token packs for bulk creators and agency tiers.

## **11. SOURCES AND REFERENCES**
- **YouTube Data API v3 Documentation** (Checked October 2026 for video data pulling limits).
- **TikTok for Developers Portal** (Checked October 2026 for research API access).
- **VidIQ Pricing Page** (Checked October 2026 for competitor pricing baselines).
- **Interviews:** 3 student content creators (Used to establish workflow timing and willingness to pay).
