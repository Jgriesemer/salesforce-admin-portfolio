Employee Onboarding and Access Management

## AIMS

When a new employee joins a company, the process of collecting their information and arranging their Salesforce access should be automated to be more consistent.

1. The employee completes a Screen Flow to submit their personal and employment details, including their department, job title and start date.
2. Salesforce saves the information in a custom Employee Onboarding record and automatically creates a follow-up Task for the Salesforce Administrator.
3. The administrator reviews the submitted details, creates the Salesforce User account and assigns the appropriate Permission Set.

The aim is to reduce manual administration, avoid unnecessary data entry, and ensure employees receive the correct level of Salesforce access.

## IMPLEMENTATION

- Created two Permission Sets:
  - Sales Access
  - Sales Manager Access
- Created a custom Employee Onboarding object to store employee information.
- Built a Screen Flow to collect employee details.
- Used a Formula resource to determine the **requested** access based on department and job title. Actual acess is assigned by the Administrator during account creation.
- Used Create Records elements to save the onboarding information and generate an administrator Task.
- Added a confirmation screen at the end of the Flow.

## SALESFORCE SKILLS DEMONSTRATED

- Screen Flows
- Custom Objects and Fields
- Picklists and Required Fields
- Formula Resources
- Create Records
- Task Automation
- Permission Sets
- Object-Level Security

## DESIGN DECISION

Salesforce User creation remains an administrator responsibility. This provides an opportunity to verify employee information and access requirements before granting system access.