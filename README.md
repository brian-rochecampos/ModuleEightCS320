CS-320 Portfolio Reflection

1. How can I ensure that my code, program, or software is functional and secure?

I can make sure my code works by writing tests for all the main features and for the bad data too. In my projects, I used JUnit tests to check that I could add, update, and delete contacts, tasks, and appointments. I also tested what happened if I tried to put in bad data like null values, too-long IDs, or dates in the past. This made me confident that my program wouldn’t just accept anything and break later. Validating inputs before saving them is also a big part of keeping the program secure.

2. How do I interpret user needs and incorporate them into a program?

I look at the requirements that are given and turn them into checks inside the code. For example, if the user needs the phone number to be exactly 10 digits, I write code that throws an exception if it’s not 10 digits. I did the same thing with lengths for names, IDs, and descriptions. Writing tests for each requirement also helps me make sure I didn’t miss anything the user asked for.

3. How do I approach designing software?

I start by thinking about what classes I’ll need and what they should do. For this course, I made classes for Contact, Task, and Appointment, and then made services to manage them. After that, I think about how to test everything and write the tests early so I can fix any problems right away. This approach helps me stay organized and makes sure I don’t wait until the end to find out something is broken.
