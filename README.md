# MyClassData
The telecommunications dataset simulates customer records from a telecommunications company with 1,000 customers and contains variables relevant for churn analysis:

Demographic Variables:
- Customer ID: Unique identifier
- Age: Normal distribution, mean 45 years
- Tenure: Poisson distribution, mean 30 months 

Financial Metrics:
- Monthly Charges: Normal distribution, mean $70
- Total Charges: Calculated from monthly charges and tenure
 
Usage Patterns:
- Call Minutes: Normal distribution, mean 600 minutes
- Data Usage: Exponential distribution, mean 50GB
- Support Calls: Poisson distribution, mean 2 calls

Service Information:
- Contract Type: Month-to-Month, 1 Year, 2 Year
- Payment Method: Credit Card, Bank Transfer, Electronic Check, Mailed Check
- Internet Service: DSL, Fiber Optic, No service
- Streaming TV and Movies: Binary yes/no

Target Variable:
- Churn: Binary outcome with 15% churn rate

Missing data patterns are introduced systematically:
- Age: 10% MCAR
- Data Usage: 20% MAR (dependent on contract type)
- Monthly Charges: 30% MNAR (higher values more likely missing)

This structure allows students to explore relationships between service usage, customer behavior, and churn while practicing various preprocessing techniques.
