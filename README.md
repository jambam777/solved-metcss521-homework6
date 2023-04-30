Download Link: https://assignmentchef.com/product/solved-metcss521-homework6
<br>
In this assignment, you will be demonstrating your understanding and use of python classes and inheritance and polymorphism, as covered in module 6.

<a name="_Toc6926"></a>Assignment Background

This assignment makes use of inheritance to create a set of related classes.  At the end, you will have a more complex structure of parent-child classes than you saw in the module’s examples.

<a name="_Toc6927"></a>Assignment Statement

<ul>

 <li>You will create the following classes using inheritance:</li>

</ul>

o A base class called Pet o A mix-in class called Jumper o A Dog class and a Cat class that each inherit from Pet and Jumper o Two classes that inherit from Dog: BigDog and SmallDog o One classes that inherit from Cat: HouseCat

<ul>

 <li>The general skeleton of the Pet, Dog, and BigDog classes will be given to you, but you will have to identify the required inheritance for a class. You will be responsible for writing the functionality of those classes and their methods.</li>

 <li>A description of each class’s functionality, as well as the data to use, is in the requirements below.</li>

 <li>You will be required to write the code to exercise your classes per the requirements.</li>

</ul>

<h1><a name="_Toc6928"></a>Requirements</h1>

Use the provided template to complete the following.  The details are in the skeleton file.

<ol>

 <li>The Pet class:

  <ol>

   <li>Assign values to two variables: kind and color</li>

   <li>Implement the constructor to initialize the pet’s name</li>

   <li>Implement __str__ method per skeleton</li>

   <li>Implement do_tricks method per skeleton</li>

  </ol></li>

 <li>The Jumper class

  <ol>

   <li>Implement the jump method per the skeleton</li>

  </ol></li>

 <li>The Dog class

  <ol>

   <li>Decide which classes to inherit from and implement inheritance</li>

   <li>Change the kind to canine</li>

   <li>Implement __str__ per skeleton</li>

   <li>Implement __call__ per skeleton</li>

  </ol></li>

 <li>The BigDog class

  <ol>

   <li>Change the color to tan</li>

   <li>Implement __str__ per skeleton</li>

   <li>Implement speak per skeleton</li>

  </ol></li>

 <li>The SmallDog class

  <ol>

   <li>Change the color to brindle</li>

   <li>Implement __str__ per skeleton</li>

   <li>Implement speak per skeleton</li>

  </ol></li>

 <li>The Cat class

  <ol>

   <li>Change the kind to feline</li>

   <li>Implement __str__ per skeleton</li>

   <li>Implement speak per skeleton</li>

   <li>Implement climb per skeleton</li>

  </ol></li>

 <li>The HouseCat class

  <ol>

   <li>Change the color to white</li>

   <li>Implement __str__ per skeleton</li>

   <li>Implement speak per skeleton</li>

  </ol></li>

 <li>Create the code to exercise the class structure according to the following:

  <ol>

   <li>Instantiate each class(except Jumper)</li>

   <li>Create a list of the instantiated objects</li>

   <li>Loop through the objects</li>

   <li>For each object:

    <ol>

     <li>Print __str__</li>

     <li>print the kind of pet</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Print the Color of the pet</li>

</ul>

<ol>

 <li>Have the pet do tricks</li>

 <li>if applicable, print rollover action and the owners name</li>

 <li>If applicable, have the pet climb vii. To separate each pet, print a line of underscores or dashes</li>

</ol>

<h2>Sample Output</h2>

Your output should look something like this and should be in this order:




I am a brown animal named Rover animal brown

Rover is doing tricks

—————————————- I am a cat named Lion

feline

brown

Lion is doing tricks Lion says Meow!!!

Lion is jumping

<em>Lion is climbing the curtains again</em> – note climbing action is for Cats

—————————————-

I am a dog named Roo

canine brown

Roo is doing tricks

Roo is jumping

<em>Roo is rolling over</em> – note rollover and owner actions are for Dogs

<em>My owner is George</em>

—————————————- Noah is a large, muscular dog canine tan

Noah is doing tricks Noah says Woof!!! Noah is jumping

Noah is rolling over

My owner is George

—————————————- Lucky is a tiny, cute dog canine brindle

Lucky is doing tricks Lucky says Yip!

Lucky is jumping

Lucky is rolling over

My owner is George

—————————————- Zebra is a cat with fluffy, white fur feline white

Zebra is doing tricks

Zebra says Purr

Zebra is jumping

Zebra is climbing the curtains again

—————————————-




Process finished with exit code 0

<h1><a name="_Toc6929"></a>What to Deliver</h1>




You are required to supply a single file –  <em>emailID_hw6.py</em> (example: marc10is_hw6.py)




<h1><a name="_Toc6930"></a>Notes</h1>




<ul>

 <li>Start by identifying and ordering the objectives.</li>

 <li>Look at the skeleton – there is a lot of guidance in it. The amount you need to code is smaller than in our other assignments.  We want to make sure that you see how the different classes work together to show inheritance and polymorphism.  This would be way too big an assignment without the skeleton.</li>

 <li>The “exercising your pet” portion of this tests all the methods and classes created in this assignment. Your output should match the order of the sample output provided.  You can get “creative” – for instance, instead of “My owner is George”, feel free to say something along the lines of “My owner, George, is the BEST owner in the whole world” But it should all still print in the order below.</li>

 <li>A 25-point deduction for one day late. After 1 day late, a 0 will be given.</li>

</ul>


