# Launchpad
Side Project
Project Title: Launchpad
Team Members: Christian, Jordan, Nick, Jerry
Category: Social Media

1. PROBLEM STATEMENT
Aspiring content creators treat social media algorithms like a black box, spending hours producing videos without knowing what actually drives engagement. Because they lack actionable, cross-platform data on hooks, pacing, and trends, they rely on guesswork, which leads to burnout and stagnant audience growth. 

2. SOLUTION
Launchpad is a web-based analytics dashboard that takes the guesswork out of content creation. Users submit a video link or concept, and the app analyzes the metadata to generate a "Viral Score." Core MVP features include a Viral Score generator, a Content Organizer for planning, and a Video Analyzer that breaks down what works.

3. TARGET MARKET
Aspiring and mid-tier independent content creators (YouTubers, TikTokers, Instagram Reels creators). According to a widely cited SignalFire report, over 50 million people consider themselves creators, but only about 2 million make a full-time living. Our target market is the 48 million "amateur" creators trying to break through the algorithm to reach monetization.

4. WHY IT IS VALUABLE
It transforms content creation from a guessing game into a data-driven process. Launchpad saves creators hours of manual trend research and helps them optimize their content formats before they spend hours filming and editing, directly increasing their chances of growing an audience and generating revenue.

5. HOW YOU WILL MAKE MONEY
Freemium model. The free tier allows users to run 3 basic video analyses and Viral Scores per month. The Premium tier is $10/month for unlimited Viral Score calculations, advanced AI trend insights, and unlimited use of the Content Organizer. 
Total addressable market: If we target just 1% of the 48 million amateur creators, that is 480,000 potential users. At a realistic 5% conversion rate to the premium tier (24,000 users), that generates $240,000 in monthly recurring revenue. Users can also buy one-off token packs for extra AI scraping limits.

6. MVP FEATURES
- Viral Score Generator: Analyzes a submitted video link against current engagement metrics to produce a 1-to-100 viability score.
- Video Analyzer: Extracts keywords, length, and engagement statistics from a provided link to highlight successful patterns.
- Content Organizer: A planning board where creators can track their video ideas from concept to published.

7. TIMELINE AND DIVISION OF WORK
Week 1: 
- Christian: Backend architecture and basic data scraping logic. 
- Jordan: Define viral score metrics and research API data limits. 
- Nick: Design baseline algorithms for the Video Analyzer. 
- Jerry: UI wireframes and web front-end repository setup.

Week 2: 
- Christian: Integrate video analyzer backend with the web interface. 
- Jordan: Test viral score accuracy by running 50 known videos through the system. 
- Nick: Refine the scoring algorithm based on Jordan's test data. 
- Jerry: Build and style the Content Organizer UI.

Week 3: 
- Christian: Finalize API endpoints and handle edge-case bug fixing. 
- Jordan: Conduct user testing with 3 student creators and gather feedback. 
- Nick: Compile testing data, research competitors, and draft presentation slides. 
- Jerry: Polish CSS, finalize user navigation, and ensure visual responsiveness.


8. TEAM ROLES AND RESPONSIBILITIES
Christian, Lead Programmer
- Backend system architecture and API integration
- Develop core data scraping and AI integration scripts
- Code reviews and technical bug fixing
- Estimated share of the codebase: 30%

Jordan, QA Tester and Data Lead
- Research data collection methods and platform API limits
- Test AI integration and validate the Viral Score against real-world video data
- Quality assurance and edge-case testing
- Estimated share of the codebase: 25%

Nick, Research and Algorithm Design
- Research virality factors and current social media trends
- Design the scoring logic and algorithm weights for the Video Analyzer
- Presentation preparation and competitive research
- Estimated share of the codebase: 25%

Jerry, UI/UX Designer
- Design the web app's layout, dashboard, and navigation flow
- Front-end implementation (HTML/CSS/JS)
- Survey UX efficiency and adjust the interface based on testing
- Estimated share of the codebase: 20%

(30 + 25 + 25 + 20 = 100%)

9. VIABILITY: HOW WE WILL PROVE THIS WORKS
User Testing:
- Interview 3 student content creators (e.g., campus vloggers or tech reviewers) during development.
- Ask: "Does this score accurately reflect your past analytics? Would you pay $10/month for this?"
- Have 1 creator use the Content Organizer to plan their content for a week.

Competitive Analysis:
- TubeBuddy and VidIQ: Both offer robust YouTube analytics and SEO tools with free and paid tiers (ranging from $3 to $50+/month). 
- Our difference: Those tools are heavily YouTube-centric and cluttered with deep SEO metrics. Launchpad is designed to be cross-platform (TikTok, Reels, Shorts) and focuses purely on an actionable, easy-to-understand "Viral Score" and organization, rather than overwhelming a beginner with spreadsheets. 
- Honest limitation: A massive YouTube channel with a dedicated SEO manager is better served by VidIQ's enterprise tools.

Success Metrics:
- A tester successfully uses the Content Organizer and reports time saved on research.
- The Viral Score accurately predicts the top-performing video out of a creator's past three uploads during our testing phase.
- Testers state they would pay a $10 monthly subscription for unlimited access.

10. SCALABILITY: ROADMAP FROM MVP TO 100K USERS
Phase 1 (This semester): 
- MVP web app with basic web scraping and local/simple database storage.
- Supports individual creator tracking.
- Target: 100-200 early users.
- Revenue: Free, to build a user base and train the scoring algorithm.

Phase 2 (Months 3 to 6): 
- Move to robust cloud hosting, add official API integrations (YouTube/TikTok), and launch the multi-platform dashboard.
- Target: 500 to 1000 users.
- Revenue: Introduce the $10/month premium tier. 

Phase 3 (Months 6 to 12): 
- Fully trained custom ML models for trend prediction, automated video hook generation, and a collaborative team tier.
- Target: 2,000 to 5,000 users.
- Revenue: $10/month individual tier, plus a $99/month agency/team tier.

Technical Progression:
- Phase 1: Basic web app, simple database, lightweight scraping scripts.
- Phase 2: Cloud-hosted relational database, official API implementation, secure user authentication.
- Phase 3: Service-based backend, microservices architecture to handle heavy AI processing loads, and mobile client apps.

11. SOURCES AND REFERENCES
- SignalFire Creator Economy Report (Used for total addressable market counts of amateur vs. professional creators).
- VidIQ and TubeBuddy pricing pages
- Developer Documentation: YouTube Data API and TikTok Research API (Used for data limit research).
- Interviews: 3 local student content creators (Used for viability testing and workflow timing).
