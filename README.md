# Project01-2020ICT101
IT1214 - Object-Oriented Design And Programming [Project-01]

## Question:

<p>
You have been assigned to develop a Library Management System for a public library. Design and implement the necessary classes to support the system using the concepts of class, objects, abstraction, inheritance, encapsulation, and polymorphism. Your implementation should include the following
</p>
<ol>
<li>
LibraryItem (abstract class)
<ul>
<li>
Properties:
<ul>
<li><b>title</b> (String): the title of the library item.</li>
<li><b>itemID</b> (String): a unique identifier for the library item.</li>
</ul>
</li>
<li>
Methods:
<ul>
<li><b>checkOut():</b> marks the library item as checked out.</li>
<li><b>checkIn():</b> marks the library item as checked in.</li>
<li><b>displayItemDetails():</b> displays the details of the library item.</li>
</ul>
</li>
</ul>
</li>

<li>
Book (subclass of LibraryItem)
<ul>
<li>
Additional Properties:
<ul>
<li><b>author</b> (String): the author of the book.</li>
<li><b>numPages</b>  (int): the number of pages in the book.</li>
</ul>
</li>
</ul>
</li>
<li>
Magazine (subclass of LibraryItem)
<ul>
<li>
Additional Properties:
<ul>
<li><b>issueDate</b> (String): the issue date of the magazine.</li>
<li><b>publisher</b> (String): the publisher of the magazine.</li>
</ul>
</li>
</ul>
</li>
<li>
LibraryMember
<ul>
<li>
Properties:
<ul>
<li><b>memberID</b> (String): a unique identifier for the library member.</li>
<li><b>name</b> (String): the name of the library member.</li>
</ul>
</li>
<li>
Methods:
<ul>
<li><b>displayMemberDetails()</b>: displays the details of the library member</li>
</ul>
</li>
</ul>
</li>
</ol>

<p>
Implement the above classes and write the necessary code to demonstrate the following functionality:
</p>
<ol>
<li>Create 5 objects of the Book class, each representing a different book in the library.</li>
<li>Create 5 objects of the Magazine class, each representing a different magazine in the library.</li>
<li>Create 5 objects of the LibraryMember class, each representing a different member of the library.</li>
<li>Set the properties of the objects using appropriate setter methods.</li>
<li>Call the checkOut() and checkIn() methods on one of the library items.</li>
<li>Display the details of all the library items and library members.</li>
</ol>

Books:

| Title | Item ID    | Author   |Number of Pages|
| :---:   | :---: | :---: |:---: |
| The Catcher in the Rye | B001   | J.D. Salinger	|240 |
| To Kill a Mockingbird | B002   | Harper Lee   | 281 |
| 1984 | B003   | George Orwell   | 328 |
| Pride and Prejudice | B004   | Jane Austen   |432 |
| The Hobbit | B005   | J.R.R. Tolkien   | 320 |

Magazines:
Title	|Item ID |	Issue Date |	Publisher|
| :---:  | :---: | :---: |:---: |
|National Geographic| M001|	August 2023|	National Geographic Society|
|Time|	M002|	September 2023	|Time USA, LLC|
|Forbes|	M003|	June 2023|	Forbes Media|
|Vogue|	M004|	July 2023	|Condé Nast|
|Sports Illustrated|	M005	|July 2023|	Maven Coalition|
 
Library Members:

|Member ID|	Name|
| :---: |:---: |
|L001	|John Doe|
|L002	|Jane Smith|
|L003	|David Johnson|
|L004|	Sarah Williams|
|L005	|Michael Brown|


## Output:

<pr>
	
	Microsoft Windows [Version 10.0.22621.1992]
	(c) Microsoft Corporation. All rights reserved.

	D:\UOV\Semester-2\Subjects\IT1214 - ObjectOrientedDesignAndPrograming\Projects\Project-01\2020ICT101 [Project-01]>javac LibraryManagementSystem.java

	D:\UOV\Semester-2\Subjects\IT1214 - ObjectOrientedDesignAndPrograming\Projects\Project-01\2020ICT101 [Project-01]>java LibraryManagementSystem
	Title of the book: The Catcher in the Rye
	Item ID of the book: B001
	The book checked out or not: true
	Author of the book: J.D.Salinger
	Number of pages: 240
	Title of the book: The Catcher in the Rye
	Item ID of the book: B001
	The book checked out or not: false
	Author of the book: J.D.Salinger
	Number of pages: 240

	Books:
	Title of the book: The Catcher in the Rye
	Item ID of the book: B001
	The book checked out or not: false
	Author of the book: J.D.Salinger
	Number of pages: 240
	Title of the book: To Kill a Mockingbird
	Item ID of the book: B002
	The book checked out or not: false
	Author of the book: Harper Lee
	Number of pages: 281
	Title of the book: 1984
	Item ID of the book: B003
	The book checked out or not: false
	Author of the book: George Orwell
	Number of pages: 328
	Title of the book: Pride and Prejudice
	Item ID of the book: B004
	The book checked out or not: false
	Author of the book: Jane Austen
	Number of pages: 432
	Title of the book: The Hobbit
	Item ID of the book: B005
	The book checked out or not: false
	Author of the book: J.R.R.Tolkien
	Number of pages: 320

	Magazines:
	Title of the book: National Geographic
	Item ID of the book: M001
	The book checked out or not: false
	Issue Date of the book: August 2023
	Publisher of the book: National Geographic Society
	Title of the book: Time
	Item ID of the book: M002
	The book checked out or not: false
	Issue Date of the book: September 2023
	Publisher of the book: Time USA, LLC
	Title of the book: Forbes
	Item ID of the book: M003
	The book checked out or not: false
	Issue Date of the book: June 2023
	Publisher of the book: Forbes Media
	Title of the book: Vogue
	Item ID of the book: M004
	The book checked out or not: false
	Issue Date of the book: July 2023
	Publisher of the book: Condé Nast
	Title of the book: Sports Illustrated
	Item ID of the book: M005
	The book checked out or not: false
	Issue Date of the book: July 2023
	Publisher of the book: Maven Coalition

	Library Members:
	Member ID: L001
	Name: John Doe
	Member ID: L002
	Name: Jane Smith
	Member ID: L003
	Name: David Johnson
	Member ID: L004
	Name: Sarah Williams
	Member ID: L005
	Name: Michael Brown

	D:\UOV\Semester-2\Subjects\IT1214 - ObjectOrientedDesignAndPrograming\Projects\Project-01\2020ICT101 [Project-01]> 
	
</pr>
