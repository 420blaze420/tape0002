# tape0002


RFP Wireless Infrastructure

### 1. Organization and Project Background

#### What the organization does and who it serves
* **Xcompanyx** is a specialized art storage and brokerage firm that integrates secure, climate-controlled warehousing with full-service commercial sales support. We work with collectors, galleries, and investors, to safely store high-value artworks while also facilitating private viewings, and managing sales. By combining reliable storage with active market support, **Xcompanyx** provides a streamlined solution for clients looking to both protect and manage the value of their art collections.

* **Xcompanyx** has 13 separate departments.
  * Executive
  * Sales
  * Customer service
  * Warehouse management
  * Security
  * IT
  * Conservation & preservation
  * Finance
  * HR
  * Legal & compliance
  * Marketing & public relations
  * Logistics & shipping
  * Facility maintenance
  
* **Xcompanyx** needs a new wireless network that provides reliable coverage, strong security, modern performance, centralized management, and support for future growth.

#### The size of the organization and number of users
* 1442 employees, 1256 employees using internet services, 86 IT employees.
* Employees require network access across the campus to support daily business operations, including but not limited to asset management and client service.
* Some employees need full internet access, while others might only need access to internal applications such as POS or shared terminals.
* The design must support role based access, and a separation of departments in support of protecting sensitive client and inventory data.

#### Why the new wireless network is required
* **Xcompanyx** has expanded its campus, and employees are spread far and wide across the company campus. A new wireless network would support troubleshooting, testing, and deployment of internal network configurations across the campus. The ability to connect to a wireless network anywhere across the campus will increase efficiency and lower down time, in regard to troubleshooting, testing, and new configuration deployments.

#### Current problems or limitations
* Due to the lack of a wireless network, **Xcompanyx** IT employees must use a physical ethernet connection for troubleshooting, testing, and deploying. Since the expansion of our company campus, IT employees have been limited in their abilities to troubleshoot, test, and deploy internal network configurations around the expansion. 
  
### 2. Project Objectives

#### Reliable wireless coverage
* Reliable wireless coverage should span the entire campus.
* For IT operations such as troubleshooting, testing, and deploying this would reduce downtime significantly. This would also greatly lower the risk of productivity and financial loss, due to the relationship between downtime and financial loss.

#### Improved performance and capacity
* The wireless network must be able to support at least 1256 users at once, with consistent strong performance.
* IT employees must have the capacity to connect to and use the network from anywhere on the **Xcompanyx** campus.

#### Stronger security
* Must implement WPA3 security with a RADIUS server for 802.1X authentication of all users and devices on the new wireless network.
* RADIUS server must be integrated with existing architecture and support ADDS for policy enforcement.
* Integration of a new firewall, or configuration of the old firewall to support wired and wireless protections.
* 

#### Centralized monitoring and management
* **XCompanyx** administration is done through the use of an ADDS deployed on a domain controller.
* The new wireless network must support centralized administration through the use of an ADDS on the **Xcompanyx** domain 'xcomx'.

#### Support for future growth
* The wireless network must be installed with future growth in mind. **Xcompanyx** is one of the fastest growing companies in North America, and the network infrastructure must be able to support future expansions, changes, and additions.

### 3. Scope of Work

#### Wireless site survey
* Prior to any implementations or configurations **Xcompanyx** requires a site survey done by the project manager. They will collaborate with an IT employee, chosen by the **Xcompanyx** CIO, to determine the best fit for our campus environment.
* The site survey document should include a signal strength heat map, access point placement, installation and configuration recommendations, integration with existing wired network, security configurations, expected basic maintenance, and expectations of support.

#### Access point placement
* Access point placement should be determined through the use of a heat map, of which would be produced during the site survey.
* Access points must support Wi-Fi 6 technology at minimum, and support options for future expansion; Wi-Fi6E or Wi-Fi7 readiness.
* Expected indoor coverage: 100%
* Expected outdoor coverage: 95%

#### Installation and configuration
* **Xcompanyx** can spare a maximum of 4 IT employees to assist the project manager when making determinations regarding the wireless network and complete configurations.
* The installation and configurations must **NOT** be done by **Xcompanyx** IT employees.
* IT employees assigned to support the project manager, are responsible for facilitating and assisting the efficient deployment and integration of the new wired network, not for performing duties of the project manager.
  
#### Integration with the existing wired network
* The new wireless network must be integrated with the current wired network, supporting communication between wired and wireless users.
* Must design, install, configure, and integrate a RADIUS server with LAN controller and/or access points to support 802.1x authentication.

#### Security configuration
* Must implement WPA3 security with a RADIUS server to support 802.1X authentication and authorization for all users on the new wireless network.
* RADIUS should authenticate users with the ADDS 'xcomx' domain.
* Implementation of role-based access, enforced by assigning users to appropriate department VLAN or enforcing access control lists via ADDS 'xcomx' domain.
* The new wireless network must be integrated with the current wired network to support security concerns regarding communications or company data leaking out of the domain.
* Integration of a new firewall, or configuration of the old firewall to support wired and wireless protections.
* Must complete a series of network tests to validate whether or not it was a successful deployment.

#### Testing and validation
* Technicians must complete and document a series of network tests, validating successful implementation and integration of the wireless network.
* Documentations must be completed on the comprehensive 'Testing & Validation' document/form.

#### Basic maintenance and support expectations
* Require a post installation meeting where the project manager can explain and discuss the installation with CIO, and other IT employees.
* The project manager must complete and submit a document covering expected maintenance, and a separate document covering expectations for future support.
* **Xcompanyx** intends on future expansions to the company and company campus and expects a configuration that supports user and geographical growth.

### 4. Technical Requirements

#### Wi-Fi 6 or newer
* **Xcompanyx** at minimum requires a wireless network that supports Wi-Fi 6 technology.
* Typical business operations require very fast speeds to ensure customer satisfaction.

#### WPA3
* Must implement WPA3 enterprise grade security with 802.1X authentication for all users on the new wireless network.
* Must use a RADIUS server for authentication and authorization, via integration with the 'xcomx' ADDS domain.
* Communications between the RADIUS server(s) and wireless infrastructure must be encrypted.
* The final design must support at least 1256 simultaneous users, and at least 3000 devices.

#### Guest network isolation
* A subnet for guest users will not be necessary.
* Due to the risk associated with our business operations, only employees who require access will receive access.
* No guest users will be permitted on the network. 

#### VLAN integration
* Multiple network segmentations exist separating departments via VLANs.
* The new wireless network configuration must be integrated with the company's current VLAN configuration.
* VLAN assignment must be supported by the policies implemented on the RADIUS server.

#### Support for the expected number of users and devices
* The new network must be able to support all 1256 employees using internet services simultaneously.
* The new network must be able to support at least 3000 devices.

#### Scalability
* The new wireless network must support the expansion of users, devices and geographical coverage.
* Option to increase number of access points without controller replacement.

#### Mandatory and preferred requirements
* Implementation of WPA3 security with 802.1x authentication and a RADIUS server.
* No guest network.
* Must support 1256 simultaneous users, and at minimum 3000 devices.
* Must be scalable, due to planned expansions.

### 5. Deliverables

#### Documentation

##### List of required documents.
* A comprehensive document titled 'Installation, Configuration, and Integration' covering the entire process of installation, configuration, and integration of all devices with the current wired network.
* A comprehensive document titled 'Basic Maintenance' covering expected basic maintenance is required.
* A comprehensive document titled 'Support Expectations' covering future support expectations is required.
* A comprehensive document titled 'Testing & Validation' covering troubleshooting, testing and validation results is required.
* A comprehensive document titled 'Site Survey'. For more details, see '5.Deliverables > Site survey report'
* A comprehensive document titled 'Administrator guide' covering changes and new expectations of the wireless network to the network administrator.

#### Site survey report
The site survey report must include the following:
* Heat map representing signal strength.
* Access point placement recommendations.
* Installation and configuration recommendations.
* Integration recommendations.
* Security recommendations.
* Expected maintenance.
* Support expectations.

#### Wireless network design
* **Xcompanyx** requires the creation and submission of a wireless network diagram, showcasing the details of the network.

#### Installed and configured access points
* Access points will be installed in designated areas around the campus to support 100% indoor coverage and at minimum 95% outdoor coverage.
* Designated areas will be determined through the use of a signal strength heat map under the project managers discretion.
* Access points will be placed in a manner of which increases signal strength in low signal strength areas.

#### Network diagram
* **Xcompanyx** requires the creation and submission of a network diagram, showcasing the details of the wired and wireless network.

#### Test results
* All test results are to be documented and submitted within the 'Testing & Validation' document. 

#### Administrator guide
* A document titled 'Administrator guide' must be delivered explaining the changes which have occurred since the integration.
* This document explains the changes and new expectations to the network administrator.
* This document should include but is not limited too WPA3, 802.1x authentication, RADIUS server, access points, integration, wireless coverage statistics,

#### Support plan
* A support plan document must be submitted detailing post-launch maintenance, service level agreements and any new technical requirements.

### 6. Timeline and Pricing

#### Proposal deadline
* September 15, 2026

#### Vendor selection date
* October 10, 2026

#### Project start date
* November 1, 2026

#### Installation and testing period
* November 1, 2026 - January 15, 2027

#### Project completion date
* January 16, 2027

#### Initial costs 
* Approximately $343,000

#### Ongoing costs
* Approximately $54,000

### 7. Evaluation Criteria

#### Create a weighted evaluation table that totals 100 percent
| Category | Weight |
| --- | --- |
| Technical Solution | 25% |
| Security | 25% |
| Implementation plan | 15% |
| Vendor experience | 10% |
| Scalability| 10% |
| Pricing | 15% |
| Total | 100% |

### 8. Submission and Terms

#### Submission format and contact information
* Format: Hardcopy via mail services.

* Submissions may be sent via mail.

* Questions may be submitted via mail or our public email.

* All submissions must be to submitted by September 15, 2026

Contact Information: 
* **Xcompanyx**

  Mailing Address: 59 Grey Road, LA

  Company Email: xmox@xcompanyx.com
  
#### Late-submission policy
* Proposals received after the submission deadline will be considered late and may be disqualified.

#### Confidentiality
* All information in this RFP and further communications is confidential and intended for the recipient vendor only. 
* Breach of confidentiality may result in disqualification from bidding, and/or legal action.

#### Pre-implementation support expectations
* Vendor will provide and assign **Xcompanyx** a project manager.

#### Post-implementation support expectations
* Critical issues: 24x7 support.
* Low-severity issues: 8am to 5pm support.

#### Change-control process
* All changes to design, schedule scope or cost after being awarded the contract must follow a formal change-control process.

#### Contract duration
* 3 years post completion date.

Optional renewal
* Up to two additional years.

Termination
* **Xcompanyx** may terminate the contract within 90 days written notice.


