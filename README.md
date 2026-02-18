# Financial Advisor System

This Spring Boot project implements the data model for managing advisors, clients, portfolios, and securities.  

Entities:
- Advisor
- Client
- Portfolio
- Security

Relationships:
- Advisor → Client (1:N)
- Client → Portfolio (1:1)
- Portfolio → Security (1:N)

All entities are implemented using Spring Data JPA.
