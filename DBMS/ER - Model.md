- Stands for **Entity-Relationship (ER) Model.**
- Used for designing and representing the structure of a database.
- Explains the relationship among the entities present in the database.

## Symbols Used in ER Model
- ****Lines:**** Represent relationships between two entities.
- ****Double Ellipse:**** Double Ellipses represent [Multi-Valued Attributes]. Eg : Phone No.
![[Pasted image 20231119234539.png]]

## Components of ER Diagram
ER Model consists of Entities, Attributes, and Relationships among Entities in a Database System.

![[Pasted image 20231119235739.png]]

## Entity
Entity in DBMS can be a real-world object with an existence, For example, in a College database, the entities can be Professor, Students, Courses, etc.

#### Types of Entity Type:
Collection of the entity having similar attributes.
	
-  **Strong Entity Type**:
	Strong entities are those entity types which have a key attribute. The primary key helps in identifying each entity uniquely. It is represented by a rectangle.
	
- **Weak Entity Type**: 
	Weak entity type doesn’t have a key attribute. Weak entity types can’t be identified on their own. It depends upon some other strong entity for its distinct identity.
	
#### Entity Set 
Entity Set is a collection of entities of the same entity type. We can say that entity type is a superset of the entity set.


-------------------------------------------------------------------------------
## Attribute
Properties that define the entity. For example, Roll_No, Name, DOB.

-  ****1. Key Attribute****
	
	The attribute which ****uniquely identifies each entity**** in the entity set is called the key attribute. For example, Roll_No.
	The key attribute is represented by an oval with underlying lines.
	![[Pasted image 20231120000200.png]]
	
-  ****2. Composite Attribute****
	
	An attribute ****composed of many other attributes**** is called a composite attribute. For example, the Address attribute consists of Street, City, State, and Country.
	The composite attribute is represented by an oval.
	![[Pasted image 20231120000411.png]]
	
-  ****3. Multivalued Attribute****
	
	An attribute consisting of more than one value for a given entity. For example, Phone_No (can be more than one for a given student).
	A multivalued attribute is represented by a double oval.
	![[Pasted image 20231120000533.png]]
	
-  ****4. Derived Attribute****
	
	An attribute that can be derived from other attributes of the entity type is known as a derived attribute. e.g.; Age (can be derived from DOB).
	The derived attribute is represented by a doted oval.
	![[Pasted image 20231120000642.png]]

-------------------------------------------------------------------------------

## Relationship

### Types of relationship
	
- **Unary Relationship Set –** Unary relationship set is a relationship set where only one entity set participates in a relationship set.
	
- **Binary Relationship Set –** Binary relationship set is a relationship set where two entity sets participate in a relationship set.
	
- **Ternary Relationship Set –** Ternary relationship set is a relationship set where three entity sets participate in a relationship set.
	
- **N-ary Relationship Set –** N-ary relationship set is a relationship set where ‘n’ entity sets participate in a relationship set.

### Cardinality Relationship

- One to One
	![[Pasted image 20231120001547.png]]
	
- One to Many
	![[Pasted image 20231120001638.png]]

- Many to One
	![[Pasted image 20231120001728.png]]
	
- Many to Many
	![[Pasted image 20231120001848.png]]
