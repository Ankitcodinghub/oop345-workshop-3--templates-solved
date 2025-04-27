# oop345-workshop-3--templates-solved
**TO GET THIS SOLUTION VISIT:** [OOP345 Workshop 3- Templates Solved](https://www.ankitcodinghub.com/product/oop345-workshop-3-templates-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;108319&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;OOP345 Workshop 3- Templates Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this workshop, you design and code several class templates and test them on different instantiations.

Learning Outcomes

Upon successful completion of this workshop, you will have demonstrated the abilities to:

instantiate a template class

specialize a member function of a templated class to process a particular type derive a templated class from another templated class design and code a class template template a class variable specialize a templated class variable for a particular type

Submission Policy

The workshop is divided into two coding parts and one non-coding part:

Part 1: worth 0% of the workshop’s total mark, is optional and designed to assist you in completing the second part.

reflection: non-coding part, to be submitted together with Part 2. The reflection does not have marks associated to it, but can incur a penalty of max 40% of the whole workshop’s mark if your professor deems it insufficient (you make your marks from the code, but you can lose some on the reflection).

If the file contains only your work, or work provided to you by your professor, add the following message as a comment at the top of the file:

I have done all the coding by myself and only copied the code that my professor provided to complete my workshops and assignments.

If the file contains work that is not yours (you found it online or somebody provided it to you), write exactly which parts of the assignment are given to you as help, who gave it to you, or which source you received it from. By doing this you will only lose the mark for the parts you got help for, and the person helping you will be clear of any wrong doing.

Compiling and Testing Your Program

All your code should be compiled using this command on matrix: bash /usr/local/gcc/10.2.0/bin/g++ -Wall -std=c++17 -g -o ws file1.cpp file2.cpp …

-Wall: compiler will report all warnings

-std=c++17: the code will be compiled using the C++17 standard

-g: the executable file will contain debugging symbols, allowing valgrind to create better reports -o ws: the compiled application will be named ws

After compiling and testing your code, run your program as following to check for possible memory leaks (assuming your executable name is ws):

bash valgrind ws

To check the output, use a program that can compare text files. Search online for such a program for your platform, or use diff available on matrix.

Part 1 (0%)

This workshop consists of the following modules: – w3 (supplied) – Dictionary (partially supplied) – Queue

Have all your code inside the sdds namespace, and protect against double multiple inclusions.

You will have to create the Dictionary and Queue modules in this workshop; The Queue must have only a header file. ðŸ—Ž Explain in the reflection why we do not split this module into *.h and *.cpp like you did in the previous workshops.

In all classes that you create, you are allowed to add any private members that your design requires (without changing the specs)!

w3 Module (supplied)

Do not modify this module! Look at the code and make sure you understand how to instantiate a templated class.

Dictionary Module

This module has a term and it’s definition. Like you would find in a dictionary.

“`cpp class Dictionary { std::string m_term{}; std::string m_definition{}; public: const std::string&amp; getTerm() const { return m_term; } const std::string&amp; getDefinition() const { return m_definition; } Dictionary(const std::string&amp; term, const std::string&amp; definition) : m_term{ term }, m_definition{ definition }{}

// TODO: Code the missing prototype functions and operators // that the class needs in order to work with the Queue class. // Implement them in the Dictionary.cpp file. }; “`

Dictionary objects that have the same term are equal or the same in this workshop.

ðŸ—Ž In the reflection justify why it was necessary to add each one of the members you have decided to add.

Queue Module

This module represents a queue of elements of any data type (for example, queue of ints, or queue of Dictionarys, etc.).

Objects get added to the back of the queue and are removed from the front of the queue (like a line at a grocery store).

Design and code a class template named Queue. Your class holds a statically-allocated array of objects of any type. The template parameters in order of their specification are:

T: the type of any element in the queue

CAPACITY: the capacity of the collection (a non-type parameter; an integer without sign). This is the maximum number of elements that can be added to the queue.

Your Queue class object needs to know how many objects it is currently storing. This is different than the capacity. When an empty queue is made, this value is set to 0.

Class Members

An object of type T. This object will be returned by member-functions when the client requests an object that is not in the queue.

Public Members

bool push(const T&amp; item): a mutator that adds a copy of the parameter to the queue if there still is capacity. If the item has been added, this function return true; false otherwise.

pop(): a mutator that removes the first member of the queue. It creates a temporary copy of it and then shifts the rest of the queue elements forward by one index. This function returns a copy of the removed object. size(): a query that returns the current number of elements in the queue

display(): a query that receives as the parameter an output stream (with default value std::cout) and inserts into the stream all items from the collection (see the sample output for formatting hints).

operator[]: a query that receives an index as parameter and returns a copy of the element stored in the collection at the specified index. If the index is not valid (outside the boundaries of the collection), this query returns the dummy object.

Add any other private members that your design requires (without changing the specs above)!

Specialize the class-member object when type T = Dictionary and CAPACITY = 100u so the term is “Empty Term” and the definition is “Empty Substitute”. Sample Output

When the program is started with the command: ws the output should look like the one from the sample_output.txt file.

Test Your Code

To test the execution of your program, use the same data as shown in the output example above.

Upload your source code to your matrix account. Compile and run your code using the latest version of the g++ compiler (available at /usr/local/gcc/10.2.0/bin/g++) and make sure that everything works properly.

~profname.proflastname/submit 345_w3_p1 and follow the instructions.

This part represents a milestone in completing the workshop and is not marked!

Part 2 (100%)

After completing part 1, upgrade your project by adding a new derived class derived from Queue, named UniqueQueue; this class that doesn’t allow duplicates.

Queue Module

Modify the push() member function in the Queue module to enable inclusion polymorphism on the hierarchy. For the same purpose, add an empty body destructor.

No other changes are necessary to this module.

UniqueQueue Module

Create a new class named UniqueQueue that is a Queue that cannot have multiple items with the same value inside it.

Derive the UniqueQueue class template from Queue&lt;T, 100&gt; (the UniqueQueue will always have a capacity of 100 items). The UniqueQueue will have only one template parameter T.

Public Members

override the inherited function push to prevent adding an item if it already exists in the UniqueQueue.

No other members need to be added to this class.

Specializations

When T = double, the function push() will ensure that the numbers are “identical” if the difference between them is 0.005 or less (e.g., 3.001 is the same as 2.998 or 3.004).

When implementing this specialization, consider the function std::fabs().

Sample Output

When the program is started with the command: ws the output should look like the one from the sample_output.txt file.

ðŸ—Ž Reflection

Study your final solution, reread the related parts of the course notes, and make sure that you have understood the concepts covered by this workshop. This should take no less than 30 minutes of your time and the result is suggested to be at least 150 words in length.

Create a text file named reflect.txt that contains your detailed description of the topics that you have learned in completing this workshop and mention any issues that caused you difficulty and how you solved them. Include in your explanationâ€”but do not limit it toâ€”the following points: – the reason for specializing the push() member function. – the reason for defining the class variable outside the class definition. – answers to the other questions in these specifications.

To avoid deductions, refer to code in your solution as examples to support your explanations.

Submission

To test and demonstrate execution of your program use the same data as shown in the output example above.

Upload the source code and the reflection file to your matrix account. Compile and run your code using the latest version of the g++ compiler (available at /usr/local/gcc/10.2.0/bin/g++) and make sure that everything works properly.

~profname.proflastname/submit 345_w3_p2 and follow the instructions.
