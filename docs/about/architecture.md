# Gen3 Commons Architecture

***

User access to the Gen3 Commons runs through a VPC or Virtual Private Cloud.   Access to data and analysis tools through a Virtual Private Cloud (VPC) allows for balance of usability and security.   All access is through a monitored head node.  Data is not directly accessed from the Internet.  

Other secure and compliant Gen3 member systems (including cloud based systems) can access Gen3 data through the API.

### Diagram of the Gen3 System Architecture
![Gen3 Architecture]({{ "/assets/architecture.png" | absolute_url }})
