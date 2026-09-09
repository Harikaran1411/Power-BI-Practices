\# Data Modeling \& Relationships



\## Topics Practiced



\- Power BI Model view

\- Creating relationships between tables

\- Identifying common keys

\- One-to-many relationships

\- Relationship cardinality

\- Relationship direction

\- Using fields from related tables in visuals



\## Example Data Model



Customer

&#x20;   |

&#x20;   | Customer\_ID

&#x20;   |

&#x20;   ↓

Orders



The Customer table acts as a lookup/dimension table, while the Orders

table contains transactional data.



\## Relationship



Customer\[Customer\_ID] → Orders\[Customer\_ID]



Relationship type:



One-to-Many (1:\*)



\## What I Learned



Data modeling helps connect related tables so that data can be analyzed

together in Power BI.



A proper relationship allows fields from related tables to be used

together in reports and visualizations.



\## Tool Used



\- Microsoft Power BI Desktop

