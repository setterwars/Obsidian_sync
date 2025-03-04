#forMidterm
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
Requirements Engineering
In ERD we use Chen notation.

---

# Lecture 2. Data Modeling (EER diagrams)

#### Enhanced Entity Relationship Diagram (EERD)


Concept: Superclass and subclass

##### Constrains and characteristics

- Disjoint (d) - Subclass a mutually exclusive
- Overlapping(o) - Subclass can overlap; an entity can belong multiple subclass
- Total specialization - Every superclass entity must belong to at least one subclass. Shown in EER diagrams by a double line
- Partial specialization - Superclass entities do not have to belong to any subclass.Shown in EER diagrams by a single line.
![[Pasted image 20250303200746.png]]

---

# Lecture 3. Relational model and Relational algebra

### Relational model

In the relational model all data must be stored in relations. Each relation consists of rows and columns. 

##### Relational model constrains

- Inheritance model-based constrains 
- Schema based constrains 
- Application based constrains 
- Semantic Integrity Constrains


#### Relational model operations
- Delete
- Update

### Relational algebra

##### Operators:
 - Basic operators 
	 - Unary operators
		 - Projection 
		 - Selection 
		 - Rename
	 - Binary operators
		 - Union 
		 - Cross product 
		 - Minus/Set difference
 - Extended / Derived operators 

##### Select
To select we use $\sigma$. Also we can use operations like OR, AND,NOT
###### Project 
To project we use $\pi$. 

We can use project and select to see some part of relational model:

**$\pi (\sigma (A > 100) A-numbers))$**

###### Rename
to rename we use $p$

Relational algebra operations can be used with sets theory.  We can use Union, Intersection and Minus operations.

Cross Product, Join, Division operation.

### Tutorial 

##### Cartesian product:
![[Pasted image 20250303202405.png]]


##### Joins 

![[Pasted image 20250303202445.png]]

---
# Lecture 4. From ERD to relational scheme to SQL


### Rules with Relationship

![[Pasted image 20250304123844.png]]
![[Pasted image 20250304123853.png]]
![[Pasted image 20250304123904.png]]
![[Pasted image 20250304123916.png]]
