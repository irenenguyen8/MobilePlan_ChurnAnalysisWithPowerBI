# Telecommunication Company Customer Churn Analysis

## Overview

This project provides a PowerBI dashboard for customer churn analysis based on a dataset containing user information from a telecommunications company. The dataset includes demographic data, services used by customers, and information related to user churn.

### Purpose

The PowerBI dashboard serves the following purposes:

- **Customer Overview**: Provides an overview of the churn situation by comparing customer churn profiles to all customer profile. This sheet is intended for team leaders of sales or CRM teams to oversee the churn situation and churn characteristics.

- **Customer Detail**: Allows team members of sales or CRM teams to look up information by customer ID. It provides customer contact information, demographic info, and services they are using. Team members can then tailor their approach to decrease the churn rate.

- **Churn Reason Analysis**: Analyzes the top 5 churn reasons and their respective percentages. This sheet offers insights into the main reasons behind customer churn.

- **Ask a Question**: Provides a feature for searching information by keywords, enabling users to quickly access relevant data.

## Dataset

The dataset provides user information of a telecommunications company, including demographic data, services that customers are using, and information related to user churn.

### Data Dictionary

- **Customer ID**: Customer ID.
- **Churn Label**: Indicates whether the customer has churned or not.
- **Account Length (in months)**: Time from when the customer opened the account to the current time.
- **Local Calls**: Number of local calls.
- **Local Mins**: Duration of local calls.
- **Intl Calls**: Number of international calls.
- **Intl Mins**: Duration of international calls.
- **Intl Active**: Indicates if the customer is subscribed to international calling.
- **Extra International Charges**: Extra charges for international calls.
- **Customer Service Calls**: Number of customer service calls made.
- **Avg Monthly GB Download**: Average monthly GB downloaded.
- **Unlimited Data Plan**: Indicates if the customer is using an unlimited data plan.
- **Extra Data Charges**: Extra charges for data usage.
- **State**: Customer's state.
- **Phone Number**: Customer's phone number.
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Under 30**: Indicates if the customer is under 30 years old.
- **Group**: Indicates if the customer is subscribed to group services.
- **Number of Customers in Group**: Number of people in the group.
- **Device Protection & Online Backup**: Indicates if the customer is using device protection and online backup services.
- **Contract Type**: Type of contract.
- **Payment Method**: Payment method.
- **Monthly Charge**: Monthly charge paid by the customer.
- **Total Charges**: Total charges paid by the customer.
- **Churn Category**: Churn category.
- **Churn Reason**: Reason for churn.

## Usage

To use the PowerBI dashboard:

1. Download and install PowerBI Desktop from [Microsoft's website](https://powerbi.microsoft.com/desktop/).
2. Import the provided dataset into PowerBI Desktop.
3. Open the PowerBI project file (dashboard_user_churn.pbix) containing the dashboard.
4. Interact with the dashboard to explore churn analysis insights.

## Dependencies

- PowerBI Desktop
