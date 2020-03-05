# Book Store Entity-Relation Diagram
This is the first ER diagram that I've done.
It is my idea of an Entity Relation Diagram of a Book Store. <br /> 
This was done learning about the Fundamentals of Data Bases (Fundamentos de Bases de Datos) course from Platzi.

![BookStoreER](BookStore.PNG)

## First Iteration

I realized there was a need to create a break between Employees and Book Stores and to adjust some VARCHAR lengths

![1stIteration](1st.png)

## Second Iteration

Since one book can have availability in many stores and a book store is made of many books, I added a many-to-many cardinality. <br />
There was no need to have the SSN number from a customer, so I erased it. <br />
I consider is accurate to say Genre instead of Category. Table named "Categories" was changed to "Genres"

![2ndIteration](2nd.png)

# Firebase

Tried to re-create the DB in this NoSQL based on Documents. <br /> <br />
Top Level Collections: <br />
 - Customers <br />
 - Books <br />
 - Authors <br />
 - Genres <br />
 - Editorials <br />
 - Book Stores <br /> <br />

Sub-collections: <br />
- Employees (Sub-collection from Book Stores)

![Firebase](fireb.PNG)