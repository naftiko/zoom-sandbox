# Zoom API & MCP Sandbox
This is an API sandbox for the Zoom API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Zoom API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Zoom API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Zoom API & MCP Sandbox.

- Number of Paths: 186
- Number of Operations: 186
- Number of Read Operations: 0
- Number of Write Operations: 186
- Number of Schemas: 199
- Number of Responses: 0
- Number of Parameters: 0
- Number of Examples: 163
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Zoom API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Zoom Account Management Api](openapi/zoom-account-openapi-original.yml)
  - [Zoom Chat Messages Api](openapi/zoom-chat-openapi-original.yml)
  - [Zoom H323sip Device Management Api](openapi/zoom-device-openapi-original.yml)
  - [Zoom Groups Api](openapi/zoom-group-openapi-original.yml)
  - [Zoom Instant Messaging Groups Api](openapi/zoom-im-openapi-original.yml)
  - [Zoom Meetings Api](openapi/zoom-meeting-openapi-original.yml)
  - [Zoom Dashboard Metrics Api](openapi/zoom-metrics-openapi-original.yml)
  - [Zoom Rest Api](openapi/zoom-openapi-original.yml)
  - [Zoom Cloud Recording Api](openapi/zoom-recording-openapi-original.yml)
  - [Zoom Report Api](openapi/zoom-report-openapi-original.yml)
  - [Zoom User Api](openapi/zoom-user-openapi-original.yml)
  - [Zoom Webinar Api](openapi/zoom-webinar-openapi-original.yml)

## Resources
These are the resources available via the Zoom API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Account
  - Account Reports
  - Audio Reports
  - Billing Management
  - Chat
  - Chat History
  - Cloud Recording
  - Cloud Recordings
  - Crc Metrics
  - Dashboard
  - Device
  - Device Management
  - Group
  - Group Members
  - Groups
  - Im Group
  - Im Group Members
  - Im Groups
  - Instant Messaging Metrics
  - Meeting
  - Meeting Connector Recordings
  - Meeting Information
  - Meeting Management
  - Meeting Metrics
  - Meeting Registration
  - Plan Management
  - Quality Of Service
  - Report
  - Schedule Privileges
  - Sub-account Management
  - User
  - User Assistants
  - User Authentication
  - User Lookup
  - User Management
  - User Reports
  - User Status
  - Webinar
  - Webinar Attendees
  - Webinar Engagement
  - Webinar Lookup
  - Webinar Management
  - Webinar Metrics
  - Webinar Panelists
  - Webinar Registration
  - Zoom Rooms Metrics

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Zoom API & MCP Sandbox.

  - Activate User
  - Add An Additional Plan
  - Add Members To A Group
  - Approve Webinar Registrants
  - Auto-create User
  - Cancel Webinar Registrations
  - Check Zpk Token Validity
  - Check Email Existence
  - Create Sso User
  - Create A Group
  - Create A Meeting
  - Create A New Device
  - Create A New Sub-account
  - Create An Im Group
  - Create User
  - Create Webinar
  - Custom Create User
  - Deactivate User
  - Delete Cloud Recording
  - Delete A Device
  - Delete A Group
  - Delete A Meeting
  - Delete A Sub-account
  - Delete An Im Group
  - Delete User
  - Delete User Assistant
  - Delete Webinar
  - End A Meeting
  - End Webinar
  - Get Crc Port Usage
  - Get Cloud Recording Details
  - Get Im Group Details
  - Get Instant Messaging Statistics
  - Get Meeting Details
  - Get Quality Of Service Metrics
  - Get Webinar Details
  - Get Zoom Room Details
  - Get Account Report
  - Get Audio Usage Report
  - Get Chat Messages
  - Get Daily Report
  - Get Group Details
  - Get Meeting Details
  - Get Plan Information
  - Get Sub-account Details
  - Get User By Id
  - Get User By Email
  - Get User Report
  - Get Webinar Q&a
  - Get Webinar Details
  - Get Webinar Panelists
  - Get Webinar Polls
  - Get Webinar Registration Info
  - List Cloud Recordings
  - List Im Group Members
  - List Meeting Connector Recordings
  - List Meetings Metrics
  - List Webinars Metrics
  - List Zoom Rooms
  - List All Im Groups
  - List All Devices
  - List All Groups
  - List All Sub-accounts
  - List All Users
  - List Chat Sessions
  - List Group Members
  - List Live Meetings
  - List Pending Users
  - List Registration Webinars
  - List Schedule Privileges
  - List Scheduled Meetings
  - List Webinar Uuids
  - List Webinar Attendees
  - List Webinar Registrants
  - List Webinars
  - Permanently Delete User
  - Register For A Meeting
  - Register For Webinar
  - Remove Members From A Group
  - Remove Members From An Im Group
  - Revoke Sso Token
  - Set User Assistant
  - Subscribe To Plans
  - Update A Device
  - Update A Group
  - Update A Meeting
  - Update A Plan
  - Update A Sub-account
  - Update An Im Group
  - Update Billing Information
  - Update User
  - Update User Profile Picture
  - Update Webinar

## Backstage
We provide a Backstage software catalog entity for the Zoom API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Zoom Account Management API](backstage/zoom-account-backstage-original.yml)
  - [Zoom Chat Messages API](backstage/zoom-chat-backstage-original.yml)
  - [Zoom H323sip Device Management API](backstage/zoom-device-backstage-original.yml)
  - [Zoom Groups API](backstage/zoom-group-backstage-original.yml)
  - [Zoom Instant Messaging Groups API](backstage/zoom-im-backstage-original.yml)
  - [Zoom Meetings API](backstage/zoom-meeting-backstage-original.yml)
  - [Zoom Dashboard Metrics API](backstage/zoom-metrics-backstage-original.yml)
  - [Zoom Rest API](backstage/zoom-backstage-original.yml)
  - [Zoom Cloud Recording API](backstage/zoom-recording-backstage-original.yml)
  - [Zoom Report API](backstage/zoom-report-backstage-original.yml)
  - [Zoom User API](backstage/zoom-user-backstage-original.yml)
  - [Zoom Webinar API](backstage/zoom-webinar-backstage-original.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Zoom API & MCP Sandbox.

