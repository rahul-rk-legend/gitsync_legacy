# Jira Connector
Fetch issues from Jira to Siemplify


Integration: Jira

Integration Version: 50.0

Device Product Field: device_product

Event Name Field: issuetype_name
### Parameters
|Name|Description|Is Mandatory|Value|
|----|-----------|------------|-----|
|Use Jira Project as Environment|Use Jira project as environment else use Environment Field Name as environment.|False|false|
|Environment Field Name|Describes the name of the field where the environment name is stored. If the environment field isn't found, the environment is the default environment.|False||
|Days Backwards|Max number of days backwards to pull alerts from|False|1|
|Project Names|Project names separated by comma|False|kanban project|
|Proxy Server Address|The address of the proxy server to use.|False||
|Script Timeout (Seconds)|The timeout limit (in seconds) for the python process running current script|True|180|
|Api Root|The API root of the JIRA instance|True|https://google-team-gcr2cbk8.atlassian.net|
|Username|Username|True|marthasahithya@google.com|
|Api Token|Api Token|True|***************|
|Proxy Password|The proxy password to authenticate with.|False||
|Environment Regex Pattern|A regex pattern to run on the value found in the "Environment Field Name" field. Default is .* to catch all and return the value unchanged. Used to allow the user to manipulate the environment field via regex logic. If the regex pattern is null or empty, or the environment value is null, the final environment result is the default environment.|False|.*|
|Max Tickets Per Cycle|Max tickets to fetch and process in one connector cycle|False|2|
|Verify SSL|If enabled, verify the SSL certificate for the connection to Jira server is valid.|False|false|
|Issue Statuses|Issue statuses separated by comma|False||
|Assignees|Users full names separated by comma|False||
|Issue Types|Issue types separated by comma|False||
|Issue Priorities|Issue priorities separated by comma|False||
|Issue Components|Issue components separated by comma|False||
|Proxy Username|The proxy username to authenticate with.|False||

