## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/alexander-varljen/alexander-varljen.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Welcome to Alex Varljen's GitHub Pages webpage

This webpage contains software artifacts worked on by Alexander Varljen. Alex's areas of
interest include programming, data analysis, and data science. Please review the sources
below and feel free to click the links provided to my public GitHub page containing my 
program files.

### Code Review

Link to Code Review Video:

[Zipped File Version Link](https://drive.google.com/file/d/19qB4ywqz7rjAAgLcKoWCNpRRDYibPWUh/view?usp=sharing)

[MOV File Version Link](https://drive.google.com/file/d/10cxJDtofgnS_sbGbILLz1FpD3kXjxyGa/view?usp=sharing)

### Artifact Enhancement One: Banking Program 

Link to Public Page with the source file (
[artifactone.zip](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifactone.zip) )

**Banking Program's Flowchart**

![Image](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifactoneimage.png)

**Description of the Artifact:**

The artifact demonstrating my software development/engineering skills, which was created between 
July 10 and July 17, 2022, is a Python reconstruction of a banking application’s C++ source code,
which is from a project that I had worked on in a previous course. This artifact presents a menu
which asks the user to give an initialinvestment amount, a monthly deposit amount, an annual 
interest rate, and the number of years (up until five years) in which they wish to see the change
in their endof year balance and accrued interest. Then, the calculations are made based on the 
users input and an output display is made.

**Why This Artifact was Chosen:**

I chose this artifact because it demonstrates my Python programming skills, which is a language 
commonly used in data analysis and data science, my main fieldsof interest. The range of Python 
programming techniques employed in this enhancement include user defined functions for subprocesses 
such as checking and receivingvalid inputs, input receivers, while-loops, conditional statements, 
output displays, and basic arithmetic operations for calculating the year-end balance and interest.
Also, through working on this artifact, I was able to secure the integrity of the software more 
faithfully by including exception handling for user inputs, which wasnot included in the original 
C++ project. This demonstrates my ability to develop more secure, functional, and reliable software.

**Artifact Enhancement and Course Objectives:**

My main objectives for this specific enhancement where to take my old project, give like functionality
to the source code written in Python, make it more secure, and to add clearer and more concise code 
comments for the benefit of other developers and reviewers of the source code. I believe that I met 
all those objectives while working on this artifact, as this program has the same functionality as 
the old C++ project and multiple try-catches were employed for exception handling around areas that
accept input and do calculations. There were also four course outcomes for this enhancement that I 
was to try and achieve, which are the following:

1.	Employ strategies for building collaborative environments that enable diverse audiences to 
	support organizational decision making in the field of computer science.
2.	Design, develop, and deliver professional-quality oral, written, and visual communications
	that are coherent, technically sound, and appropriately adapted to specific audiences and 
	contexts.
3.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in 
	computing practices for the purpose of implementing computersolutions that deliver value 
	and accomplish industry-specific goals (software engineering/design/database).
4.	Develop a security mindset that anticipates adversarial exploits in software architecture 
        and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy
	and enhanced security of data and resources.
	
With regards to achieving the first of these four course outcomes, I was able to create many 
descriptive code comments throughout the program explaining the programs functionality, create
a description of the program at the top of the source file, and add modularity by using various 
user defined functions throughout the program. These features grant programmers and reviewers the 
ability to look through the program and make sense of it, which can make it easier for them to 
change, add to, or understand the program. In terms of reaching the second course outcome, this 
document, as well as an in-program code comment at the top of the source file providing a 
description, seeks to explain the accompanying Python banking program artifact using accurate 
and comprehensive language. In terms of reaching the third course outcome, I was able to create
a working program that does what it is meant to do, which is to take in four user inputs, use
them to calculate end of year balance and interest, and display the results to the user. Also,
I sought to use well-founded techniques, such as creating user-defined functions to handle 
subprocesses and exception handling to check for potential errors and bugs. These cases of
exception handling, which can be found in all functions that take in input and perform
calculations, also aided me in achieving the final of the four course outcomes.

### Artifact Enhancement Two: Storing and Sorting Bids

Link to Public Page with the source file (
[artifacttwo.zip](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifacttwo.zip) )

**Storing and Sorting Bids Program Flowchart (Original)**

![Image](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifacttwooriginalflowchart.png)

**Storing and Sorting Bids Program Flowchart (Enhancment)**

![Image](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifacttwoenhancementflowchart.png)

**Description of the Artifact:**

The original project from which this artifact enhancement was taken from was called “CS 260 
Data Structures and Algorithms: Hash Tables and Chaining”, which I created for an assignment
back in February of 2021. The goal of the project was to create a program that, via four menu
options, allowed the user to load bid data from a csv file into a Hash Table data structure,
display all the bids from within this data structure, find one bid from the list stored in the
Hash Table, and remove one bid from the Hash Table. My enhancement to this artifact was adding
vector sorting capacity with four new menu options, one for loading the bids into the vector
that was used for the vector sorting, one for displaying all the bids in this vector, one for
sorting the bids in that vector via selection sort, and one for sorting the bids in that
vector via quick sort. This enhancement was made in the third week of July in 2022.

**Why This Artifact was Chosen:**

I selected this artifact as my algorithms and data structures enhancement because it demonstrates
my ability to store and manipulate data using multiple forms of data structure and different
algorithms. These included an unmapped vector containing bid data and a mapped, or “hashed”,
vector, also containing the bid data from a csv file. The unmapped vector was used by the vector
sorting algorithms “quick sort” and “selection” sort, with selection sort being a simpler, but
less efficient, algorithm and selection sort being a more complex but more efficient sorting
algorithm, both of which were used to sort the bid data in ascending order. The mapped, or
“hashed”, vector is a more complex vector to construct, but provides a much faster and more
efficient way of finding an item, like a bid, than compared to using an unmapped vector. By 
including both types of vectors and their corresponding algorithms in this project, I was able
to demonstrate that I can work with multiple algorithms and data structures, which each have 
their trade-offs, but can be utilized for different problems and desired outcomes.

**Course Objectives:**

As far as what I wanted to complete for this specific artifact, which was to add vector
sorting capacity to the old project, as well as more menu options that allow the user to
use the vector sorts, I have completed this main objective. In addition to the hash table
data structure storing bid data and allowing for the finding or removal of single bids, there
is now two working vector sorting algorithms that a user can use to sort the list of bids in
ascending order. There where also four course outcome objectives that apply to this 
enhancement which were to:
1.	Employ strategies for building collaborative environments that enable diverse audiences
        to support organizational decision making in the field of computer science.
2.	Design, develop, and deliver professional-quality oral, written, and visual 
        communications that are coherent, technically sound, and appropriately adapted to 
	specific audiences and contexts.
3.	Design and evaluate computing solutions that solve a given problem using algorithmic
        principles and computer science practices and standards appropriate to its solution, 
	while managing the trade-offs involved in design choices.
4.	Develop a security mindset that anticipates adversarial exploits in software 
        architecture and designs to expose potential vulnerabilities, mitigate design flaws, and
	ensure privacy and enhanced security of data and resources.
	
As far as completing the first objective, I was able to add plenty of comments and a description
of the program’s functionality to the artifact, as well as many user-defined functions for
modularity. These can make it easier for any programmer looking to review, add to, or change
components of the program to do so. As far as achieving the second course objective, this 
document explains what the artifact is and what the enhancements were using technically sound
terms and descriptions. In alignment with the third course objective, I was able to properly
provide the ability to load data from a csv file and allow a user to display all the data, remove
specific items, find specific items, and sort items in a data structure using two data structures
and multiple algorithms which grant these capabilities. Also, with regards to the last of the
course objectives, I was able to employ multiple examples of exception handling for bugs or errors
in processing data. More, specifically, these can be found as part of the methods that contain code
loading the csv file to the mapped and unmapped vectors.  

**Reflection:**

As part of the process of completing my enhancements to this artifact, I had to look over the
program thoroughly to understand how it works, what enhancements where possible without changing
the whole program, and, when those enhancements were decided on, what programming decisions would
be necessary to complete those enhancements. This was made easier by my familiarity with C++,
which is the programming language that I am most familiar with. While going through this process
of reviewing the projects code, I noticed that the Hash Table data structure doesn’t easily lend 
itself to vector sorting, so I added an additional vector. This became central to many of my other
programming decisions, which includes four new menu options and an extra algorithm for loading the
new vector with the csv file data. I don’t believe that a set of menu options like this would
normally take place. However, I wanted to display multiple forms of data structures and algorithms
while using the same source of data and the same theme of the program, which was storing, adding to,
removing, and looking up bids. So, to have a coherent program with one main theme while still
demonstrating multiple data structures, I added a second set of options that were labeled differently
for the users benefit. 

### Artifact Enhancement Three: QuantigrationUpdates Database

Link to Public Page with the source file (
[artifactthree.zip](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifactthree.zip) )

**Quantigration Updates MySQL Database UML Diagram**

![Image](https://github.com/alexander-varljen/alexander-varljen.github.io/blob/main/artifactthreemysqldiagram.png)

**Quantigration Updates MongoDB Database UML Diagram**



**Description of Artifact**

The original project from which the artifact enhancement was taken was called “DAD 220 Project One”,
which I created for an assignment back in August of 2020. The goal of this project was to create a
database called “QuantigrationUpdates” with three tables called “Customers”, “Orders”, and “RMA”,
query their records, update their records, delete their records, and download the records from the
“Orders” table onto a csv file using MySQL. My enhancement to this artifact was creating a similar 
database, also called “QuantigrationUpdates”, with three collections that contain the same fields,
use similar queries, updates, deletions, and a download while using MongoDB commands on a MongoDB
shell. My enhancement also included adding two levels of user accounts to provide extra security to
the database. This enhancement was completed in the last week of July 2022.

**Why This Artifact Was Chosen**

I chose this artifact because it allowed me to show a range of CRUD skills with Databases using
MongoDB, a popular database tool. By using MongoDB commands, I was able to create a database for a
fictional business with three collections, each containing multiple fields of data, as well as create
a view of one of the collections. I was also able to add records to each database using correct
commands, display records with queries, update specific records using query and update commands, and
delete records using query and delete commands. I was also able to export a collection to a csv file
with a MongoDB command. I was also able to go beyond the functionality of the original project by
adding password secured user accounts.

**Course Objectives**

My main objectives with this artifact enhancement where to recreate all the functionality of the
original SQL project while adding more security using a MongoDB shell and tools. I was able to 
successfully complete these objectives. There where also four course outcomes that apply to this 
enhancement, which were to:
1.	Employ strategies for building collaborative environments that enable diverse audiences to
        support organizational decision making in the field of computer science.
2.	Design, develop, and deliver professional-quality oral, written, and visual communications 
	that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
3.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in
        computing practices for the purpose of implementing computer solutions that deliver value and
	accomplish industry-specific goals.
4.	Develop a security mindset that anticipates adversarial exploits in software architecture and 
        designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and 
	enhanced security of data and resources.
	
As far as completing the first course outcome is concerned, I was able to take screenshots of my
command terminal and explain why each of the commands were used. I will also download the three csv
files used for each collection so that others wishing to learn or test my work can rerun the same
commands with the same data sets and see the results. As far as completing the second course outcome
is concerned, I formed my explanations written in the document containing my enhancement’s
screenshots, as well as the enhancement’s description in this narrative, so that others could follow
along and understand my MongoDB commands and what they were used for. As far as the third course
outcome is concerned, I was able to correctly use MongoDB commands to create a database containing
three collections, query the database, update it, add records to it, delete records from it, and download
a collection from it. MongoDB is a well-respected set of software tools designed to work with structured
and unstructured data and databases. As far as the fourth course outcome is concerned, I was able to
add two accounts secured via a password that granted two levels of access to the Mongo Server that
was used in creating the “QuantigrationUpdates” database. 

**Reflection**

Since I’d already learned how to use MongoDB commands previously, much of the new knowledge I gained
from working on this enhancement has been while adding a local Mongo shell, Mongo Server, and other
necessary tools to my computer. This was also the main source of the challenges that I had in completing
this project, as I have never downloaded and used MongoDB tools on my local device before. However,
after seeking help from tech support, the internet, and some trial and error, I was able to use my 
own working MongoDB shell and server to complete this artifact enhancement. 

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

theme: jekyll-theme-slate
title: Welcome to alexander-varljen's homepage!
description: Feel free to bookmark this to keep an eye on my project updates

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/alexander-varljen/alexander-varljen.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
