## Fifteen Factor App

In the continuously evolving world of technology, the most pressing requirement for any software development is to have the application performant, scalable, easily manageable, and resilient. In 2012, programmers at Heroku debuted the Twelve-Factor app methodology that states the General Principles and Guidelines for creating robust Enterprise Applications.  

Modern application architectures are very complex and the containerized approach of hosting Cloud Native applications, especially the microservices architecture, makes the complete environment highly dynamic. Though Twelve-factor app principles are equally effective today and do align with the changing environment, but need to have extensions to these principles is felt. 

This article focuses on the additional factors that are pretty much in force and are highly discussed across the industry now-a-days. 


#### The Methodology - Fifteen Factor App

<strong>Fifteen Factors</strong> are an extension and suggested additions to the twelve factors that support the modern application architectures. Looking at the complexity and architectural changes witnessed in modern applications, existing layout principles are being elaborated further and the key suggested factor additions are as below –
- API First Approach
- Telemetry
- Security (Authentication and Authorization)

The methodology remains aligned with the principles suggested in core Twelve-Factor App methodology with an extension to additional factors –
- Use <strong>Declarative Formats</strong> for setup automation, to minimize time and cost for new developers joining the project
- Have a <strong>Clean Contract</strong>, offering maximum portability between execution environments
- Are suitable for deployment on modern Cloud Platforms, obviating the need for servers and systems administration
- <strong>Minimize Divergence</strong> between development and production, enabling continuous deployment for maximum agility
- <strong>Dynamically Scalable</strong> without significant changes to tooling, architecture, or development practices.
- <strong>Service-Driven Approach</strong> – Availability of the contract to be consumed by a Front-end client application, routing gateway, or any other downstream system
- <strong>Monitoring</strong> the distributed applications deployments for domain/application-specific logs/data, health information, or more statistics on modern cloud platforms
- <strong>Security</strong> (Authentication and Authorization) is addressed appropriately so that identity is implemented for each of the requests
<BR/>

![15FactorApp-15-Factors.jpg](./images/15FactorApp-15-Factors.jpg)

#### Article References to 15 Factors

| Reference                                                 | Description                                                  |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| [Initial Setup & Tools](./setup_and_tools.md)                                     | Quick setup and tools reference to start with                          |
| [01 - Codebase](./01_codebase.md)                                     | Start with Git Repository                          |
| [02 - Dependencies](./02_dependencies.md)                                     | Handle Dependencies                          |
| [03 - Config](./03_config.md)                                     | Managing project Configurations                          |
| [04 - Backing services](./04_backing_services.md)                                     | Backing Services Insight                          |
| [05 - Build, Release, Run](./05_build_release_run.md)                                     | Build, Release, Run stages reference                          |
| [06 Processes](./06_processes.md)                                     | Stateless Processes                          |
| [07 - Port binding](./07_port_binding.md)                                     | Port Binding Approach reference                          |
| [08 - Concurrency](./08_concurrency.md)                                     | Bringing-in Concurrency                          |
| [09 - Disposability](./09_disposability.md)                                     | Bringing-in Concurrency                          |
| [10 - Dev / Prod Parity](./10_dev_prod_parity.md)                                     | Bringing-in Concurrency                          |
| [11 - Logs](./11_logs.md)                                     | Logging Guidelines                          |
| [12 - Admin Processes](./12_admin_processes.md)                                     | Manage Admin Processes                          |
| [13 - API First](./13_api_first.md)                                     | API First Approach                          |
| [14 - Telemetry](./14_telemetry.md)                                     | Telemetry - Application Monitoring                          |
| [15 - Security](./15_security.md)                                     | Security - Authentication and Authorization                             
