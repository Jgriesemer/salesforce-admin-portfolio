AIMS

When a Lead is converted into an Account and Contact, I want the first steps of the customer handover to be automated.

The new Contact receives a welcome email with a link to a pdf that has been uploaded to Salesforce Files. The PDF contains useful information about the company. If no contact email address is found, the email is skipped.

At the same time, Salesforce creates a follow-up Task for the Account Owner, reminding them to get in touch with the new customer within three days.

The idea is to reduce manual work and make sure new customers don't get forgotten after conversion.

How the Flow Works

The automation is built using a record-triggered flow on the lead object.

When a Lead is converted:

1. The Flow retrieves the newly converted Contact using the Converted Contact ID.
2. A Decision element checks whether the Contact has an email address.
3. If an email address is available, a welcome email is sent with a link to the company PDF.
4. If an email address is unavailable, the email step is skipped.
5. Regardless of the email outcome, a follow-up Task is created for the Account Owner.
