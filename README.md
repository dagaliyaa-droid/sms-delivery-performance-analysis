# SMS Delivery Performance Analysis

## Objective
To analyze SMS delivery data and identify delivery success rates, failure patterns, and operator-level performance issues.

## Tools Used
- Microsoft Excel
- Tableau (for visualization)
- Sample SMS delivery dataset (CSV)

## Dataset Description
The dataset contains SMS delivery records with the following fields:
- Message ID
- Client Name
- Operator
- Message Route (OTP, Promotional, Transactional)
- Delivery Status
- Delivery Time (seconds)
- Date

## Key Analysis Performed
- Delivery success vs failure analysis
- Operator-wise delivery performance
- Route-level failure trends
- Average delivery time for successful messages

## Insights
- OTP routes showed higher failure rates on specific operators
- Promotional messages had higher delivery times compared to transactional messages
- Certain operators showed consistent delivery delays

## Outcome
This analysis helps identify weak delivery routes and operators, enabling faster escalation and improved messaging performance.

## Future Enhancements
- Add SLA breach analysis
- Include time-based trend analysis
- Automate reporting using SQL
