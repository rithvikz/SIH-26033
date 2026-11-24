# Smart India Hackathon Workshop
# Date: 24-11-2026
## Reference Number: 26001465
## Name: Rithvik Kuttin

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
KRISHI-SENSE – Smart and Predictive Crop Advisory System
Detailed Explanation of the Proposed Solution
KRISHI-SENSE is an AI-powered crop advisory application designed to help small and marginal farmers make better farming decisions. It collects information about the farmer's land, soil type, crop, weather conditions and budget to provide suggestions that are relevant to their farmland.

Farmers can create a digital profile for their land by entering details such as soil type, water availability, crop history and sowing date. Using this information, the application provides crop-related suggestions, identifies possible risks and helps farmers plan their farming activities.

The application also includes an AI-based plant health scanner that analyses uploaded crop photographs to identify possible diseases, pest attacks and nutrient deficiencies. Weather information is used to generate early warnings about conditions such as excessive rainfall, high temperatures and water shortages.

One of the main features of KRISHI-SENSE is the What-If Farming Simulator. It allows farmers to compare different farming decisions before implementing them. For example, they can compare the possible costs and effects of delaying irrigation, changing fertilizers or selecting a different crop. A crop profitability calculator also helps farmers compare cultivation expenses, expected yield and market prices.

The platform provides irrigation and fertilizer suggestions, crop-care reminders, market price updates and a community alert system where farmers can report unusual crop conditions and share warnings with nearby farmers. It also supports regional languages, voice interaction and offline access to important information.
How it Addresses the Problem
- Provides farming suggestions based on individual farmland conditions instead of generic recommendations.
- Helps farmers identify possible crop problems and weather-related risks at an early stage.
- Allows farmers to compare different farming decisions before spending money or using resources.
- Helps reduce unnecessary water and fertilizer usage.
- Supports crop selection by comparing cultivation expenses and expected returns.
- Makes agricultural information easier to access through regional languages and voice assistance.
Innovation and Uniqueness
The main innovation of KRISHI-SENSE is the What-If Farming Simulator, which allows farmers to understand the possible outcomes of different farming decisions before putting them into practice. Instead of simply suggesting what a farmer should do, the application helps compare available options based on estimated costs, resource requirements and possible risks.

Another important feature is the Farm Digital Passport, which maintains individual records of farmland and uses them to provide more relevant recommendations. The combination of crop-risk alerts, profitability comparison and community-based warnings makes the platform more useful as a complete farming decision-support system.

## Technical Approach
Suggested Technology Stack
Component	Technology
Frontend	Flutter
Backend	Python Django / Django REST Framework
Database	PostgreSQL
AI/ML	TensorFlow / PyTorch
Image Processing	OpenCV
Data Processing	Pandas, NumPy
Weather Information	Weather APIs
Maps	OpenStreetMap
Voice Assistance	Speech-to-Text / Text-to-Speech
Offline Storage	SQLite

## Technical Workflow Diagram
<img width="1535" height="1024" alt="image" src="https://github.com/user-attachments/assets/e7e32fcc-0bdf-44a2-98c5-03c4b720ab1e" />


## System Workflow
1. Farmer registration and login.
2. Farm details and crop information collection.
3. Creation of individual Farm Digital Passport.
4. Weather and soil information retrieval.
5. AI-based crop health analysis and risk identification.
6. Farming recommendations and resource management.
7. What-If Farming Simulator and profitability comparison.
8. Notifications, crop-care reminders and community alerts.
9. Farmer receives personalized agricultural suggestions.


## Feasibility and Viability
The proposed system can be developed using commonly available technologies such as Python, Django, Flutter and PostgreSQL. Existing machine learning models and agricultural datasets can be used for image analysis and crop-related predictions.

The application can initially work with manually entered farmland information without requiring expensive sensors or hardware. The What-If Farming Simulator can be developed using basic calculations and rule-based algorithms, making it practical to implement.

## Impact and Benefits
Target Group	Expected Benefits
Small and Marginal Farmers	Better farming decisions and reduced avoidable expenses
Agricultural Workers	Easier access to crop-related information
Agricultural Officers	Better understanding of common regional farming problems
Environment	Improved use of water and fertilizers
Government Organizations	Access to aggregated information about agricultural challenges
Overall, KRISHI-SENSE aims to make farming decisions easier and more informed by bringing farm-specific recommendations, risk alerts and financial comparisons into a single platform.

## Research and References
Indian Council of Agricultural Research (ICAR) – https://icar.org.in/

Ministry of Agriculture and Farmers Welfare – https://agriwelfare.gov.in/

India Meteorological Department – https://mausam.imd.gov.in/

AGMARKNET – Agricultural Market Information.

Food and Agriculture Organization (FAO) – https://www.fao.org/

TensorFlow – https://www.tensorflow.org/

OpenCV – https://opencv.org/
