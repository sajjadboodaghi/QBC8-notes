## Week 8 | Thursday | 1 AZAR
### [Part 1 | Microservices](https://drive.google.com/file/d/13gTnJHDamU7ph8-kiiSAzHCXUQHnfrip/view)
- Availability `12:50`
- Consistency `13:30`
- CAP theorem [Link](https://en.wikipedia.org/wiki/CAP_theorem) `14:00`
- Interview Questions `15:20`
- Before Microservice (Single Project) `17:00`
- Load Balancing `20:00`
- Planet Scale `26:00`
- xFood Services `30:45`
- Create Order Flow `39:45`
- ACID `47:15`
- OLAP `52:30`
- inter-service / process communication types: `55:00`
- Sequence Diagram `01:07:10`

### [Part 2 | Outbox & Poller](https://drive.google.com/file/d/1uYRwwlCfcjy8SglEt1g8XirdDK-Yupgx/view)
- Transactional Messaging `00:00`
- Outbox Pattern `01:20`
- Outbox Implementation Factors `12:41`
- Storage `14:55`
  - Apache Parquet [Link](https://parquet.apache.org/) `16:30`
- OLAP `17:25`
- Columnar Storage `19:30`
- Outbox Diagram `23:00`
- Poller `35:00`
  - Go Cron Package [Link](https://github.com/robfig/cron)
- Map of Microservices **Site** [Link](https://microservices.io/patterns/index.html)
- Mircoservices Patterns **Book** [Link](https://microservices.io/book)
- Idempotent `59:55`
- Event Lost = Zero `01:01:30`
- Partition Tolerance `01:04:10`
- Transaction log trailing `01:07:40`

### [Part 3 | Data Consistency & SAGA](https://drive.google.com/file/d/16cZ0-ZFOwt8QxMpQLkCh2UA4CzGjBRmZ/view?usp=sharing)
- Review `00:00`
- Transactions in a Monolith Architecture `04:00`
- Transactions in a Microservice Pattern `06:00`
- Real World Example `08:40`
- SAGA `10:47`
- Sequence Diagram `24:25`
- Choreography-based saga `28:40`
- Orchestration-based saga `29:11`
- Revert `32:00`
- Study [2PC](https://microservices.io/patterns/data/saga.html#forces)
- Event Sourcing `41:00`
  - Order Example for Event Sourcing `42:00`
- CQRS (Command Query Responsibility Segregation) `01:01:15`
- Separate write from read in DB `01:07:05`
- Replicate in DB `01:08:30`
  - Eventual Consistency `01:09:45`
- SQL Proxy `01:11:15`, `01:13:55` [Link](https://proxysql.com/)
- Multi Master in DB `01:12:00`
- Designing Data-Intensive Applications **Book** [Link](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- Database Internals **Book** [Link](https://www.amazon.com/Database-Internals-Deep-Distributed-Systems/dp/1492040347)
- Mongodb & Elastic & Sharding `01:19:00`
- Passing User Data between Services `01:22:10`
- How companies document technical conventions and contracts? `01:24:15`
- Q/A