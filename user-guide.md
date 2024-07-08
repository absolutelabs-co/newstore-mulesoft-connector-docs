# NewStore MuleSoft Connector- Mule 4 (1.0.0)
The NewStore Connector allows seamless integration within Mule apps, enabling the management of customer data integration.
This connector connects you to the NewStore REST API, offering a variety of operations to access backend systems.
For compatibility information, please refer to the release notes.

# Before You Begin
To use this connector, you must be familiar with:
- The NewStore REST API
- Anypoint Connectors
- Mule runtime engine (Mule)
- Elements and global elements in a Mule flow
- Creating a Mule app using Anypoint Studio
- Access to a NewStore account.

# Authentication Types
NewStore Connector connections use the following authentication type:
OAuth 2.0 Client Credentials Grant:
Uses client ID and secret for authentication

# Using the connector
## Add the connector to the Anypoint Studio

To add the NewStore Connector to Anypoint Studio:
1.	Open Anypoint Studio.
2.	In your project, right-click on "src/main" or another appropriate folder.
3.	Select "Anypoint Connectors" from the context menu.
4.	Click on "Add External Connectors".
5.	Search for "NewStore" in the marketplace.
6.	Select the NewStore Connector and follow the prompts to install it.
To include dependencies for the NewStore Connector in your pom.xml file for a manually coded Mule app, add the following XML snippet:
<img width="682" alt="image" src="https://github.com/absolutelabs-co/newstore-mulesoft-connector-docs/assets/133132174/da172a58-f801-467b-b0b7-df7e6a3b9522">

## Configure the Connector credentials with API Client

| Field | Description |
|----------|----------|
| Tenant   | Typically the name of your company |
| Stage   | The stage variable, for example: sandbox, staging, or empty if production|
| Client Id | Your NewStore Client Id |
| Client Secret  | Your NewStore Client Secret |
| Scopes  | List of scopes that apply to the OAuth token |

<img width="663" alt="image" src="https://github.com/absolutelabs-co/newstore-mulesoft-connector-docs/assets/133132174/5cb51641-3d94-4e53-9f7c-e66f259c11b3">

<img width="663" alt="image" src="https://github.com/absolutelabs-co/newstore-mulesoft-connector-docs/assets/133132174/59d2c2a4-3079-49a7-915b-60502d55fec0">

# Example use case of the connector
This use case demonstrates how to utilize the NewStore Connector for creating or updating a customer. It includes:

1. Utilizing an HTTP Listener as the input source.
2. Employing a NewStore operation with a specified payload.

<img width="449" alt="image" src="https://github.com/absolutelabs-co/newstore-mulesoft-connector-docs/assets/133132174/786b9a75-5706-4d58-bca4-5b31b6c8c0fa">

<img width="677" alt="image" src="https://github.com/absolutelabs-co/newstore-mulesoft-connector-docs/assets/133132174/0d6e5ddc-f1e8-4945-9ba9-3de9f425f040">































