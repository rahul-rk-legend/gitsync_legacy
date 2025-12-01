# GitSync

## Integrations
|Name|Description|
|----|-----------|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|EmailUtilities|A set of utility actions to assist with working with emails.  Includes actions to parse EMLs and analyze email headers.|
|Exchange|Integration provides support for Microsoft Exchange 2010 - 2019 and Microsoft Office365 mail servers. Integration uses Exchange Web Services (EWS) for communication. Integration includes a series of actions to send out emails and work with received emails, along with a connector to monitor specific mailboxes and ingest emails from that mailboxes as alerts to Google SecOps for further analysis.|
|Functions|A set of math and data manipulation actions created for Google SecOps Community to power up playbook capabilities.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|HTTP V2|HTTP V2 integration was designed for you to build your own integrations, actions without the need of writing any code.|
|Jira|Jira Software is part of a family of products designed to help teams of all types manage work. Originally, Jira was designed as a bug and issue tracker. But today, Jira has evolved into a powerful work management tool for all kinds of use cases, from requirements and test case management to agile software development. Jira will be the perfect fit for: requirements & test case management, agile teams, project management teams, software development teams, product management teams, task management, bug tracking and much more...|
|UrlScanIo|urlscan.io is a service to scan and analyse websites.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Exchange Mail Connector v2 with Oauth Authentication|Connector can be used to monitor specific mailboxes on Office 365 mail servers that require Oauth authentication. Get Authorization and Generate Token actions can be used to obtain refresh token that should be set in the connector. Note: Make sure to configure the integration first for the Oauth authentication.|True|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|Jira Connector|Fetch issues from Jira to Siemplify|True|


## Playbooks
|Name|Description|
|----|-----------|
|Block 2|An embedded workflow that can receive inputs and return an output.|
|Playbook 1||
|Block 1|An embedded workflow that can receive inputs and return an output.|
|Playbook 2||


## Visual Families
|Name|Description|
|----|-----------|
|Family 1 |Family 1|


## Jobs
|Name|Description|
|----|-----------|
|Sync Comments|Sync comments between Google SecOps alert's case and corresponding Jira ticket. Sync mechanism works in both ways, Google SecOps → Jira and Jira → Google SecOps|
|Token Renewal Job|Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.|

