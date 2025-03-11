# FINTECH-DATA-ANALYSIS

## TABLE OF CONTENT
- [Project Overview](#Project-Overview)
- [Key Objectives:](#Key-Objectives)
- [Tools Used](#Tools-Used)
- [Workflow](#Workflow)
- [Insights](#Insights)
- [Recommendations](#Recommendation)
- [Challenges](#Challenges)

### PROJECT OVERVIEW
This project analyzes Nigeria’s FinTech market to provide data-driven insights for a startup looking to refine its product offerings, pricing strategy, target customer segmentation, and marketing approach. The goal is to understand user preferences, financial behavior, and economic status to help the startup optimize its services and reach the right audience effectively.

### TOOLS USED
**Data Processing & Analysis**
- Python (Pandas, NumPy): Data generation and manipulation

**Data Visualization & Interpretation**
- Power BI: Interactive dashboards for market trends, pricing structures, and customer segmentation.

**Research Tools**
- CBN & NBS Reports: Official statistics on financial inclusion, income distribution, and digital finance adoption.
- Industry Research & FinTech Websites: Insights into services, pricing models, and consumer behavior from platforms like Flutterwave, Moniepoint, Paystack, OPay, Kuda, and Luno.

### WORKFLOW
**Research & Data Collection**
- Survey : Conducted a small survey to gather initial insights on:
 - Demographics (Age,Income Level).
 - Financial Literacy (Understanding of banking, investments, and budgeting).
 - Preferred FinTech Services (Mobile banking, digital payments, micro-loans).
 - Service Delivery Preferences (Self-service vs. agent banking).
 - CBN & NBS Reports: Used official financial inclusion data to ensure realistic income levels, banking adoption rates, and digital transaction 
 trends.
 - Industry Research & FinTech Websites → Analyzed pricing structures, services, and customer trends from leading Nigerian FinTech firms

**Data Generation & Processing**
- Dataset Creation (200,000 Rows): Based on survey insights and official statistics, a synthetic dataset was generated using Python (NumPy, Pandas).
- Realistic Data Distributions: Ensured accuracy in:
- Age Groups (Weighted toward middle-aged users for better representation).
- Income Levels (Aligned with Nigerian economic data).
- Financial Literacy (Classified as Low,Medium and High).
- Business Ownership Segments (Young Professionals, Urban Professionals, Small Business Owners, Rural Users).
- Service Preferences (Mobile App, Web Platform, or Agent Banking)

**Data Analysis & Visualization**
- Visualized trends and patterns using line charts, bar charts, pie chart etc.

### INSIGHTS
### 1. Companies and Their Products

- Digital payments and mobile banking are the most common fintech offerings.
- Blockchain-based companies (Binance, Luno, Roqqu, Flutterwave) are fewer in number.
- Micro-lending is a niche market with only a few players.
<img width="816" alt="Screenshot 2025-03-11 at 4 51 47 PM" src="https://github.com/user-attachments/assets/dbe965f9-25f8-443c-8f11-82563fd2a4fe" />

### 2. Preferred Products by Users
- Digital Payments (85K users) and Mobile Banking (82K users) are the most preferred FinTech products.
- Micro-Lending (20K users) and Blockchain (13K users) have significantly fewer users, suggesting lower adoption.
<img width="814" alt="Screenshot 2025-03-11 at 4 54 12 PM" src="https://github.com/user-attachments/assets/90cdf82e-2e40-4cf8-ba83-612c7165b016" />

### 3. Product Familiarity by Users
- Digital payments are the most well-known, with 43K experts and 25K novice users.
- Mobile banking has the highest novice user base (49K), indicating high adoption among beginners.
- Blockchain has the lowest user familiarity (6K experts, 1K novices).
<img width="815" alt="Screenshot 2025-03-11 at 4 56 45 PM" src="https://github.com/user-attachments/assets/4db8a713-a1bd-4e2c-8a2a-4e1262a56a26" />

### 4. Companies Ranked by Number of Users and Pricing Strategy
- OPay leads with 60K users.
- Moniepoint follows closely with 47K users.
- Kuda ranks third with 29K users.
- Flutterwave (18K) and Paystack (14K) hold mid-tier positions.
- FairMoney (9K) and PiggyVest (5K) are notable among value-based pricing fintechs.
- Smaller players like Roqqu and Luno have the lowest user base at 2K each.
- Competitive Pricing dominates, driving the largest user adoption.
<img width="821" alt="Screenshot 2025-03-11 at 4 58 48 PM" src="https://github.com/user-attachments/assets/327f68ca-6e96-4c64-b1ad-d77e2bc65605" />

### 5. Distribution of Pricing Strategies
The majority (90.45%) of FinTech companies use Competitive Pricing, while only 9.55% use Value-Based Pricing.
This suggests that most companies prioritize market competition over customer-perceived value.
<img width="815" alt="Screenshot 2025-03-11 at 5 00 02 PM" src="https://github.com/user-attachments/assets/5a7b45be-9bc6-4750-a108-8efddd70643f" />

### 6. Products and Their Fee Structures
- Digital Payments leads in the number of companies, with 86K using this product.
- 54K companies use a Flat Fee model.
- 32K use a Percentage Fee model.
- Mobile Banking follows with 81K companies.
- 45K use a Flat Fee model.
- 29K use a Percentage Fee model.
- 7K use a Subscription-Based model.
- Micro-Lending has 20K companies, all using a Flat Fee model.
- Blockchain has 11K companies, all using a Percentage Fee model.
- Flat Fee models dominate across fintech categories.
<img width="817" alt="Screenshot 2025-03-11 at 5 01 09 PM" src="https://github.com/user-attachments/assets/00524e2f-1ee0-4063-ba94-95f25e646e22" />

### 7. Gaps in Competitive Pricing
- Many FinTech companies offer competitive pricing, but only a few provide user benefits.
- Binance offers Trading Discounts, Kuda has Loyalty Rewards, while OPay and Roqqu provide Cashback.
- Several companies (Flutterwave, Interswitch, Luno, Moniepoint, Paystack) offer no additional user benefits.
<img width="757" alt="Screenshot 2025-03-11 at 5 02 03 PM" src="https://github.com/user-attachments/assets/8ed98738-2770-483e-8641-0a464ee50a3f" />

### 8. Gaps in Value-Based Pricing
- Several FinTech companies use a value-based pricing strategy, but their user benefits vary.
- Companies like CowryWise and PiggyVest offer free tools, while FairMoney provides cashback.
<img width="764" alt="Screenshot 2025-03-11 at 5 02 48 PM" src="https://github.com/user-attachments/assets/ea99d9c6-c1eb-46c9-bec5-a3f2020b2fad" />

### 10. Financial Literacy and Usage
- Young Urban Professionals have the highest number of fintech users (80K), with a majority having high financial literacy (56K) and medium literacy (24K).
- Urban Professionals have the same number of highly literate users (56K) but fewer medium-literate users (14K), totaling 70K.
- Small Business Owners have 30K users, with a more balanced split among financial literacy levels: 15K medium, 9K low, and 6K high.
- Rural Users have the lowest fintech usage (20K), with most having low financial literacy (16K) and very few having medium literacy (4K).
<img width="823" alt="Screenshot 2025-03-11 at 5 03 42 PM" src="https://github.com/user-attachments/assets/9728118d-04a9-4067-9e2a-eca570a39014" />

### 11. Users by Service Preference
- Mobile Apps are the most preferred service with 83K users.
- Web Platforms attract 54K users.
- Agent Banking is used by 34K users.
- Self-Service is the least preferred, with 29K users.
- Digital-first channels (Mobile & Web) dominate user preferences.
<img width="817" alt="Screenshot 2025-03-11 at 5 04 58 PM" src="https://github.com/user-attachments/assets/4af22bdd-2244-43c7-a147-295c07f4b68b" />

### 2. Users and Service Preference
- Young Urban Professionals (80K)
- Prefer Mobile Apps (48K users)
- Web Platforms (24K users)
- Agent Banking (8K users)
- Urban Professionals (70K)
- Mobile Apps (35K users)
- Web Platforms (21K users)
<img width="812" alt="Screenshot 2025-03-11 at 5 06 03 PM" src="https://github.com/user-attachments/assets/4057db98-94ea-4121-907d-012701be9da1" />

### 13. Income Level by Number of Users
- High-income users: 50.40% are Urban Professionals, while 49.60% are Young Urban Professionals.
- Middle-income users: 42.70% are Young Urban Professionals, followed by 27.92% Urban Professionals, 24.06% Small Business Owners, and 5.32% Rural Users.
- Low-income users: 57.02% are Rural Users, and 42.98% are Small Business Owners.
<img width="814" alt="Screenshot 2025-03-11 at 5 06 52 PM" src="https://github.com/user-attachments/assets/c5a3255e-6f2e-4015-a890-739dbe4c3bd6" />

### 14. Number of User by Location
Urban users (170.94K, 85.47%) form the overwhelming majority of FinTech users.
Rural users (29.06K, 14.53%) have significantly lower adoption.
<img width="782" alt="Screenshot 2025-03-11 at 5 07 32 PM" src="https://github.com/user-attachments/assets/7ad638fc-df35-44f0-8eb3-aba651694355" />

### 15. Age Group by Number of Users
- Young Adults (94K users) form the largest segment of FinTech users.
- Adults (71K users) are the second-largest group.
- Middle-Aged (21K users) and Aged (14K users) have significantly lower adoption.
<img width="819" alt="Screenshot 2025-03-11 at 5 08 17 PM" src="https://github.com/user-attachments/assets/8d0e18e1-d8dc-4f54-97d8-431b46c3a998" />

### 16. Financial Literacy Level & Service Preference
Low: 72.98% rely on Agent Banking, showing dependence on intermediaries.
Medium: More balanced use of Mobile Apps (37.31%) and Web Platforms (27.84%).
High: More self-reliant, with 51.91% using Mobile Apps and 30.09% using Web Platforms.
<img width="815" alt="Screenshot 2025-03-11 at 5 10 01 PM" src="https://github.com/user-attachments/assets/0c92094c-97fd-4372-b54d-5623807a0522" />

### 18. Transaction Volume
- Young Urban Professionals conduct the highest transaction volume at 80K.
- Urban Professionals follow with 70K transactions.
- Small Business Owners account for 30K transactions.
- Rural Users contribute the least, with only 20K transactions.
<img width="817" alt="Screenshot 2025-03-11 at 5 10 56 PM" src="https://github.com/user-attachments/assets/b137546d-228a-47f4-b4bb-78ceb51d280e" />

### 19. Customer Satisfaction Levels
Young urban professionals report the highest satisfaction (79.99% high, 20.01% moderate).
Urban professionals also show high satisfaction (70.22% high).
Small business owners have moderate satisfaction (49.72%), with 20.07% low satisfaction.
Rural users report the lowest satisfaction (69.93% low satisfaction).
<img width="813" alt="Screenshot 2025-03-11 at 5 11 29 PM" src="https://github.com/user-attachments/assets/9e2f8b80-6c16-49d7-b2d4-12ab0f0e4b07" />

## Recommendations

- Product Focus: Prioritize Digital Payments & Mobile Banking (most preferred), expand Micro-Lending with better awareness, and promote Blockchain education to increase familiarity.

- Service Delivery: Strengthen Agent Banking for low-literacy users, enhance Mobile & Web platforms for medium- and high-literacy users.

- Customer Targeting: Focus on Young Urban Professionals & Urban Professionals (largest user base), introduce business-specific solutions for SMEs, and boost financial literacy campaigns for rural users.

- Pricing Strategies: Offer loyalty rewards & cashback, implement a hybrid competitive & value-based pricing model, and introduce tiered subscription services for premium users.

- Marketing & Engagement: Use social media for urban professionals, localized campaigns for rural users, and referral incentives to drive adoption.

## Challenges

- Data Privacy Constraints: Limited access to sensitive information, such as revenue data from companies, restricted our ability to provide deeper insights and enhance data quality.
- Integration of Multiple Data Sources: Merging data from surveys, CBN reports, and industry research required careful alignment to maintain consistency and accuracy.
- Data Assumptions in Synthetic Generation: Reliance on estimated distributions for synthetic data generation introduced potential biases, affecting data reliability.
- Realism of Generated Data: Ensuring that the generated dataset accurately reflected real-world user behavior and economic conditions posed a significant challenge.




