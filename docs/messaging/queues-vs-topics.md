\# Queues vs Topics



\## Queue



A message is processed by a single consumer.



Producer

&#x20;   ↓

&#x20;Queue

&#x20;   ↓

Consumer



\### Characteristics



\- Load balancing

\- Work distribution

\- One-time processing



\## Topic



A message can be consumed by multiple consumers.



&#x20;           Consumer A

Producer → Topic

&#x20;           Consumer B

&#x20;           Consumer C



\### Characteristics



\- Publish/Subscribe

\- Event distribution

\- Multiple subscribers



\## When to Use Queues



\- Task processing

\- Batch jobs

\- Order processing



\## When to Use Topics



\- Event streaming

\- Notifications

\- Analytics

