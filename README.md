#VeevaVault Connector

The Veeva Vault Connector lets you connect Mule flows to the Veeva Vault platform using Veeva REST API depending on the operation you configure. 
The connector works with the Veeva Vault REST, Bulk, and Streaming API, depending on the operation you configure. Each API call uses an JSON/CSV request and returns JSON input stream response over an HTTPS connection. All required request headers, error handling, and HTTPS connection configurations are built into the connector.

The Veeva Vault connector can be use in mule application as an outbound connector with CRUD (Create, Retrieve, Update, Delete), Query, Download operations on following Vault Objects. These operations are discussed later in this document.

•	Documents – Create, Retrieve, Update, Delete, Download, Export.
•	Document Renditions – Create, Retrieve, Update, Delete.
•	Vault Object – Create, Retrieve, Update, Delete.
•	Picklists – Retrieve.
•	Audit Trial – Retrieve.  
•	Query – VQL Query to query on Documents, Vault Object, Workflows.


About MuleSoft Certified Connectors
MuleSoft Certified Connectors are developed by MuleSoft’s partners and developer community. These connectors have been reviewed and certified by MuleSoft. Fees for MuleSoft Certified Connectors may vary. MuleSoft Certified Connectors are not accessible in the MuleSoft Community Edition. MuleSoft disclaims any support obligation for MuleSoft Certified Connectors.

This connector is managed by MuleSoft's partner, Xoriant Corporation. The use of this connector requires an additional fee to Xoriant. For more information about using this connector or to receive assistance or support, contact Xoriant directly at +1 408 743 4400.

By installing this connector, you consent to MuleSoft sharing your contact information with the developer of this connector so that you can receive more information about it directly from the developer.

About Xoriant
Xoriant is a Silicon Valley based product engineering, software development and technology services firm with offices in the U.S., Europe and Asia. For both technology companies and enterprises, from startups to the Fortune 100, we leverage our expertise in emerging technologies to deliver innovative solutions that accelerate our clients’ Digital Transformation initiatives. Our practices include Product Engineering, Cloud & Infrastructure, Security, Big Data & Analytics, Data Management & Governance and IoT. Across all practice areas, we are making significant investments in next generation technologies and solutions to help deliver innovation to our clients. These include machine learning, hybrid cloud security & compliance, blockchain, IoT data gathering & processing and open source solution integration. To learn more about Xoriant, visit the Xoriant website - https://www.xoriant.com
