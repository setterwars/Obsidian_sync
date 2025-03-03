
# Lecture 1.  Introduction to databases Basic Concepts. Data models, Databases design, The Entity-Relationship Model

**Data** -  is a collection of facts in a raw or unorganized form.

### Data, information, Knowledge, Wisdom( DIKW) pyramid
![[Pasted image 20250303191850.png]]

### File based systems

Manual file systems:
- Inadequate for processing of information in files 
- Inadequate for cross-reference
- Lack of security 
- Prone to be damage and misplaced 
- Hard to make change
- Takes up a lot of physical space
File based systems:
- Predecessor to the DBMS
- A collection of application programs that perform services for end-users
- Each program defines and manages its own data 


**Database** is a collection of related data. It describes the activity of one or more related organizations.

**Database Management Systems (DBMS)** is a computerized system that enable users to create and maintain a database. Designed to assist in maintaining and utilizing large collections of data. Primary goal of DBMS is to ***provide a way to store and retrieve database information that is both convenient and efficient.***

#### DBMS Advantages over file-processing systems
- Data redundancy and inconsistency
- Difficulty in accessing data
- Data isolation 
- Integrity problem
- Atomicity problem
- Concurrent-access
- Security issues

### Entity relationship model

- Entity: corresponds to a thing or object in the real world 
- Relationship: corresponds to a link between entities
- Attributes: a property that describes an entity

##### Entity keys:
- Primary key: A candidate key chosen by the database designer to uniquely identify the entity set
- Super key: A set of attributes(one or more) that together define an entity in an entity set
- Candidate key: A minima super key
An entity set may have more than one candidate key.

##### Cardinality ratios 
- on to may relation 
- one to one relation
- any to one relation
- many to many relation

Total participation(Indicate in ERD with a 2 lines) and Partial participation. In total participation each entity is involved in the relationship. Partial participation Not all entities are involved in the relationship.

Entity type that do have a key attribute - are called strong entity types.
Entity type that do not have a key attributes of their own are called weak entity types

Weak relationship is a connection that exist between a weak entity type and its owner. 

## Tutorial 1
