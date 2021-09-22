# MARKETPLACE_ASTERIX
REST API for managing products on a marketplace.  A RESTful API created using Spring boot. A Marketplace that allows to register a new user or login with created one and to manage products.

TEAM: Bivol Gavril W-1841
WIKI LINK: https://en.wikipedia.org/wiki/Representational_state_transfer

## Getting Started

Marketplace is a simple platform where people
regularly gather for the purchase and sale of goods. 
It uses a relational database (PostgreSQL) to store the data. 
To secure endpoints, I've used bearer key provided by 
jjwt library, and configured with swagger3. MyBatis was used to
perform CRUD operation with database. At the last, FlyWay guarantees
database migration to future versions.
All APIs are "self-documented" by OpenApi3, using annotations.

Roles: Bivol Gavril - developer, tester, team lead/manager, technical writer, analist, consultant

![image](https://user-images.githubusercontent.com/68549495/134401398-c46969b4-7b3c-4d90-a8af-2272e1e1db2f.png)
