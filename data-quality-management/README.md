Data Quality Management

AIMS

Poor-quality data can make it difficult for a sales team to function.

The aim of this project was to improve data quality by preventing duplicate Leads, enforcing important data requirements, and making incomplete records easier to identify.

BUSINESS VALUE

This project can help an organisation maintain more reliable customer data, reduce duplicate records, and give sales management better visibility of data quality.


The solution includes:

Duplicate detection to identify and prevent the creation of duplicate Lead records.

Account validation rules to encourage consistent and reliable Account information.

A Lead Data Completeness score to highlight missing information.

Reports and a dashboard to help the sales team and management monitor data quality.

IMPLEMENTATION

1. Duplicate Lead Prevention

Created a Lead matching rule using exact Email matching.

Created a duplicate rule to block Leads with an existing matching email address.

Added a second matching rule using First Name, Last Name and Company to identify potential duplicates with different email addresses.

Configured the second rule to display a warning while allowing the user to continue.

2. Account Validation Rules

Created a validation rule to require an Industry value when saving an Account.

Added an Unknown option to the Industry picklist.

3. Lead Data Completeness

Created a custom formula field to calculate Lead data completeness as a percentage.

The score checks whether Email, Phone, Title, and Industry are populated.

Added the score to the Lead record header using a custom Compact Layout.

This makes incomplete records easier for users to identify.

4. Reports and Dashboard

Created reports to monitor data quality:

Leads with Incomplete Data

Leads by Data Completeness

Combined these reports into a Leads and Account Data Quality dashboard.

TESTING

Tested duplicate Lead prevention using two Leads with the same email address.

Tested potential duplicate detection using matching names and company names but different email addresses.

Tested Account validation rules with missing and populated Industry values.

Checked that the Data Completeness formula returned the expected percentages.

Verified that reports and dashboard components reflected the test data.

SALESFORCE SKILLS DEMONSTRATED

Matching Rules

Duplicate Rules

Validation Rules

Custom Picklist Values

Formula Fields

Compact Layouts

Salesforce Reports

Dashboards

Data Import Wizard

Data Quality Management