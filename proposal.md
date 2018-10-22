# X-Team 52 Baked Goods Project

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

We buy a certain amount of ingredients that are usually used to bake like flour, sugar, and milk. It is for a bakery sale at school and we must bake cookies, cake, and other items. We need a master list of resources and need to divide them up appropriately in order to make sure we have enough for all required items.
We will use an ArrayList (or other similar data structure) to assign students to what they need to make/bring in for the event. Each item will be a binary search tree (or other similar tree structure) and will have one student be in charge (be the root node) of the group. The tree could assign students to the left or right node depending on what they are able to bring to make sure the group accomplishes their specified task.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)



2. Output: Describe the output your program will produce.  Include and example format of the output produced.
The output for the program will give the leader of each category of baked goods (cake, cookie, etc.). Under that leader, then we will have the students's contribution to the event. Each node will have multiple fields for the specific student: name, phone number, and ingredients amount.

Ex:

Item1: chocolate cookeis

stu A: Abby 

 student id: 123
 
 phone: 6081117888
 
 ingredients of goods: 2 pounds flour, 0 pounds butter, 15 pounds sugar
 
 voluteer time: 2.5 h
 
stu B: Bob

 student id:456
 
 phone: 6081117886
 
 ingredients of goods: 0 pounds flour, 1 pounds butter, 1.5 pounds sugar
 
 voluteer time: 0.5 h
 
stu C: Cate

 student id:789
 
 phone: 6081117889
 
 ingredients of goods: 1 pounds flour, 4 pounds butter, 3 pounds sugar
 
 voluteer time: 1.5 h



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
The input of the program will start off by asking which tree the student should be placed in (i.e. asking which group they are going to be responsible for making an item with). We will then need to input the student's name (as a string) and phone number (probably as an int). Next each student node being added will have to specify the amount of ingredients they are bringing (how much flour/milk/eggs/sugar/etc.). They will be organized in the BST according to the total amount of ingredients they are bringing. Because we do not want the leader of each group to change we chose not to use an AVLTree like we originally planned.

Ex:
Which item will this student help bring for the event? 1.Cake 2.Cookies 3.Brownies    input: 1
What is the student's name?    input: Dep Deppeler
What is this student's phone number?    input:6088675309
How many hours can this student volunteer the day of the event?    input: 2.5
How much flour can this person bring?    input: 2 pounds
How much butter can this person bring?    input: 0 pounds
How much sugar can this person bring?    input: 15 pounds
Student has been added to the group.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Student name and category will be Strings. Phone number, ids, and amount of ingredients will be ints.


Name each interface or class and briefly describe its function or purpose.
Student class: Will contain all of the important fields for each BST (student name, id, phone number, and ingredients amount).

## Edit and Submit this file and any figures referenced by this document.

