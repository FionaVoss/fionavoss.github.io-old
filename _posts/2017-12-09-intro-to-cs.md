---
layout: post
title: What I Learned from Taking Intro to Computer Science as a Bootcamp Grad
---
<!-- Audience: other bootcamp grads -->

<!-- Purpose: to make the case for taking an intro to CS class and help bootcamp grads decide if they want to do it -->

This fall, one year after I completed Learn Academy’s web development bootcamp and started working as a Rails developer, I began working toward a degree in computer science. I enrolled in Oregon State’s online post-baccalaureate CS program, through which I’ll earn a second bachelor’s degree in the next two to three years.

I started my first quarter in September with one course: CS 165, Accelerated Introduction to Computer Science. A few days ago, I submitted my final project.

The course was basically an introduction to programming in C++. It is considered an “accelerated” course because it consists of 8 credits in a 12 week term, in contrast to the normal 4 credits. As a result, it is intended for students who either have prior programming experience, or who are studying full-time and can devote a lot of time to the class. Otherwise, students are advised to take the equivalent 2 intro courses separately during 2 quarters. Since I was a proficient Ruby and Javascript programmer, I felt confident about choosing the accelerated version.

Before the course started, I didn’t know much about C++. I knew it was considered a low-level language, which I understood at the time to basically mean that it is harder to work with than high-level languages like my beloved Ruby. I also knew that it was considered my many to be a pretty terrible language. So, I expected that I would not especially like programming in C++, but that I could learn more about how computers work, by becoming acquainted with a language that did less for me.

### The basics

The first few weeks were fairly straightforward. We covered data types, functions, conditions, loops, and classes. There was a lot of assigned reading, but since all of it was about concepts that I was already very familiar with, I only needed to skim the text, looking for ways that C++ was different from Ruby and JavaScript. The main difference, of course, was that C++ is statically typed, requiring you to declare the type of all your variables, class members, and function return values explicitly. As much as I love dynamically-typed Ruby, I like this feature of C++. It enforces disciplined thinking, makes code more explicit and therefore more readable, and, I can see how it could prevent certain bugs.

Pass by value vs pass by reference

During this stage of the class, learning C++ made me appreciate Ruby a lot more. It make Ruby feel “magical” in a way that I had never felt before, since I hadn’t had anything to compare it to  except JavaScript. For example, in Ruby, you can initialize an empty array, and then add any number of items to it. An array can hold objects of different classes. In C++, you have to initialize an array with a size and a class, and it can only hold elements of that class. I learned that this is because the program allocates memory for the array, and it needs to know the size and the class of the elements in order to know how much memory to allocate. This made sense, but made me wonder how Ruby worked the way it did. What did the people who wrote Ruby do to make it so flexible?

### It gets real

The first concept the covered that was truly new to me was pointers. Pointers are thing that Ruby uses behind the scenes, which has some implications Ruby developers should know about, but you don’t interact with pointers directly when programming in Ruby. The concept of pointers was not too difficult for me, but I’m still not comfortable with the syntax. I wouldn’t be able to tell you where to use the `&` or `*	` symbols without a cheat sheet in front of me. However, there were plenty of opportunities to practice using pointers throughout the last half of the course, and I feel pretty good about them.

The next challenging topic was dynamic memory allocation. I knew this was going to be something different when the textbook warned that making a mistake here could crash your entire computer! Fortunately, I never got myself into that kind of trouble. But, if I never have to manage my own memory again, I won’t be sad about it.

Searching & sorting, Analysis of algorithms

this, constant member functions, friend classes, copy constructors, operator overloading, convert constructors, aggregation, composition, inheritance, protected, overriding

### Demystifying the Magic

Then we learned about template classes, dynamic binding, linked lists, stacks, and queues. This section was challenging, but looking back it was the most valuable part of the course because it helped demystify some of the "magic" that I mentioned earlier. For example, a linked list is a data structure consisting of nodes, each of which stores a value. The nodes are connected because each node stores a pointer to the next node. It is similar to an array because elements are stored in a particular order. You can iterate over a linked list like an array, for example if you wanted to print each element or find the element at a particular index. Unlike a C++ array, but like a Ruby array, a linked list does not have a fixed length, so you can add as many elements as you need to. Now Ruby arrays don't feel so magical, because I know how to implement similar functionality.

### Overall experience & what's next

I am glad I took this course. While I was already familiar with many of the concepts it covered, I learned a lot of new things.

I was on the fence at first, but having taken this course, I have decided that I do want to continue with the OSU program and work toward earning a computer science degree.

This course has introduced me to concepts that will help me in future courses like Algorithms, Data Structures, Operating Systems, and Assembly Language. So, from the perspective of a student, I am glad that took this course. It covered important fundamentals that I hadn't learned in a year of professional Ruby development.

From the perspective of a Rails developer, I also think this class was useful. I probably won't use big O notation to formally analyze algorithms at work, but being aware of it will help me write more efficient code. And knowing how pointers work means that I won't be surprised when they cause strange behavior in Ruby.

### My advice for other bootcamp grads

If you're already interested in going back to school for a computer science degree, you'll need to take intro to CS. Assuming you are mostly familiar with high-level languages like Ruby, Python, or JavaScript, an introductory course in a low-level language like C++ can teach you a lot. Be prepared to be challenged.

If you don't need to take the class for a degree, you can still benefit from learning C++, although it's not for everyone. If you are mostly interested in what you can build, you can stick with high-level languages. But if you want to learn how your tools work under the hood, consider learning C++. It's helped me understand *why* Ruby works better than a year of programming *in* Ruby did.
