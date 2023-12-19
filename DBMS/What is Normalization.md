- Normalization is used to minimize the redundancy from a table.
- Normalization divides the larger table into smaller and links them using relationships.
- The process of Normalization is achieved by following some rules which are defined as Normal Forms.
- There are basically 3 types of Normal Form – 1NF, 2NF, 3NF. Strictness increases as we go from 1NF to 3NF.
- Apart from that there exists 1 more Normal Form called Boyce Codd Normal Form (BCNF). This is an advanced version of 3NF.


## 1NF
Table should not contain multivalued attribute.
![[Pasted image 20231120043838.png]]
Solution : Increase the tables.


## 2NF
- The table must be present in 1Nf.
- All the non-Prime attributes should be fully functional dependent on Candidate Key. (means the attributes which are not participating in the formation of candidate key)
	![[Pasted image 20231120045349.png]]
	Store-Id and Location matches so it is dependent.


## 3NF
- The table must be present in 2NF.
- There should be no transitive dependency in the table. (means Non-Prime attributes should not determined by Non-Prime attributes. Non-Prime attributes only determined by Candidate Key).
	![[Pasted image 20231120050716.png]]
	![[Pasted image 20231120050754.png]]
	Roll no determining state & state determining city means roll no is determining city but it is derived by the transitive dependency. 