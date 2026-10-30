# Smart India Hackathon Workshop
# Date:30.10.2026
## Reference Number:26008136
## Name:Deepshika.S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
1. Detailed explanation of the proposed solution:
Our solution, KrishiSetu, is an integrated B2B2C digital marketplace operating as a progressive web app (PWA) to ensure low-bandwidth accessibility for rural farmers. The platform operates on a decentralized hub-and-spoke model.
• Farmer/FPO Side: Farmers or Farmer Producer Organizations (FPOs) list their harvest with expected yield dates, quality grades, and pricing.
• Buyer Side: Consumers, local retailers, and bulk buyers (hotels, processing units) place direct orders.
• Logistics Layer: Integrates local third-party logistics (3PL) providers and freelance transport drivers through a dynamic bidding engine.
• AI Engine: Analyzes historic regional market data to project upcoming demand trends and uses genetic algorithms to bundle multiple small farmer shipments heading along the same geographic route.
2. How it addresses the problem:
By establishing direct communication channels and automated smart contracts between FPOs and bulk buyers, the platform entirely removes the multi-tiered Arhatiya (middlemen) system. The AI-driven route optimization and load-pooling reduce deadhead miles for logistics providers, driving down transit costs. Farmers receive immediate, transparent digital receipts and higher profit margins, while consumers benefit from lower retail prices due to eliminated intermediary markups.
3. Innovation and uniqueness of the solution:
• Dynamic Cooperative Load-Pooling: Small-scale farmers rarely fill an entire truck. Our algorithm dynamically groups neighboring farmers' harvests bound for the same urban market into a single shared logistics trip.
• Predictive Harvest Matching: Instead of waiting for harvest to find buyers, the system uses historical buying patterns to pre-match FPO crops with bulk buyers 2-3 weeks before harvest, securing cash flow.
• Offline-First SMS/USSD Sync: For regions with poor cellular connectivity, critical tasks (crop listing, price confirmation) fallback to a synchronized USSD gateway.

## Technical Approach
1. Technologies to be used:
• Frontend Mobile/Web: React Native or Flutter (for cross-platform deployment), TailwindCSS.
• Backend & APIs: Node.js (Express) or FastAPIs (Python) for processing concurrent user requests.
• Database: PostgreSQL for structured relational data (users, orders, transactions); Redis for high-speed caching of live tracking data.
• AI/ML Stack: Python, scikit-learn, and Facebook Prophet (for regional demand forecasting); Google OR-Tools (for vehicle routing problem optimization).
• Cloud & Maps: AWS (EC2/S3) for hosting; OpenStreetMap API (Leaflet.js) to avoid high Google Maps API costs.
2. Methodology and process for implementation:
• Phase 1 (User Architecture): Define database schemas linking Farmers, FPOs, Buyers, and Logistics agents. Implement multi-tenant authentication.
• Phase 2 (Core Marketplace & AI): Build the bidding engine and train the predictive model using open-source historical crop yield data from Government portals (like Agmarknet).
• Phase 3 (Logistics Integration): Code the routing engine using OpenStreetMap coordinates to calculate optimized milk-run pickup paths.
• Phase 4 (Validation & Testing): Run simulations on mock data representing 50 farmers and 5 regional distribution centers to test load-pooling efficiency
IMAGE SUBMISSION:
![alt text](<SIH problem image.png>) 



## Feasibility and Viability
1. Analysis of the feasibility of the idea:
The solution leverages existing infrastructure (smartphones, rural digital literacy, localized logistics networks) making it highly feasible. FPOs already cluster farmers organizationally, which drastically reduces the friction of onboarding individual users.
2. Potential challenges and risks:
• Trust and Adoption: Farmers might be hesitant to leave traditional cash-in-hand middlemen relationships.
• Quality Standardization: Discrepancies between the crop quality listed online and the physical product delivered.
• Perishability during Transit: Logistics delays leading to spoiled inventory.
3. Strategies for overcoming these challenges:
• FPO Digital Promoters: Appoint and incentivize youth leaders within existing FPOs to manage listings and facilitate initial trust.
• Assured Micro-Grading Protocols: Provide basic digital image guidelines inside the app for quality sorting, verified by local FPO collection hubs before transit.
• Cold-Chain Integration & Escrow: Onboard refrigerated transit partners for highly perishable items; use an escrow-based payment system that releases funds to the farmer immediately upon successful digital quality validation by the buyer

## Impact and Benefits
1. Potential impact on the target audience:
• Farmers: Experience an estimated 25-30% increase in net income due to direct price discovery and reduced reliance on exploitative credit structures from middlemen.
• Bulk Buyers/Retailers: Secure fresh inventory directly at 15-20% lower procurement costs with predictable delivery timelines.
2. Benefits of the solution:
• Social: Empowers rural communities and strengthens FPOs, keeping wealth within agrarian ecosystems.
• Economic: Reduces overall food inflation in urban areas while boosting rural household disposable income.
• Environmental: Optimized transit routes drastically cut down carbon emissions per ton of food moved; faster logistics pipelines cut down post-harvest wastage and landfill organic decay.

## Research and References
1. Details / Links of the reference and research work:
• Government Data Source: Agmarknet Portal (agmarknet.gov.in) for daily crop arrivals and market price trends.
• Academic Literature: Research papers on the "Vehicle Routing Problem with Time Windows (VRPTW)" for logistics route optimization.
• Policy Reports: NITI Aayog reports on structural reforms in agricultural marketing and the role of FPOs in digital agriculture.

