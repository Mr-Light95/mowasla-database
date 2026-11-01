# Mowasla Database Design

A coursework database design and SQL query reference for a transportation service.

## Project focus

The supplied design models passengers, drivers, vehicles, rides, routes, locations, wallets, transactions, payments, feedback and administrators. The query reference covers filtering, joins, aggregation, inserts and updates using SQL Server style syntax.

## Query examples covered

- Passenger and driver ride histories and ride details.
- Driver vehicle information and ratings.
- Wallet balances, transactions and payment records.
- Driver earnings and route usage reports.
- Ride status changes, passenger registration and feedback submission.

## Project documents

- [SQL query reference](MOWASLA_SQL_Queries.pdf): original six-page query reference with query purposes.
- [Entity relationship diagram PDF](Mowasla_ER_Diagram.pdf): original diagram spread across four pages.
- [Full diagram image](Mowasla_ER_Diagram.png): supplied overview image.

![Mowasla entity relationship overview](Mowasla_ER_Diagram.png)

## Current scope

This repository presents **database design and query documentation**, not a completed transportation application. The supplied application folders contain placeholder files. No database creation script, backup, populated database or runnable application was supplied, so queries have not been executed or validated against a live schema.

The design and query reference need reconciliation before implementation: for example, the queries use `Location.street` while the diagram lists an address attribute, and some query columns are not shown in the conceptual diagram. The illustrated login queries use profile information rather than a secure authentication mechanism and should not be treated as production login code.

## Skills demonstrated

Entity relationship modeling, relational database concepts, SQL joins, filtering, aggregation and data manipulation.
