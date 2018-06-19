#README.txt
#Author: Allie Miranda

1) Let's talk about variables (cont.)
   So, in 2a, we went over the various kinds of data types.
   Try to think about what a data type is, and how it is important.
   Now, we will talk about variables in JS and how we declare them.

2) Const -
   a) Write the following lines of code in your .js file:
      const bar1 = 3;
      document.write(bar1);
      What do you think will happen, when you run it?
      So a const, is a variable that maintains a constant value.
   b) If you were to reassign bar1, it would crash and nothing would happen.
      Try it!  Place the following in your .js file (before the print):
      bar1 = 4;
      What do you think will happen? **Hint: I already told you!!**

3) Var -
   a) Write the following in your .js file:
      var bar2 = 7;
      document.write(bar2);
      What do you think will happen?
      A var is a variable that can be mutated(changed in some way).
      A var can be declared as an integer and then changed to be another data type
      A var is a *global* variable.
      This means that when the var changes within a method, it will change throughout the whole program.
   b) Try to reassign bar2:
      bar2 = 8;
      What will change this time?

4) Let -
   a) Write the following in your .js file:
      let bar3 = "Hello World!";
      document.write(bar3);
      What do you think will happen?
      let is a way to declare a variable within a certain scope.
      This means that when you change a let variable, it will only change within that scope.
   b) Write the following into your .js file(before document.write()):
      if(true){
         let bar3 = false;
         document.write(bar3);
      }
      What do you think will happen?
      [Don't get caught up in the if statement, I cover that later.]
   c) ***Note: in order to change a let variable within a small scope, you must reinitialize it***
      For instance, type the following into your .js file:
      if(true){
         bar3 = "some number";
         document.write(bar3);
      }
      document.write(bar3);
      What do you think will happen?
      Try it!

Don't forget to check out the html file!
I will continue to add to it as the tutorials go on!
Html is NOT a programming language, but more like a markup language.
This means that HTML is for design purposes only, its not programmable.
So, check it out! [This time I showed you about paragraphs!]
