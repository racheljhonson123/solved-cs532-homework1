Download Link: https://assignmentchef.com/product/solved-cs532-homework1
<br>
<ol>

 <li> Design an ER diagram for the Student Registration System based on the provided Requirements Document (see blackboard). Remember to indicate the key for each entity set and the connectivity of each relationship. Use (min, max) format to indicate connectivity. (Note 1: Hand-drawing diagram is acceptable but it must be neat and easy to read. Note 2: For unary relationship, adding role information is often helpful in attaching the correct connectivity information with the right relationship link/edge. Note 3: Some constraints cannot be represented in the ER diagram naturally, no need to design un-natural structures in the ER diagram just to represent such constraints. You can get additional clues on such constraints from Question 2. These constraints will be represented at later stages of the database design. Question 2 of this homework asks you to list these constraints.)</li>

 <li>Identify constraints in the Requirements Document for the Student Registration System that cannot be naturally expressed using the ER model discussed in class. First list the constraints not represented in your ER diagram for each entity set separately. Then list the unrepresented constraints involving multiple entity sets or some relationship.</li>

</ol>

The following are some examples (please include them in your answer):

Constraints that cannot be naturally represented in the ER diagram:

Students:

Valid values for status (freshman, sophomore, junior, senior, MS, PhD).

Valid values for gpa (decimal number between 0 and 4). Students have unique email addresses (additional keys).

The actual size of a class must not exceed the limit of the class.       No faculty member can teach classes with overlapping times.

<ol start="3">

 <li> Discuss whether or not it is a good idea to create a super entity set for Students and Faculty in the ER diagram for the Student Registration System.</li>

 <li> Discuss whether or not it is a good idea to make TAs a sub entity set of Students in the ER diagram for the Student Registration System.</li>

</ol>


