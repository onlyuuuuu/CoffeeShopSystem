# Coffee Shop System 101D

> For general designs, please refer to [CoffeeShopSystem101D.drawio](CoffeeShopSystem101D.drawio). You can open this from **draw.io** application or head to https://app.diagrams.net/ (Choose **File**, **Open from**, **Device**)

## Time estimation

**1d** = **8 hours of work**

### Design and Initial Development Phase (2d):
- Database designs, code base initial setup with Liquidbase SQL Scripts, scripts for running database container for development: **1d**.
- Setup dummy data sets for development, bootstrapping with application startup, more scripts for building and localize testing: **1d**.

### Core Service Development Phase (3d):
- Develop main functionalities: **2d**.
  - CRUD operations for products, orders: **1d**.
  - CRUD operations for venues, customers: **1d**.
- Unit testing, UAT testing and resolving issues: **1d**.

### Auth Service Development Phase (2d):
- Develop main functionalities: **1d**.
    - JWT Token authorization and integration with Core Service: **1d**.
- Unit testing, UAT testing and resolving issues: **1d**.

### Final Testing and Packaging Phase (2-3d):
- Develop more scripts for building testing and containerizing: **1d**.
- Setting up an NGINX container instance for wrapping up: **1d**.
- Final testing and issues resolving (buffer duration, in case anything goes wrong): **1d**.

### Total Estimation: 10d = 80 hours of work

## Technology stacks:
- Authentication/Authorization:
  - OAuth2, JWT Token, SHA256 Token Signing.


- Design Patterns:
  - Singleton
  - Builders
  - Bridge


- Backend Core:
  - Java 20
  - Spring Boot
  - Liquibase

- Database:
  - PostgreSQL

- Deployment:
  - Docker.
  - Docker Compose.
  - NGINX.
  - Shell scripts
  - Python (if required)

For testing, probably a good idea to use Selenium for writing scripted test cases in Java, but I've never done it before, same thing for the Liquibase migration.

Sorry for not including some more details in this since I've just started working on this yesterday, I was quite busy at the weekend. My apology. Thanks for reviewing, very much appreciate it. Have a good day.